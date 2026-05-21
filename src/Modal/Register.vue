<script>

</script>

<template>
    <div className="min-h-screen bg-gray-100 flex items-center justify-center p-4">
        <div
            className="w-full max-w-5xl bg-white rounded-3xl shadow-2xl overflow-hidden grid grid-cols-1 lg:grid-cols-2">
            <div
                className="hidden lg:flex flex-col justify-center bg-gradient-to-br from-yellow-400 via-yellow-300 to-blue-500 p-12 text-white relative overflow-hidden">
                <div className="absolute top-0 left-0 w-72 h-72 bg-white/10 rounded-full blur-3xl"></div>
                <div className="absolute bottom-0 right-0 w-72 h-72 bg-black/10 rounded-full blur-3xl"></div>

                <div className="relative z-10">
                    <h1 className="text-5xl font-extrabold mb-6 leading-tight">
                        Join the Marketplace
                    </h1>
                    <p className="text-lg text-white/90 leading-relaxed max-w-md">
                        Create your account and discover millions of products, deals,
                        and exclusive offers inspired by the modern eBay shopping
                        experience.
                    </p>

                    <div className="mt-10 space-y-4">
                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                ✓
                            </div>
                            <span className="text-white/90">Fast & secure signup</span>
                        </div>

                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                ★
                            </div>
                            <span className="text-white/90">Exclusive member offers</span>
                        </div>

                        <div className="flex items-center gap-3">
                            <div
                                className="w-10 h-10 rounded-full bg-white/20 flex items-center justify-center text-xl">
                                ⚡
                            </div>
                            <span className="text-white/90">Quick access to trending items</span>
                        </div>
                    </div>
                </div>
            </div>

            {/* Right Side */}
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
                            <input type="text" placeholder="John"
                                className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                        </div>

                        <div>
                            <label className="block text-sm font-medium text-gray-700 mb-2">
                                Last Name
                            </label>
                            <input type="text" placeholder="Doe"
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
                        <input type="password" placeholder="••••••••"
                            className="w-full rounded-2xl border border-gray-300 px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent transition" />
                    </div>

                    <div>
                        <label className="block text-sm font-medium text-gray-700 mb-2">
                            Confirm Password
                        </label>
                        <input type="password" placeholder="••••••••"
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
                    <button className="border border-gray-300 rounded-2xl py-3 font-medium hover:bg-gray-50 transition">
                        Google
                    </button>

                    <button className="border border-gray-300 rounded-2xl py-3 font-medium hover:bg-gray-50 transition">
                        Apple
                    </button>
                </div>

                <p className="text-center text-sm text-gray-500 mt-8">
                    Already have an account?{' '}
                    <span className="text-blue-600 font-semibold cursor-pointer hover:underline">
                        Sign in
                    </span>
                </p>
            </div>
        </div>
    </div>
    );
    }
</template>