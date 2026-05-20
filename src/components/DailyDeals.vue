<script>

</script>

<template>
    <!-- Promo Bar -->
    <div class="bg-primary text-black py-2 px-4 text-center text-base">
        Free shipping on orders over $50 | Flash sales end in <span class="font-bold">02:15:40</span>
    </div>

    <!-- Hero Banner with Countdown -->
    <section class="bg-gradient-to-r from-primary/10 to-secondary/10 py-12 px-4">
        <div class="container mx-auto text-center">
            <h2 class="text-[clamp(1.8rem,4vw,3rem)] font-bold mb-3">Daily Deals & Flash Sales</h2>
            <p class="text-gray-700 max-w-2xl mx-auto mb-6">Discover amazing prices on trending items —
                updated every 24 hours.</p>

            <!-- Countdown Timer -->
            <div class="flex justify-center gap-4 mb-6">
                <div class="bg-white rounded-lg w-16 h-16 flex flex-col items-center justify-center card-shadow">
                    <span class="text-xl font-bold text-primary">02</span>
                    <span class="text-xs text-gray-600">Days</span>
                </div>
                <div class="bg-white rounded-lg w-16 h-16 flex flex-col items-center justify-center card-shadow">
                    <span class="text-xl font-bold text-primary">15</span>
                    <span class="text-xs text-gray-600">Hours</span>
                </div>
                <div class="bg-white rounded-lg w-16 h-16 flex flex-col items-center justify-center card-shadow">
                    <span class="text-xl font-bold text-primary">30</span>
                    <span class="text-xs text-gray-600">Mins</span>
                </div>
                <div class="bg-white rounded-lg w-16 h-16 flex flex-col items-center justify-center card-shadow">
                    <span class="text-xl font-bold text-primary">45</span>
                    <span class="text-xs text-gray-600">Secs</span>
                </div>
            </div>

            <div class="flex flex-wrap justify-center gap-3">
                <span class="bg-white px-4 py-2 rounded-full card-shadow font-medium">Up to 70% Off</span>
                <span class="bg-white px-4 py-2 rounded-full card-shadow font-medium">Free Shipping</span>
                <span class="bg-white px-4 py-2 rounded-full card-shadow font-medium">Limited Stock</span>
                <span class="bg-white px-4 py-2 rounded-full card-shadow font-medium">Top Rated</span>
            </div>
        </div>
    </section>

    <!-- Category Tabs -->
    <section class="border-b border-gray-200 px-4">
        <div class="container mx-auto">
            <div class="flex gap-6 overflow-x-auto scrollbar-hide">
                <button class="tab-btn py-3 px-1 border-b-2 border-blue-500 text-blue-500 font-medium whitespace-nowrap"
                    data-target="all">All Deals</button>
                <button
                    class="tab-btn py-3 px-1 border-b-2 border-transparent text-gray-600 hover:text-blue-500 cursor-pointer font-medium whitespace-nowrap"
                    data-target="electronics">Electronics</button>
                <button
                    class="tab-btn py-3 px-1 border-b-2 border-transparent text-gray-600 hover:text-blue-500 cursor-pointer font-medium whitespace-nowrap"
                    data-target="fashion">Fashion</button>
                <button
                    class="tab-btn py-3 px-1 border-b-2 border-transparent text-gray-600 hover:text-blue-500 cursor-pointer font-medium whitespace-nowrap"
                    data-target="home">Home & Garden</button>
                <button
                    class="tab-btn py-3 px-1 border-b-2 border-transparent text-gray-600 hover:text-blue-500 cursor-pointer font-medium whitespace-nowrap"
                    data-target="sports">Sports & Outdoors</button>
                <button
                    class="tab-btn py-3 px-1 border-b-2 border-transparent text-gray-600 hover:text-blue-500 cursor-pointer font-medium whitespace-nowrap"
                    data-target="beauty">Beauty & Health</button>
            </div>
        </div>
    </section>

    <!-- Main Content with Filters -->
    <section class="py-8 px-4">
        <div class="container mx-auto flex flex-col lg:flex-row gap-6">
            <!-- Sidebar Filters -->
            <aside
                class="filters-sidebar w-full lg:w-1/4 bg-white rounded-xl p-5 card-shadow h-fit transition-transform duration-300">
                <div class="flex items-center justify-between mb-4">
                    <h3 class="font-bold text-lg">Filters</h3>
                    <button class="text-sm text-primary">Reset All</button>
                </div>

                <!-- Price Range -->
                <div class="mb-5">
                    <h4 class="font-medium mb-2">Price Range</h4>
                    <div class="flex gap-2">
                        <input type="number" placeholder="$ Min" class="w-1/2 px-2 py-1 border rounded text-sm">
                        <input type="number" placeholder="$ Max" class="w-1/2 px-2 py-1 border rounded text-sm">
                    </div>
                </div>

                <!-- Discount -->
                <div class="mb-5">
                    <h4 class="font-medium mb-2">Discount</h4>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> 30% or more
                    </label>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> 50% or more
                    </label>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> 70% or more
                    </label>
                </div>

                <!-- Condition -->
                <div class="mb-5">
                    <h4 class="font-medium mb-2">Condition</h4>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> New
                    </label>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> Refurbished
                    </label>
                    <label class="flex items-center gap-2 text-sm mb-1">
                        <input type="checkbox"> Used
                    </label>
                </div>

                <!-- Rating -->
                <div class="mb-5">
                    <h4 class="font-medium mb-2">Customer Rating</h4>
                   
                    <label class="flex items-center gap-1 text-sm mb-1">
                        <input type="checkbox">4<span><svg
                                class="w-3 h-3 text-yellow-500 " aria-hidden="true"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor"
                                viewBox="0 0 24 24">
                                <path
                                    d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                            </svg>
                        </span> & up
                    </label>
                    <label class="flex items-center gap-1 text-sm mb-1">
                        <input type="checkbox">3<span><svg
                                class="w-3 h-3 text-yellow-500 " aria-hidden="true"
                                xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor"
                                viewBox="0 0 24 24">
                                <path
                                    d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                            </svg>
                        </span> & up
                    </label>
                </div>

                <button class="w-full bg-primary text-white py-2 rounded-lg hover:bg-primary/90">Apply
                    Filters</button>
            </aside>

            <!-- Deals Grid -->
            <div class="w-full lg:w-3/4">
                <!-- Sort Bar -->
                <div class="bg-white rounded-xl p-3 mb-6 card-shadow flex flex-wrap items-center justify-between gap-3">
                    <p class="text-sm text-gray-600"><span class="font-bold">247</span> products found</p>
                    <div class="flex items-center gap-2">
                        <label class="text-sm text-gray-600">Sort by:</label>
                        <select
                            class="text-sm border rounded px-2 py-1 focus:outline-none focus:ring-1 focus:ring-blue-500">
                            <option>Best Match</option>
                            <option>Price: Low to High</option>
                            <option>Price: High to Low</option>
                            <option>Top Rated</option>
                            <option>Newest First</option>
                        </select>
                    </div>
                </div>

                <!-- Tab Content: All Deals -->
                <div id="all" class="tab-content">
                    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
                        <!-- Deal Item 1 -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?ixlib=rb-4.0.3&auto=format&fit=crop&w=500&q=80"
                                    alt="Wireless Headphones"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute top-3 left-3 bg-danger text-white text-sm font-bold px-2 py-1 rounded bg-red-500">-45%</span>
                                <span class="absolute top-3 left-3 mt-8 bg-success text-white badge">Free
                                    Ship</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">Premium Wireless Noise
                                    Cancelling Headphones</h4>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="text-lg font-bold text-primary">$89.99</span>
                                    <span class="text-gray-500 line-through text-sm">$165.00</span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- Deals Item-2 -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://images.unsplash.com/photo-1733556046668-4ed1e54e22e5?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDgxfHx8ZW58MHx8fHx8"
                                    alt="Wireless Bluetooth Earbuds"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute top-3 left-3 bg-danger text-white text-sm font-bold px-2 py-1 rounded bg-red-500">-37%</span>
                                <span class="absolute top-3 left-3 mt-8 bg-success text-white badge">Free
                                    Ship</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">Wireless Bluetooth Earbuds - White
                                </h4>
                                <div class="flex items-center gap-2 mb-3 mt-8">
                                    <span class="text-lg font-bold text-primary">$49.99</span>
                                    <span class="text-gray-500 line-through text-sm">$79.99</span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- third deals item -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://thfvnext.bing.com/th/id/OIP.amyPYnM57ZeryFNvVz_ZtwHaHa?w=197&h=196&c=7&r=0&o=7&cb=thfvnextfalcon&dpr=1.3&pid=1.7&rm=3"
                                    alt="Polo Blue"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute top-3 left-3 text-white text-sm font-bold px-2 py-1 rounded bg-red-500">-37%</span>
                                <span class="absolute top-3 left-3 mt-8 bg-success text-white badge">Free
                                    Ship</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">POLO BLUE by Ralph Lauren 4.2 oz edt
                                    Cologne for men New in Box</h4>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="text-lg font-bold text-primary">$51.57</span>
                                    <span class="text-gray-500 line-through text-sm">$112.00</span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- fourth deals item -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://i.ebayimg.com/images/g/-VcAAeSwG3BofarO/s-l225.jpg" alt="Polo Blue"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute bg-red-500 top-3 left-3 bg-danger text-white text-sm font-bold px-2 py-1 rounded">-49%</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">PETKIT PuraMAX 2 Automatic Smart Cat
                                    Litter Box Self-Cleaning Cat Litter Box</h4>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="text-lg font-bold text-primary">$179.89</span>
                                    <span class="text-gray-500 line-through text-sm">$349.99</span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- fifth deals item -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://i.ebayimg.com/images/g/UtIAAeSwWvdqBOYJ/s-l1600.webp" alt="Polo Blue"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute bg-red-500 top-3 left-3 bg-danger text-white text-sm font-bold px-2 py-1 rounded">-76%</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">14K Gold 1/4ct Round Lab Grown Diamond Solitaire Bezel Pendant Necklace</h4>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="text-lg font-bold text-primary">$215.95</span>
                                    <span class="text-gray-500 line-through text-sm">$899.95 </span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- sixth deals item -->
                        <div class="bg-white rounded-xl overflow-hidden card-shadow card-hover group">
                            <div class="relative">
                                <img src="https://i.ebayimg.com/images/g/Yt0AAeSw9cNqDI33/s-l500.webp" alt="Polo Blue"
                                    class="w-full h-48 object-cover group-hover:scale-105 transition-transform duration-300">
                                <span
                                    class="absolute bg-red-500 top-3 left-3 bg-danger text-white text-sm font-bold px-2 py-1 rounded">-20%</span>
                                <button
                                    class="wishlist-btn absolute top-3 right-3 bg-white/80 backdrop-blur-sm p-2 rounded-full hover:bg-white transition-colors">
                                    <i class="fa fa-heart-o text-gray-700"></i>
                                </button>
                                <!-- Quick View Button -->
                                <button
                                    class="absolute bottom-0 left-0 right-0 bg-dark/70 text-white py-2 text-sm opacity-0 group-hover:opacity-100 transition-opacity">
                                    Quick View
                                </button>
                            </div>
                            <div class="p-4">
                                <h4 class="font-medium text-dark mb-2 line-clamp-2">Acer Aspire 3 15.6" Ryzen 5 7520U 7000 Ser 16GB 1TB SSD Radeon Graphics Refurb</h4>
                                <div class="flex items-center gap-2 mb-3">
                                    <span class="text-lg font-bold text-primary">$377.99</span>
                                    <span class="text-gray-500 line-through text-sm">$929.99 </span>
                                </div>
                                <div class="flex items-center justify-between mb-2">
                                    <div class="flex items-center text-warning text-sm">
                                        <i class="fa fa-star"></i>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>