<template>
    <div class="max-w-7xl mx-auto grid grid-cols-2 gap-4">
        <div class="main-left">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <h1 class="mb-6 text-2xl">Log in</h1>
                <p class="font-bold">
                    Don't have an account? <RouterLink to="/signup" class="underline">Click here</RouterLink> to sign up!
                </p>
            </div>
        </div>

        <div class="main-right">
            <div class="p-12 bg-white border border-gray-200 rounded-lg">
                <form action="" class="space-y-6">
                    <div>
                        <label for="email">E-mail</label><br>
                        <input type="email" name="email" id="email" placeholder="Enter your e-mail here"
                            class="w-full mt-2 py-4 px-6 border border-gray-200 rounded-lg">
                    </div>
                    <div>
                        <label for="">Password</label><br>
                        <input type="password" name="password" id="password" placeholder="Enter your password here"
                            class="w-full mt-2 py-4  px-6 border border-gray-200 rounded-lg">
                    </div>

                    <div>
                        <button class="py-4 px-6 bg-purple-600 text-white rounded-lg">Log in</button>
                    </div>
                </form>
            </div>
        </div>

    </div>
</template>