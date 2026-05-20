<script>

</script>

<template>
    <div class="bg-gray-50 text-gray-800 font-sans">
        <main>
            <!-- Hero Banner -->
            <section class="max-w-7xl mx-auto px-3 sm:px-4 lg:px-6 py-6 sm:py-8">
                <div
                    class="rounded-xl overflow-hidden shadow-md bg-gradient-to-r from-blue-600 to-indigo-700 text-white">
                    <div class="grid md:grid-cols-2 items-center">
                        <div class="p-6 sm:p-8 lg:p-10 space-y-3 sm:space-y-4">
                            <h1 class="text-[clamp(1.5rem,4vw,2.5rem)] font-bold leading-tight">
                                Great Deals on Top Brands
                            </h1>
                            <p class="text-blue-100 text-base sm:text-lg">
                                Shop millions of products with unbeatable prices and fast shipping.
                            </p>
                            <a href="#"
                                class="inline-block bg-white text-blue-700 font-medium px-5 sm:px-6 py-2.5 rounded-lg shadow hover:shadow-md transition-all">
                                Shop Now
                            </a>
                        </div>
                        <div class="hidden md:block p-4">
                            <img src="https://picsum.photos/id/26/600/400" alt="Hero banner"
                                class="w-full h-auto rounded-lg object-cover" />
                        </div>
                    </div>
                </div>
            </section>

            <!-- Categories Section -->
            <section class="max-w-7xl mx-auto px-3 sm:px-4 lg:px-6 py-6 sm:py-8">
                <h2 class="text-xl sm:text-2xl font-bold mb-4 sm:mb-6">Shop by Category</h2>
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://plus.unsplash.com/premium_photo-1687854992749-e15cba89631d?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8Z2FtZSUyMHBhZHxlbnwwfHwwfHx8MA%3D%3D" alt="Electronics"
                            class="w-30 h-30  mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Electronics</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://images.unsplash.com/photo-1492707892479-7bc8d5a4ee93?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTV8fGZhc2hpb258ZW58MHx8MHx8fDA%3D" alt="Fashion"
                            class="w-30 h-30  mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Fashion</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://images.unsplash.com/photo-1509099233820-42783cca6408?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDN8fGhvbWUlMjBhbmQlMjBsaXZpbmclMjBwcm9kdWN0fGVufDB8fDB8fHww" alt="Home & Living"
                            class="w-30 h-30 mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Home & Living</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://images.unsplash.com/photo-1762089423685-60f5cef02cda?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Nzl8fGNvbGxlY3RpYmxlJTIwcHJvZHVjdHN8ZW58MHx8MHx8fDA%3D" alt="Collectibles"
                            class="w-30 h-30 mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Collectibles</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://images.unsplash.com/photo-1748332505463-b2fd1ce28e07?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fGpld2xlcnklMjBzZXR8ZW58MHx8MHx8fDA%3D" alt="Motors"
                            class="w-30 h-30 mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Jewelry</span>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 text-center">
                        <img src="https://images.unsplash.com/photo-1596462502278-27bfdc403348?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8YmVhdXR5fGVufDB8fDB8fHww" alt="Beauty"
                            class="w-30 h-30 mx-auto mb-2 sm:mb-3" />
                        <span class="text-sm font-medium text-gray-700 cursor-pointer hover:text-blue-600">Beauty</span>
                    </div>
                </div>
            </section>

            <!-- Recommended Products -->
            <section class="max-w-7xl mx-auto px-3 sm:px-4 lg:px-6 py-6 sm:py-8 bg-white/50">
                <h2 class="text-xl sm:text-2xl font-bold mb-4 sm:mb-6">Recommended for You</h2>
                <div
                    class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 xl:grid-cols-5 gap-4 sm:gap-5">
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-lg transition-shadow overflow-hidden group">
                        <div>
                            <img src="https://images.unsplash.com/photo-1545127398-14699f92334b?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8d2lyZWxlc3MlMjBoZWFkcGhvbmVzfGVufDB8fDB8fHww" alt="Product"
                                class="w-full h-40 sm:h-48 object-cover group-hover:scale-105 transition-transform duration-300" />
                            <div class="p-3 sm:p-4">
                                <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Wireless Noise Cancelling
                                    Headphones</h3>
                                <p class="text-lg font-bold text-blue-700 mt-1">$129.99</p>
                                <div class="flex items-center text-yellow-500 text-xs mt-1">
                                    <svg class="w-4 h-4 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                        <path
                                            d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                                    </svg>
                                    <span class="text-gray-500 ml-1">(128)</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-lg transition-shadow overflow-hidden group">
                        <div>
                            <img src="https://images.unsplash.com/photo-1551816230-ef5deaed4a26?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8c21hcnQlMjB3YXRjaHxlbnwwfHwwfHx8MA%3D%3D" alt="Product"
                                class="w-full h-40 sm:h-48 object-cover group-hover:scale-105 transition-transform duration-300" />
                            <div class="p-3 sm:p-4">
                                <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Smart Watch Series 7 - 44mm
                                </h3>
                                <p class="text-lg font-bold text-blue-700 mt-1">$199.00</p>
                                <div class="flex items-center text-yellow-500 text-xs mt-1">
                                    <svg class="w-4 h-4 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                        <path
                                            d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                                    </svg>
                                    <span class="text-gray-500 ml-1">(96)</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-lg transition-shadow overflow-hidden group">
                        <div>
                            <img src="https://images.unsplash.com/photo-1716951848908-8907bb6c655b?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NDN8fHQtc2hpcnR8ZW58MHx8MHx8fDA%3D" alt="Product"
                                class="w-full h-40 sm:h-48 object-cover group-hover:scale-105 transition-transform duration-300" />
                            <div class="p-3 sm:p-4">
                                <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Men's Casual Cotton Shirt
                                </h3>
                                <p class="text-lg font-bold text-blue-700 mt-1">$29.99</p>
                                <div class="flex items-center text-yellow-500 text-xs mt-1">
                                    <svg class="w-4 h-4 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                        <path
                                            d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                                    </svg>
                                    <span class="text-gray-500 ml-1">(245)</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-lg transition-shadow overflow-hidden group">
                        <div>
                            <img src="https://plus.unsplash.com/premium_photo-1706800283323-e9f633ccad85?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDZ8fHxlbnwwfHx8fHw%3D" alt="Product"
                                class="w-full h-40 sm:h-48 object-cover group-hover:scale-105 transition-transform duration-300" />
                            <div class="p-3 sm:p-4">
                                <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Modern Ceramic Vase Set</h3>
                                <p class="text-lg font-bold text-blue-700 mt-1">$45.50</p>
                                <div class="flex items-center text-yellow-500 text-xs mt-1">
                                    <svg class="w-4 h-4 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                        <path
                                            d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                                    </svg>
                                    <span class="text-gray-500 ml-1">(78)</span>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-lg transition-shadow overflow-hidden group">
                        <div>
                            <img src="https://images.unsplash.com/photo-1521499892833-773a6c6fd0b8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MjB8fHZpbnRhZ2UlMjBhbmFsb2clMjBjYW1lcmF8ZW58MHx8MHx8fDA%3D" alt="Product"
                                class="w-full h-40 sm:h-48 object-cover group-hover:scale-105 transition-transform duration-300" />
                            <div class="p-3 sm:p-4">
                                <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Vintage Analog Camera</h3>
                                <p class="text-lg font-bold text-blue-700 mt-1">$249.99</p>
                                <div class="flex items-center text-yellow-500 text-xs mt-1">
                                    <svg class="w-4 h-4 " aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                                        width="24" height="24" fill="currentColor" viewBox="0 0 24 24">
                                        <path
                                            d="M13.849 4.22c-.684-1.626-3.014-1.626-3.698 0L8.397 8.387l-4.552.361c-1.775.14-2.495 2.331-1.142 3.477l3.468 2.937-1.06 4.392c-.413 1.713 1.472 3.067 2.992 2.149L12 19.35l3.897 2.354c1.52.918 3.405-.436 2.992-2.15l-1.06-4.39 3.468-2.938c1.353-1.146.633-3.336-1.142-3.477l-4.552-.36-1.754-4.17Z" />
                                    </svg>
                                    <span class="text-gray-500 ml-1">(42)</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- Daily Deals Section -->
            <section class="max-w-7xl mx-auto px-3 sm:px-4 lg:px-6 py-6 sm:py-8">
                <h2 class="text-xl sm:text-2xl font-bold mb-4 sm:mb-6">Daily Deals</h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 sm:p-5 flex gap-4">
                        <img src="https://images.unsplash.com/photo-1606741965326-cb990ae01bb2?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8d2lyZWxlc3MlMjBibHVldG9vdGglMjBlYXJwdWRzfGVufDB8fDB8fHww" alt="Deal"
                            class="w-30 h-30 sm:w-34 sm:h-34 object-cover rounded" />
                        <div class="flex-1">
                            <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Wireless Bluetooth Earbuds -
                                White</h3>
                            <div class="mt-1">
                                <span class="text-lg font-bold text-blue-700">$49.99</span>
                                <span class="text-sm text-gray-500 line-through ml-2">$79.99</span>
                            </div>
                            <span
                                class="inline-block mt-2 text-xs font-semibold text-red-600 bg-red-50 px-2 py-0.5 rounded">37%
                                OFF</span>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 sm:p-5 flex gap-4">
                        <img src="https://images.unsplash.com/photo-1625708458528-802ec79b1ed8?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8c3RhaW5sZXNzJTIwc3RlZWwlMjB3YXRlciUyMGJvdHRsZXxlbnwwfHwwfHx8MA%3D%3D" alt="Deal"
                            class="w-30 h-30 sm:w-34 sm:h-34 object-cover rounded" />
                        <div class="flex-1">
                            <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Stainless Steel Water Bottle 1L
                            </h3>
                            <div class="mt-1">
                                <span class="text-lg font-bold text-blue-700">$18.50</span>
                                <span class="text-sm text-gray-500 line-through ml-2">$29.99</span>
                            </div>
                            <span
                                class="inline-block mt-2 text-xs font-semibold text-red-600 bg-red-50 px-2 py-0.5 rounded">38%
                                OFF</span>
                        </div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm hover:shadow-md transition-shadow p-4 sm:p-5 flex gap-4">
                        <img src="https://images.unsplash.com/photo-1655360832196-d8f132381e91?w=600&auto=format&fit=crop&q=60&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTMyfHxwb3J0YWJsZSUyMHBvd2VyJTIwYmFua3xlbnwwfHwwfHx8MA%3D%3D" alt="Deal"
                            class="w-30 h-30 sm:w-34 sm:h-34 o rounded" />
                        <div class="flex-1">
                            <h3 class="text-sm font-medium text-gray-800 line-clamp-2">Portable Power Bank 20000mAh</h3>
                            <div class="mt-1">
                                <span class="text-lg font-bold text-blue-700">$32.99</span>
                                <span class="text-sm text-gray-500 line-through ml-2">$49.99</span>
                            </div>
                            <span
                                class="inline-block mt-2 text-xs font-semibold text-red-600 bg-red-50 px-2 py-0.5 rounded">34%
                                OFF</span>
                        </div>
                    </div>
                </div>
            </section>
        </main>

        <!-- <footer class="bg-gray-100 border-t border-gray-200 mt-8 py-8 sm:py-10">
                <div class="max-w-7xl mx-auto px-3 sm:px-4 lg:px-6">
                    <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6 sm:gap-8">
                        <div>
                            <h4 class="text-lg font-bold text-gray-800 mb-3">About Lumina</h4>
                            <ul class="space-y-2 text-sm text-gray-600">
                                <li><a href="#" class="hover:text-blue-600">About Us</a></li>
                                <li><a href="#" class="hover:text-blue-600">Careers</a></li>
                                <li><a href="#" class="hover:text-blue-600">Company Info</a></li>
                                <li><a href="#" class="hover:text-blue-600">Investor Relations</a></li>
                            </ul>
                        </div>
                        <div>
                            <h4 class="text-lg font-bold text-gray-800 mb-3">Buying</h4>
                            <ul class="space-y-2 text-sm text-gray-600">
                                <li><a href="#" class="hover:text-blue-600">Registration</a></li>
                                <li><a href="#" class="hover:text-blue-600">Bidding & Buying Help</a></li>
                                <li><a href="#" class="hover:text-blue-600">Shipping</a></li>
                                <li><a href="#" class="hover:text-blue-600">Returns</a></li>
                            </ul>
                        </div>
                        <div>
                            <h4 class="text-lg font-bold text-gray-800 mb-3">Selling</h4>
                            <ul class="space-y-2 text-sm text-gray-600">
                                <li><a href="#" class="hover:text-blue-600">Start Selling</a></li>
                                <li><a href="#" class="hover:text-blue-600">Selling Policies</a></li>
                                <li><a href="#" class="hover:text-blue-600">Business Tools</a></li>


                        </div>
                    </div>
                </div> -->
    </div>


</template>
