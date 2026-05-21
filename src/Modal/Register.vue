<script>
export default {
    data() {
        return {

        }
    },
    methods: {
        closeRegister() {
            this.$emit('close')
        }


    }
}

</script>

<template>
    <div @click="closeRegister" class="bg-white fixed top-0 w-screen h-screen z-1030">

    </div>
    <div class="">
        <a href="/" class="flex-shrink-0 fixed z-1033"
            style="top: clamp(1rem, 3vw, 2rem); left: clamp(1rem, 3vw, 2rem);">
            <span
                class="text-[clamp(1.6rem,3vw,2rem)] font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent hover:from-indigo-700 hover:to-blue-600 transition-all duration-300">
                K R Y S
            </span>
        </a>
    </div>
    <div className="h-screen relative bg-gray-100 flex items-center justify-center p-4">
        <div
            className="w-full b-10 fixed z-1035 top-20 max-w-5xl bg-white rounded-3xl shadow-2xl overflow-hidden grid grid-cols-1 lg:grid-cols-2">
            <div
                className="hidden lg:flex flex-col justify-center bg-gradient-to-br from-indigo-400 via-indigo-300 to-blue-500 p-12 text-white relative overflow-hidden">
                <div className="absolute top-0 left-0 w-72 h-72 bg-white/10 rounded-full blur-3xl"></div>
                <div className="absolute bottom-0 right-0 w-72 h-72 bg-black/10 rounded-full blur-3xl"></div>

                <div className="relative z-10">
                    <h1 className="text-5xl font-extrabold mb-6 leading-tight">
                        Join the Marketplace
                    </h1>
                    <p className="text-lg text-white/90 leading-relaxed max-w-md">
                        Create your account and discover millions of products, deals,
                        and exclusive offers inspired by the modern KRYS shopping
                        experience.
                    </p>

                    <div className="mt-10 space-y-4">
                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                <svg class="" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24"
                                    height="24" fill="none" viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                                        stroke-width="2" d="M5 11.917 9.724 16.5 19 7.5" />
                                </svg>

                            </div>
                            <span className="text-white/90">Fast & secure signup</span>
                        </div>

                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                <svg class="" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24"
                                    height="24" fill="none" viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-width="2"
                                        d="M11.083 5.104c.35-.8 1.485-.8 1.834 0l1.752 4.022a1 1 0 0 0 .84.597l4.463.342c.9.069 1.255 1.2.556 1.771l-3.33 2.723a1 1 0 0 0-.337 1.016l1.03 4.119c.214.858-.71 1.552-1.474 1.106l-3.913-2.281a1 1 0 0 0-1.008 0L7.583 20.8c-.764.446-1.688-.248-1.474-1.106l1.03-4.119A1 1 0 0 0 6.8 14.56l-3.33-2.723c-.698-.571-.342-1.702.557-1.771l4.462-.342a1 1 0 0 0 .84-.597l1.753-4.022Z" />
                                </svg>

                            </div>
                            <span className="text-white/90">Exclusive member offers</span>
                        </div>

                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                <svg class="" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="24"
                                    height="24" fill="none" viewBox="0 0 24 24">
                                    <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"
                                        stroke-width="2"
                                        d="M4 4.5V19a1 1 0 0 0 1 1h15M7 14l4-4 4 4 5-5m0 0h-3.207M20 9v3.207" />
                                </svg>



                            </div>
                            <span className="text-white/90">Quick access to trending items</span>
                        </div>
                    </div>
                </div>
            </div>


            <div className="p-8 sm:p-10 lg:p-14 flex flex-col justify-center">
                <div className="mb-8 text-center lg:text-left">
                    <h2 className="text-4xl font-bold text-gray-900">
                        Create Account
                    </h2>
                    <p className="text-gray-500 mt-2">
                        Start your shopping journey today.
                    </p>
                </div>

                <form className="space-y-5">
                    <div className="grid grid-cols-1 sm:grid-cols-2 gap-5">
                        <div>
                            <label className="block text-sm font-medium text-gray-700 mb-2">
                                First Name
                            </label>
                            <input type="text" placeholder="Zy"
                                className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                        </div>

                        <div>
                            <label className="block text-sm font-medium text-gray-700 mb-2">
                                Last Name
                            </label>
                            <input type="text" placeholder="Ron"
                                className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                        </div>
                    </div>

                    <div>
                        <label className="block text-sm font-medium text-gray-700 mb-2">
                            Email Address
                        </label>
                        <input type="email" placeholder="you@example.com"
                            className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                    </div>

                    <div>
                        <label className="block text-sm font-medium text-gray-700 mb-2">
                            Password
                        </label>
                        <input type="password" placeholder="......"
                            className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                    </div>

                    <div>
                        <label className="block text-sm font-medium text-gray-700 mb-2">
                            Confirm Password
                        </label>
                        <input type="password" placeholder="......"
                            className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                    </div>

                    <div className="flex items-start gap-3">
                        <input type="checkbox"
                            className="mt-1 w-4 h-4 rounded border-gray-300 text-blue-600 focus:ring-blue-500" />
                        <p className="text-sm text-gray-600 leading-relaxed">
                            I agree to the Terms & Conditions and Privacy Policy.
                        </p>
                    </div>

                    <button type="submit"
                        className="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 rounded-2xl transition duration-300 shadow-lg hover:shadow-xl">
                        Create Account
                    </button>
                </form>

                <div className="relative my-8">
                    <div className="absolute inset-0 flex items-center">
                        <div className="w-full border-t border-gray-300"></div>
                    </div>
                    <div className="relative flex justify-center text-sm">
                        <span className="bg-white px-4 text-gray-500">or continue with</span>
                    </div>
                </div>

                <div className="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <button
                        className="items-center justify-center flex space-x-2 text-center border border-gray-300 rounded-2xl py-3 font-medium hover:bg-gray-50 transition">
                        <svg class="w-4 h-4 sm:w-5 sm:h-5 flex-shrink-0" viewBox="0 0 24 24" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
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
                        <span>Google</span>
                    </button>

                    <button
                        className="items-center justify-center flex space-x-2 text-center border border-gray-300 rounded-2xl py-3 font-medium hover:bg-gray-50 transition">
                        <svg class="w-5 h-5 sm:w-6 sm:h-6 text-gray-800 flex-shrink-0" aria-hidden="true"
                            xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor"
                            viewBox="0 0 24 24">
                            <path
                                d="M17.537 12.625a4.421 4.421 0 0 0 2.684 4.047 10.96 10.96 0 0 1-1.384 2.845c-.834 1.218-1.7 2.432-3.062 2.457-1.34.025-1.77-.794-3.3-.794-1.531 0-2.01.769-3.275.82-1.316.049-2.317-1.318-3.158-2.532-1.72-2.484-3.032-7.017-1.27-10.077A4.9 4.9 0 0 1 8.91 6.884c1.292-.025 2.51.869 3.3.869.789 0 2.27-1.075 3.828-.917a4.67 4.67 0 0 1 3.66 1.984 4.524 4.524 0 0 0-2.16 3.805m-2.52-7.432A4.4 4.4 0 0 0 16.06 2a4.482 4.482 0 0 0-2.945 1.516 4.185 4.185 0 0 0-1.061 3.093 3.708 3.708 0 0 0 2.967-1.416Z" />
                        </svg>
                        <span>Apple</span>
                    </button>
                </div>

                <p className="text-center text-sm text-gray-500 mt-8">
                    Already have an account?
                    <span className="text-blue-600 font-semibold cursor-pointer hover:underline">
                        Sign in
                    </span>
                </p>
            </div>
        </div>
    </div>

</template>