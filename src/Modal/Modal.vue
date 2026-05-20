<script>
export default {
    data() {
        return {

        }
    },
    methods: {
        close() {
            this.$emit('closeModal')
        }


    }
}
</script>


<template>

    <div @click="close" class="bg-white fixed top-0 w-screen h-screen z-1024">

    </div>
    <div class="">
        <a href="/" class="flex-shrink-0 fixed z-1030"
            style="top: clamp(1rem, 3vw, 2rem); left: clamp(1rem, 3vw, 2rem);">
            <span
                class="text-[clamp(1.6rem,3vw,2rem)] font-bold bg-gradient-to-r from-blue-600 to-indigo-700 bg-clip-text text-transparent hover:from-indigo-700 hover:to-blue-600 transition-all duration-300">
                K R Y S
            </span>
        </a>

        <div
            class="relative min-h-screen w-full flex justify-center items-center px-4 py-6 sm:px-6 sm:py-8 md:px-8 md:py-10">
            <div class="flex justify-center w-full top-35 fixed z-1024 px-4">
                <div class="bg-white w-full max-w-md rounded-lg shadow-md px-4 py-5 sm:px-6 sm:py-6">
                    <h2 class="text-xl sm:text-2xl font-bold text-center text-gray-800 mb-4 sm:mb-6">Sign in to your
                        account
                    </h2>

                    <div
                        class="bg-slate-100 rounded-xl py-2 px-3 sm:px-4 flex justify-between items-center mb-4 sm:mb-5">
                        <p class="font-semibold text-sm sm:text-base">new to KRYS?</p>
                        <button
                            class="border rounded-full py-1 px-2 sm:py-1.5 sm:px-3 font-semibold text-sm sm:text-base whitespace-nowrap">create
                            account</button>
                    </div>

                    <form>
                        <div class="mb-3 sm:mb-4 mt-3 sm:mt-4">
                            <input type="email" id="email"
                                class="w-full px-3 sm:px-4 py-2 sm:py-2.5 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent outline-none transition text-sm sm:text-base"
                                placeholder="Email or username">
                        </div>

                        <button type="submit"
                            class="w-full bg-blue-600 hover:bg-blue-700 text-white font-medium py-2 sm:py-2.5 rounded-full transition text-sm sm:text-base">
                            Continue
                        </button>

                        <div class="relative my-4 sm:my-6">
                            <div class="absolute inset-0 flex items-center">
                                <div class="w-full border-t border-gray-300"></div>
                            </div>
                            <div class="relative flex justify-center text-sm">
                                <span class="bg-white px-2 font-semibold">Or</span>
                            </div>
                        </div>

                        <div class="space-y-3 sm:space-y-4">
                            <button type="button"
                                class="w-full flex items-center justify-center px-3 sm:px-5 gap-2 sm:gap-3 border border-gray-300 rounded-full py-2 sm:py-2.5 hover:bg-gray-50 transition text-sm sm:text-base">
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
                                <span class="font-semibold text-center">Continue with Google</span>
                            </button>

                            <button type="button"
                                class="w-full flex items-center justify-center px-3 sm:px-5 gap-2 sm:gap-3 border border-gray-300 rounded-full py-2 sm:py-2.5 hover:bg-gray-50 transition text-sm sm:text-base">
                                <svg class="w-5 h-5 sm:w-6 sm:h-6 text-gray-800 flex-shrink-0" aria-hidden="true"
                                    xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor"
                                    viewBox="0 0 24 24">
                                    <path
                                        d="M17.537 12.625a4.421 4.421 0 0 0 2.684 4.047 10.96 10.96 0 0 1-1.384 2.845c-.834 1.218-1.7 2.432-3.062 2.457-1.34.025-1.77-.794-3.3-.794-1.531 0-2.01.769-3.275.82-1.316.049-2.317-1.318-3.158-2.532-1.72-2.484-3.032-7.017-1.27-10.077A4.9 4.9 0 0 1 8.91 6.884c1.292-.025 2.51.869 3.3.869.789 0 2.27-1.075 3.828-.917a4.67 4.67 0 0 1 3.66 1.984 4.524 4.524 0 0 0-2.16 3.805m-2.52-7.432A4.4 4.4 0 0 0 16.06 2a4.482 4.482 0 0 0-2.945 1.516 4.185 4.185 0 0 0-1.061 3.093 3.708 3.708 0 0 0 2.967-1.416Z" />
                                </svg>
                                <span class="font-semibold text-center">Continue with Apple</span>
                            </button>

                            <button type="button"
                                class="w-full flex items-center justify-center px-3 sm:px-5 gap-2 sm:gap-3 border border-gray-300 rounded-full py-2 sm:py-2.5 hover:bg-gray-50 transition text-sm sm:text-base">
                                <svg class="h-5 w-5 sm:h-6 sm:w-6 flex-shrink-0" xmlns="http://www.w3.org/2000/svg"
                                    viewBox="0 0 512 512">
                                    <path
                                        d="M480,257.35c0-123.7-100.3-224-224-224S32,133.65,32,257.35c0,111.8,81.9,204.47,189,221.29V322.12H164.11V257.35H221V208c0-56.13,33.45-87.16,84.61-87.16,24.51,0,50.15,4.38,50.15,4.38v55.13H327.5c-27.81,0-36.51,17.26-36.51,35v42h62.12l-9.92,64.77H291V478.66C398.1,461.85,480,369.18,480,257.35Z"
                                        fill="#1877F2" />
                                </svg>
                                <span class="font-semibold text-center">Continue with Facebook</span>
                            </button>

                            <p class="text-center text-xs sm:text-sm text-gray-600 mt-4 sm:mt-6">
                                Don't have an account? <a href="#"
                                    class="text-blue-600 hover:underline font-medium">Sign
                                    up</a>
                            </p>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>