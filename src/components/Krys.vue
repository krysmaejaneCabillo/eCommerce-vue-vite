<script>

</script>

<template>

    <div class="antialiased">
        <!-- Hero Section -->
        <section class="bg-neutral py-12 md:py-16">
            <div class="container mx-auto px-4">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div class="order-2 md:order-1">
                        <h1 class="text-[clamp(2rem,4vw,3.5rem)] font-bold leading-tight text-dark mb-4">
                            Buy & Sell <br> Anything, Anywhere
                        </h1>
                        <p class="text-gray-600 text-lg mb-6 max-w-lg">
                            Discover unique items, great deals, and connect with sellers worldwide. Just like the
                            marketplace you trust, but refined.
                        </p>
                        <div class="flex flex-wrap gap-3">
                            <a href="#categories"
                                class="bg-primary text-white px-6 py-3 rounded-lg font-medium hover:bg-primary/90 transition-colors">
                                Browse Categories
                            </a>
                            <a href="#featured"
                                class="border border-primary text-primary px-6 py-3 rounded-lg font-medium hover:bg-primary/5 transition-colors">
                                Featured Items
                            </a>
                        </div>
                    </div>
                    <div class="order-1 md:order-2 rounded-2xl overflow-hidden card-shadow">
                        <img src="https://images.unsplash.com/photo-1557821552-17105176677c?ixlib=4.0.3&auto=format&fit=crop&w=1200&q=80"
                            alt="Marketplace" class="w-full h-[300px] md:h-[400px] object-cover">
                    </div>
                </div>
            </div>
        </section>

        <!-- Categories -->
        <section id="categories" class="py-12 bg-white">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl md:text-3xl font-bold text-center mb-10">Shop by Category</h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-4 md:gap-6">
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://images.unsplash.com/photo-1517336714731-489689fd1ca8?ixlib=4.0.3&auto=format&fit=crop&w=200&q=80"
                            alt="Electronics" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Electronics</span>
                    </a>
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://images.unsplash.com/photo-1696218359361-b088f32f86b8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDJ8fHxlbnwwfHx8fHw%3D"
                            alt="Fashion" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Fashion</span>
                    </a>
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://plus.unsplash.com/premium_photo-1744839108979-0546638c54b8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDIwfHx8ZW58MHx8fHx8"
                            alt="Home & Living" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Home & Living</span>
                    </a>
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://images.unsplash.com/photo-1647849208531-65544855dd46?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDIzfHx8ZW58MHx8fHx8"
                            alt="Sports" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Jewelry</span>
                    </a>
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://images.unsplash.com/photo-1512496015851-a90fb38ba796?q=80&w=735&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
                            alt="Beauty" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Beauty</span>
                    </a>
                    <a href="#"
                        class="group flex flex-col items-center p-4 rounded-xl bg-neutral hover:bg-neutral/70 transition-colors card-shadow">
                        <img src="https://images.unsplash.com/photo-1545609904-f2f11654638d?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTI3fHxjb2xsZWN0aWJsZXxlbnwwfHwwfHx8MA%3D%3D"
                            alt="Collectibles" class="w-30 h-30 mb-3">
                        <span class="font-medium text-center group-hover:text-blue-500">Collectibles</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- Featured Products -->
        <section id="featured" class="py-12 bg-neutral/50">
            <div class="container mx-auto px-4">
                <h2 class="text-2xl md:text-3xl font-bold text-center mb-10">Featured Deals</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
                    <!-- Product Card 1 -->
                    <div class="bg-white rounded-xl overflow-hidden card-shadow group">
                        <div class="h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=4.0.3&auto=format&fit=crop&w=500&q=80"
                                alt="Wireless Headphones"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                        </div>
                        <div class="p-4">
                            <span class="text-sm text-gray-500">Electronics</span>
                            <h3 class="font-semibold text-lg mt-1 mb-2 line-clamp-2">Premium Wireless Noise Cancelling
                                Headphones</h3>
                            <div class="flex items-center justify-between">
                                <span class="text-xl font-bold text-dark">$129.99</span>
                                <span class="text-sm text-green-600 font-medium">Free Shipping</span>
                            </div>
                            <button
                                class="w-full mt-3 bg-secondary text-white py-2 rounded-lg hover:bg-secondary/90 transition-colors">
                                Add to Cart
                            </button>
                        </div>
                    </div>

                    <!-- Product Card 2 -->
                    <div class="bg-white rounded-xl overflow-hidden card-shadow group">
                        <div class="h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1542496658-e33a6d0d50f6?ixlib=4.0.3&auto=format&fit=crop&w=500&q=80"
                                alt="Classic Watch"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                        </div>
                        <div class="p-4">
                            <span class="text-sm text-gray-500">Accessories</span>
                            <h3 class="font-semibold text-lg mt-1 mb-2 line-clamp-2">Minimalist Stainless Steel Wrist
                                Watch</h3>
                            <div class="flex items-center justify-between">
                                <span class="text-xl font-bold text-dark">$89.50</span>
                                <span class="text-sm text-green-600 font-medium">On Sale</span>
                            </div>
                            <button
                                class="w-full mt-3 bg-secondary text-white py-2 rounded-lg hover:bg-secondary/90 transition-colors">
                                Add to Cart
                            </button>
                        </div>
                    </div>

                    <!-- Product Card 3 -->
                    <div class="bg-white rounded-xl overflow-hidden card-shadow group">
                        <div class="h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1657603471016-b3c13c3b5ff5?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8N3x8R2VudWluZSUyMExlYXRoZXIlMjBDcm9zc2JvZHklMjBCYWclMjAtJTIwQnJvd258ZW58MHx8MHx8fDA%3D"
                                alt="Leather Bag"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                        </div>
                        <div class="p-4">
                            <span class="text-sm text-gray-500">Fashion</span>
                            <h3 class="font-semibold text-lg mt-1 mb-2 line-clamp-2">Genuine Leather Crossbody Bag -
                                Brown</h3>
                            <div class="flex items-center justify-between">
                                <span class="text-xl font-bold text-dark">$145.00</span>
                                <span class="text-sm text-green-600 font-medium">Top Rated</span>
                            </div>
                            <button
                                class="w-full mt-3 bg-secondary text-white py-2 rounded-lg hover:bg-secondary/90 transition-colors">
                                Add to Cart
                            </button>
                        </div>
                    </div>

                    <!-- Product Card 4 -->
                    <div class="bg-white rounded-xl overflow-hidden card-shadow group">
                        <div class="h-48 overflow-hidden">
                            <img src="https://plus.unsplash.com/premium_photo-1777867682652-2cb98ef8c77c?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mjl8fHNtYXJ0JTIwYmx1ZXRvb3RoJTIwc3BlYWtlcnxlbnwwfHwwfHx8MA%3D%3D"
                                alt="Smart Speaker"
                                class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300">
                        </div>
                        <div class="p-4">
                            <span class="text-sm text-gray-500">Electronics</span>
                            <h3 class="font-semibold text-lg mt-1 mb-2 line-clamp-2">Portable Smart Bluetooth Speaker
                            </h3>
                            <div class="flex items-center justify-between">
                                <span class="text-xl font-bold text-dark">$49.99</span>
                                <span class="text-sm text-green-600 font-medium">Best Seller</span>
                            </div>
                            <button
                                class="w-full mt-3 bg-secondary text-white py-2 rounded-lg hover:bg-secondary/90 transition-colors">
                                Add to Cart
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>