<script>
import Navbar from './components/Navbar.vue';
import Modal from './Modal/Modal.vue';
import Home from './components/Home.vue';
import DailyDeals from './components/DailyDeals.vue';
import Sell from './components/Sell.vue';
import Saved from './components/Saved.vue';
import Krys from './components/Krys.vue';
import Footer from './components/Footer.vue';
import Help from './components/Help.vue';
import Register from './Modal/Register.vue';
export default {
    components: {
        Navbar,
        Modal,
        Home,
        DailyDeals,
        Sell,
        Saved,
        Krys,
        Footer,
        Help,
        Register
    },
    data() {
        return {
            modal: false,
            currentPage: 'Home',
        }
    },
    methods: {
        signBtn() {
            this.modal = true;
        },
        closeBtn() {
            this.modal = false;
        },
        changePage(page) {
            this.currentPage = page;

        }
    }
}

</script>

<template>
    <Navbar @show="signBtn" @goTo="changePage" />
    <Home v-if="currentPage === 'Home'" />
    <DailyDeals v-if="currentPage === 'DailyDeals'" />
    <Sell v-if="currentPage === 'Sell'" />
    <Saved v-if="currentPage === 'Saved'" />
    <Krys v-if="currentPage === 'Krys'" />
    <Help v-if="currentPage === 'Help'" />
    <Modal v-if="modal" @closeModal="closeBtn" />
    <Register />
    
    <Footer/>
</template>
