<script>
export default {
    data() {
        return {}
    },
    methods: {
        closeRegister() {
            this.$emit('close')
        }
    }
}
</script>

<template>
    <div @click="closeRegister" class="bg-white fixed top-0 w-screen h-screen z-1030"></div>

    <a href="/" class="flex-shrink-0 fixed z-1036" style="top: clamp(1rem, 3vw, 2rem); left: clamp(1rem, 3vw, 2rem);">
        <span
            class="text-[clamp(1.4rem,2.5vw,1.8rem)] font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent hover:from-indigo-700 hover:to-blue-600 transition-all duration-300">
            K R Y S
        </span>
    </a>

    <div class="min-h-screen pt-16 pb-4 bg-gray-100 flex items-center justify-center p-4">
        <div class="w-full max-w-4xl bg-white rounded-2xl shadow-xl overflow-hidden grid grid-cols-1 lg:grid-cols-2">

            <!-- Left Side -->
            <div
                class="hidden lg:flex flex-col justify-center bg-gradient-to-br from-indigo-400 via-indigo-300 to-blue-500 p-8 text-white relative">
                <div class="absolute top-0 left-0 w-60 h-60 bg-white/10 rounded-full blur-3xl"></div>
                <div class="absolute bottom-0 right-0 w-60 h-60 bg-black/10 rounded-full blur-3xl"></div>

                <div class="relative z-10">
                    <h1 class="text-2xl font-bold mb-2">Join Marketplace</h1>
                    <p class="text-sm text-white/90 mb-5">Create your account and discover millions of products &
                        exclusive offers.</p>

                    <div class="space-y-2">
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 rounded-full bg-white/20 flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="none"
                                    viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                                        stroke-width="2" d="M5 11.917 9.724 16.5 19 7.5" />
                                </svg>
                            </div>
                            <span class="text-sm text-white/90">Fast & secure signup</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 rounded-full bg-white/20 flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="none"
                                    viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-width="2"
                                        d="M11.083 5.104c.35-.8 1.485-.8 1.834 0l1.752 4.022a1 1 0 0 0 .84.597l4.463.342c.9.069 1.255 1.2.556 1.771l-3.33 2.723a1 1 0 0 0-.337 1.016l1.03 4.119c.214.858-.71 1.552-1.474 1.106l-3.913-2.281a1 1 0 0 0-1.008 0L7.583 20.8c-.764.446-1.688-.248-1.474-1.106l1.03-4.119A1 1 0 0 0 6.8 14.56l-3.33-2.723c-.698-.571-.342-1.702.557-1.771l4.462-.342a1 1 0 0 0 .84-.597l1.753-4.022Z" />
                                </svg>
                            </div>
                            <span class="text-sm text-white/90">Exclusive offers</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <div class="w-8 h-8 rounded-full bg-white/20 flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" fill="none"
                                    viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M4 4.5V19a1 1 0 0 0 1 1h15M7 14l4-4 4 4 5-5m0 0h-3.207M20 9v3.207" />
                                </svg>
                            </div>
                            <span class="text-sm text-white/90">Trending items</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Right Side Form -->
            <div class="p-6 sm:p-8 flex flex-col justify-center">
                <div class="mb-4 text-center lg:text-left">
                    <h2 class="text-xl font-bold text-gray-900">Create Account</h2>
                    <p class="text-xs text-gray-500 mt-1">Start your shopping journey today.</p>
                </div>

                <form class="space-y-3">
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                        <div>
                            <label class="block text-xs font-medium text-gray-700 mb-1">First Name</label>
                            <input type="text" placeholder="Zy"
                                class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-gray-700 mb-1">Last Name</label>
                            <input type="text" placeholder="Ron"
                                class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-medium text-gray-700 mb-1">Email Address</label>
                        <input type="email" placeholder="you@example.com"
                            class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
                    </div>

                    <div>
                        <label class="block text-xs font-medium text-gray-700 mb-1">Password</label>
                        <input type="password" placeholder="......"
                            class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
                    </div>

                    <div>
                        <label class="block text-xs font-medium text-gray-700 mb-1">Confirm Password</label>
                        <input type="password" placeholder="......"
                            class="w-full rounded-lg border border-gray-300 px-3 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-blue-500" />
                    </div>

                    <div class="flex items-start gap-2">
                        <input type="checkbox" class="mt-1 w-3 h-3" />
                        <p class="text-xs text-gray-600">I agree to Terms & Privacy Policy.</p>
                    </div>

                    <button type="submit"
                        class="w-full bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 rounded-lg text-sm transition">
                        Create Account
                    </button>
                </form>

                <div class="relative my-4">
                    <div class="absolute inset-0 flex items-center">
                        <div class="w-full border-t border-gray-300"></div>
                    </div>
                    <div class="relative flex justify-center text-xs"><span class="bg-white px-3 text-gray-500">or
                            continue with</span></div>
                </div>

                <div class="grid grid-cols-2 gap-3">
                    <button
                        class="flex items-center justify-center gap-1.5 border border-gray-300 rounded-lg py-2 text-xs hover:bg-gray-50">
                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M22.56 12.25c0-.78-.07-1.53-.2-2.25H12v4.26h5.92c-.26 1.37-1.04 2.53-2.21 3.31v2.77h3.57c2.08-1.92 3.28-4.74 3.28-8.09z"
                                fill="#4285F4" />
                            <path
                                d="M12 23c2.97 0 5.46-.98 7.28-2.66l-3.57-2.77c-.98.66-2.23 1.06-3.71 1.06-2.86 0-5.29-1.92-6.16-4.53H2.18v2.84C3.99 20.53 7.7 23 12 23z"
                                fill="#34A853" />
                            <path
                                d="M5.84 14.09c-.22-.66-.35-1.36-.35-2.09s.13-1.43.35-2.09V7.07H2.18C1.43 8.55 1 10.22 1 12s.43 3.45 1.18 4.93l2.85-2.22.81-.62z"
                                fill="#FBBC05" />
                            <path
                                d="M12 5.38c1.57 0 2.98.54 4.09 1.6l3.09-3.09C17.46 2.14 14.97 1 12 1 7.7 1 3.99 2.47 2.18 5.38l3.66 2.84C6.72 5.92 9.13 5.38 12 5.38z"
                                fill="#EA4335" />
                        </svg>
                        Google
                    </button>
                    <button
                        class="flex items-center justify-center gap-1.5 border border-gray-300 rounded-lg py-2 text-xs hover:bg-gray-50">
                        <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 24 24">
                            <path
                                d="M17.537 12.625a4.421 4.421 0 0 0 2.684 4.047 10.96 10.96 0 0 1-1.384 2.845c-.834 1.218-1.7 2.432-3.062 2.457-1.34.025-1.77-.794-3.3-.794-1.531 0-2.01.769-3.275.82-1.316.049-2.317-1.318-3.158-2.532-1.72-2.484-3.032-7.017-1.27-10.077A4.9 4.9 0 0 1 8.91 6.884c1.292-.025 2.51.869 3.3.869.789 0 2.27-1.075 3.828-.917a4.67 4.67 0 0 1 3.66 1.984 4.524 4.524 0 0 0-2.16 3.805m-2.52-7.432A4.4 4.4 0 0 0 16.06 2a4.482 4.482 0 0 0-2.945 1.516 4.185 4.185 0 0 0-1.061 3.093 3.708 3.708 0 0 0 2.967-1.416Z" />
                        </svg>
                        Apple
                    </button>
                </div>

                <p class="text-center text-xs text-gray-500 mt-4">
                    Already have an account? <span class="text-blue-600 font-medium cursor-pointer hover:underline">Sign
                        in</span>
                </p>
            </div>

        </div>
    </div>
</template>