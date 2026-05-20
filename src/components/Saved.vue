<script>

</script>

<template>

    <div class="bg-gray-50 w-full">
    

        <!-- Main Content -->
        <main class="container mx-auto px-4 py-8">
            <!-- Page Title -->
            <div class="mb-8">
                <h1 class="text-[clamp(1.8rem,3vw,2.5rem)] font-bold text-dark">Saved Items</h1>
                <p class="text-gray-600 mt-2">All your favorite items in one place — updated whenever you save or
                    remove.</p>
            </div>

            <!-- Filters & Sort -->
            <div class="flex flex-col sm:flex-row gap-4 mb-8 justify-between items-start sm:items-center">
                <div class="flex gap-2">
                    <button class="btn-primary">All Items (12)</button>
                    <button class="btn-outline">On Sale (4)</button>
                </div>
                <select
                    class="border border-gray-300 rounded-lg px-3 py-2 bg-white focus:outline-none focus:ring-1 focus:ring-primary">
                    <option>Sort: Recently Saved</option>
                    <option>Price: Low to High</option>
                    <option>Price: High to Low</option>
                    <option>Popularity</option>
                </select>
            </div>

            <!-- Items Grid -->
            <div id="savedItemsGrid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Items will be injected here via JS -->
            </div>
        </main>

    </div>


</template>