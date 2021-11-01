<template>
    <view-component
        :name="name"
        :code="code"
        :playUrl="'https://play.tailwindcss.com/g8bf9OZfoQ'"
    >
        <div class="px-3 py-6 bg-white dark:bg-gray-900" slot="component">
            <div class="flex items-center justify-center">
                <nav
                    aria-label="Breadcrumb"
                    class="flex space-x-2 font-medium text-gray-500 txt-sm items-cente r whitespace-nowrap"
                >
                    <a href="/home" class="hover:text-gray-900 dark:text-gray-300"> Home </a>
                    <svg
                        aria-hidden="true"
                        width="24"
                        height="24"
                        fill="none"
                        class="flex-none text-gray-300 dark:text-gray-300"
                    >
                        <path
                            d="M10.75 8.75l3.5 3.25-3.5 3.25"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        ></path>
                    </svg>
                    <a
                        href="/home/settings"
                        aria-current="page"
                        class="truncate hover:text-gray-900 dark:text-gray-300 "
                    >
                        Settings
                    </a>
                </nav>
            </div>
        </div>
    </view-component>
</template>

<script>
export default {
    data() {
        return {
            name: "Simple",
            code: `<nav aria-label="Breadcrumb" class="flex items-center space-x-2 text-sm font-medium text-gray-500 bg-white whitespace-nowrap">
                <a href="/home" class="hover:text-gray-900"> Home </a>
                    <svg aria-hidden="true" width="24" height="24" fill="none" class="flex-none text-gray-300">
                        <path d="M10.75 8.75l3.5 3.25-3.5 3.25" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"></path>
                    </svg>
                <a href="/home/settings" aria-current="page" class="truncate hover:text-gray-900"> Settings </a>
            </nav>`,
        };
    },
};
</script>
