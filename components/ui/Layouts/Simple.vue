<template>
    <view-component
        :name="name"
        :code="code"
        :playUrl="'https://play.tailwindcss.com/VtEJtnAu0N'"
    >
        <div class="px-3 py-6" slot="component">
            <div class="flex items-center justify-center max-w-9xl">
                <div class="min-w-full min-h-full">
                    <nav
                        class="bg-white border-4 border-gray-400 border-dashed rounded-lg "
                    >
                        <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
                            <div
                                class="flex items-center justify-between w-full h-16 "
                            >
                                Navbar
                            </div>
                        </div>
                    </nav>

                    <main class="min-w-full min-h-full">
                        <div
                            class="h-screen py-6 mt-6 bg-white border-4 border-gray-400 border-dashed rounded-lg max-w-9xl sm:px-6 lg:px-8"
                        >
                            Content
                        </div>
                    </main>
                    <footer
                        class="mt-6 bg-white border-4 border-gray-400 border-dashed rounded-lg "
                    >
                        <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
                            <div
                                class="flex items-center justify-between w-full h-16 "
                            >
                                Footer
                            </div>
                        </div>
                    </footer>
                </div>
            </div>
        </div>
    </view-component>
</template>

<script>
export default {
    data() {
        return {
            name: "Simple",
            code: `
            <div class="flex items-center justify-center max-w-9xl">
                <div class="min-w-full min-h-full">
                    <nav
                        class="bg-white border-4 border-gray-400 border-dashed rounded-lg "
                    >
                        <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
                            <div
                                class="flex items-center justify-between w-full h-16 "
                            >
                                Navbar
                            </div>
                        </div>
                    </nav>

                    <main class="min-w-full min-h-full">
                        <div
                            class="h-screen py-6 mt-6 bg-white border-4 border-gray-400 border-dashed rounded-lg max-w-9xl sm:px-6 lg:px-8"
                        >
                            Content
                        </div>
                    </main>
                    <footer
                        class="mt-6 bg-white border-4 border-gray-400 border-dashed rounded-lg "
                    >
                        <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
                            <div
                                class="flex items-center justify-between w-full h-16 "
                            >
                                Footer
                            </div>
                        </div>
                    </footer>
                </div>
            </div>
`,
        };
    },
};
</script>
