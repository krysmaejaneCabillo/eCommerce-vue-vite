<script>

</script>

<template>

    <!-- <style type="text/tailwindcss">
        @layer utilities {
      .content-auto {
        content-visibility: auto;
      }
      .shadow-soft {
        box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
      }
      .transition-custom {
        transition: all 0.3s ease;
      }
    }
  </style> -->


    <div class="bg-gray-50 text-gray-800 w-full">

        <!-- Hero Section -->
        <section class="relative h-[80vh] flex items-center overflow-hidden">
            <div class="absolute inset-0 z-0">
                <img src="https://images.unsplash.com/photo-1556228453-efd6c1ff04f6?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80"
                    alt="Selling products" class="w-full h-full object-cover" loading="lazy" />
                <div class="absolute inset-0 bg-gradient-to-r from-black/60 to-transparent"></div>
            </div>

            <div class="container mx-auto px-4 relative z-10">
                <div class="max-w-xl text-white space-y-6">
                    <h1 class="text-[clamp(2.5rem,5vw,4rem)] font-bold leading-tight">
                        Turn Your Items Into Cash
                    </h1>
                    <p class="text-lg md:text-xl text-gray-100">
                        Join millions of sellers worldwide. List anything from collectibles to electronics, fashion to
                        furniture — reach buyers instantly.
                    </p>
                    <div class="flex flex-wrap gap-4 pt-2">
                        <a href="#start-selling"
                            class="bg-[#F5AF02] hover:bg-[#e09e00] text-white px-8 py-3 rounded-lg font-semibold shadow-lg transition-custom transform hover:-translate-y-1">
                            Start Selling
                        </a>
                        <a href="#how-it-works"
                            class="bg-white/20 backdrop-blur-sm hover:bg-white/40 text-white border border-white/40 px-8 py-3 rounded-lg font-semibold transition-custom">
                            Learn More
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Why Sell With Us -->
        <section class="py-20 bg-white">
            <div class="container mx-auto px-4">
                <div class="text-center max-w-2xl mx-auto mb-16">
                    <h2 class="text-[clamp(1.8rem,3vw,2.8rem)] font-bold text-gray-800">Why Sell On Our Platform?</h2>
                    <p class="text-gray-600 mt-4">Trusted by sellers everywhere. We make selling simple, safe, and
                        profitable.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <!-- Card 1 -->
                    <div class="bg-gray-50 rounded-2xl p-8 shadow-soft hover:shadow-lg transition-custom group">
                        <div
                            class="w-30 h-30 overflow-hidden bg-[#0064D2]/10 text-[#0064D2] rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-[#0064D2] group-hover:text-white transition-custom">
                           <img class="w-30 h-30"  src="https://images.unsplash.com/photo-1614028674026-a65e31bfd27c?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8ZWNvbm9taWMlMjBncm93dGh8ZW58MHx8MHx8fDA%3D" alt="">
                        </div>
                        <h3 class="text-xl font-semibold mb-3">Global Reach</h3>
                        <p class="text-gray-600">Sell to buyers in over 190 countries. Your items get seen by millions
                            of active users daily.</p>
                    </div>

                    <!-- Card 2 -->
                    <div class="bg-gray-50 rounded-2xl p-8 shadow-soft hover:shadow-lg transition-custom group">
                        <div
                            class="w-30 h-30 overflow-hidden bg-[#0064D2]/10 text-[#0064D2] rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-[#0064D2] group-hover:text-white transition-custom">
                            <img class="w-30 h-30" src="https://plus.unsplash.com/premium_photo-1733317239304-a6bf462a2596?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MzJ8fHNlY3VyaXR5fGVufDB8fDB8fHww" alt="">
                        </div>
                        <h3 class="text-xl font-semibold mb-3">Safe & Secure</h3>
                        <p class="text-gray-600">Protected payments, seller protection programs, and 24/7 support so you
                            never sell alone.</p>
                    </div>

                    <!-- Card 3 -->
                    <div class="bg-gray-50 rounded-2xl p-8 shadow-soft hover:shadow-lg transition-custom group">
                        <div
                            class="w-30 h-30 overflow-hidden bg-[#0064D2]/10 text-[#0064D2] rounded-xl flex items-center justify-center text-2xl mb-6 group-hover:bg-[#0064D2] group-hover:text-white transition-custom">
                            <img class="w-30 h-30" src="https://thfvnext.bing.com/th/id/OIP.-crXPVHKUvaOnhldztrHVgHaEC?w=327&h=180&c=7&r=0&o=7&cb=thfvnextfalcon&dpr=1.3&pid=1.7&rm=3" alt="">
                        </div>
                        <h3 class="text-xl font-semibold mb-3">Low Fees, High Returns</h3>
                        <p class="text-gray-600">Competitive pricing structure. Keep more of what you earn with our
                            straightforward fee system.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- How It Works -->
        <section id="how-it-works" class="py-20 bg-gray-50">
            <div class="container mx-auto px-4">
                <div class="text-center max-w-2xl mx-auto mb-16">
                    <h2 class="text-[clamp(1.8rem,3vw,2.8rem)] font-bold text-gray-800">How It Works</h2>
                    <p class="text-gray-600 mt-4">Start selling in just 4 simple steps</p>
                </div>

                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                    <!-- Step 1 -->
                    <div class="text-center">
                        <div class="relative mb-8">
                            <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80"
                                alt="Create account" class="w-24 h-24 rounded-full object-cover mx-auto shadow-md" />
                            <span
                                class="absolute -top-2 -right-2 bg-[#F5AF02] text-white w-8 h-8 rounded-full flex items-center justify-center font-bold text-lg">1</span>
                        </div>
                        <h3 class="font-semibold text-lg mb-2">Create Account</h3>
                        <p class="text-gray-600 text-sm">Sign up for free and set up your seller profile in minutes.</p>
                    </div>

                    <!-- Step 2 -->
                    <div class="text-center">
                        <div class="relative mb-8">
                            <img src="https://images.unsplash.com/photo-1560472354-b33ff0c44a43?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80"
                                alt="List item" class="w-24 h-24 rounded-full object-cover mx-auto shadow-md" />
                            <span
                                class="absolute -top-2 -right-2 bg-[#F5AF02] text-white w-8 h-8 rounded-full flex items-center justify-center font-bold text-lg">2</span>
                        </div>
                        <h3 class="font-semibold text-lg mb-2">List Your Item</h3>
                        <p class="text-gray-600 text-sm">Add photos, description, and price — use our smart suggestions
                            to sell faster.</p>
                    </div>

                    <!-- Step 3 -->
                    <div class="text-center">
                        <div class="relative mb-8">
                            <img src="https://images.unsplash.com/photo-1557821552-17105176677c?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80"
                                alt="Get buyer" class="w-24 h-24 rounded-full object-cover mx-auto shadow-md" />
                            <span
                                class="absolute -top-2 -right-2 bg-[#F5AF02] text-white w-8 h-8 rounded-full flex items-center justify-center font-bold text-lg">3</span>
                        </div>
                        <h3 class="font-semibold text-lg mb-2">Get Orders</h3>
                        <p class="text-gray-600 text-sm">Receive offers or direct purchases — we notify you instantly.
                        </p>
                    </div>

                    <!-- Step 4 -->
                    <div class="text-center">
                        <div class="relative mb-8">
                            <img src="https://thfvnext.bing.com/th/id/OIP.-crXPVHKUvaOnhldztrHVgHaEC?w=327&h=180&c=7&r=0&o=7&cb=thfvnextfalcon&dpr=1.3&pid=1.7&rm=3"
                                alt="Get paid" class="w-24 h-24 rounded-full object-cover mx-auto shadow-md" />
                            <span
                                class="absolute -top-2 -right-2 bg-[#F5AF02] text-white w-8 h-8 rounded-full flex items-center justify-center font-bold text-lg">4</span>
                        </div>
                        <h3 class="font-semibold text-lg mb-2">Get Paid</h3>
                        <p class="text-gray-600 text-sm">Ship the item and receive fast, secure payments directly to
                            your account.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- CTA Section -->
        <section id="start-selling" class="py-20 bg-[#0064D2] text-white relative overflow-hidden">
            <div class="absolute inset-0 opacity-10">
                <img src="https://images.unsplash.com/photo-1523966211575-eb4a1d357ddb?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80"
                    alt="Background pattern" class="w-full h-full object-cover" />
            </div>
            <div class="container mx-auto px-4 text-center relative z-10">
                <h2 class="text-[clamp(1.8rem,3vw,3rem)] font-bold mb-6">Ready To Start Selling?</h2>
                <p class="text-blue-100 max-w-xl mx-auto mb-8 text-lg">Join thousands of successful sellers today. It’s
                    free to list, easy to manage, and profitable to grow.</p>
                <a href="#"
                    class="bg-[#F5AF02] hover:bg-[#e09e00] text-white px-2 lg:px-10 sm:px-5 sm-text-sm py-4 rounded-lg font-semibold text-lg shadow-lg transition-custom transform hover:-translate-y-1">
                    Create Your Seller Account
                </a>
            </div>
        </section>

        <!-- Form Section -->
        <section class="py-20 bg-white">
            <div class="container mx-auto px-4 max-w-3xl">
                <div class="text-center mb-12">
                    <h2 class="text-[clamp(1.5rem,2.5vw,2.2rem)] font-bold text-gray-800">Register As A Seller</h2>
                    <p class="text-gray-600 mt-2">Fill in your details and start your selling journey</p>
                </div>

                <form class="bg-gray-50 rounded-2xl p-8 shadow-soft">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                        <div>
                            <label class="block text-gray-700 font-medium mb-2">Full Name</label>
                            <input type="text"
                                class="w-full px-4 py-3 rounded-lg border border-gray-200 focus:ring-2 focus:ring-[#0064D2]/20 focus:border-[#0064D2] outline-none transition"
                                placeholder="Zy Doe" />
                        </div>
                        <div>
                            <label class="block text-gray-700 font-medium mb-2">Email Address</label>
                            <input type="email"
                                class="w-full px-4 py-3 rounded-lg border border-gray-200 focus:ring-2 focus:ring-[#0064D2]/20 focus:border-[#0064D2] outline-none transition"
                                placeholder="zy@example.com" />
                        </div>
                    </div>

                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">Business Name (Optional)</label>
                        <input type="text"
                            class="w-full px-4 py-3 rounded-lg border border-gray-200 focus:ring-2 focus:ring-[#0064D2]/20 focus:border-[#0064D2] outline-none transition"
                            placeholder="Your Shop Name" />
                    </div>

                    <div class="mb-6">
                        <label class="block text-gray-700 font-medium mb-2">What do you plan to sell?</label>
                        <textarea class="w-full px-4 py-3 rounded-lg border border-gray-200 " name="" id=""></textarea>
                    </div>
                </form>
            </div>
        </section>
    </div>

</template>