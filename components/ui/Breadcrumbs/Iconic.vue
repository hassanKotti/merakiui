<template>
    <view-component
        :name="name"
        :code="code"
        :playUrl="'https://play.tailwindcss.com/OskEgRTxJi'"
    >
        <div class="px-3 py-6 bg-gray-100 dark:bg-gray-900" slot="component">
            <div class="flex items-center justify-center">
                <nav
                    aria-label="Breadcrumb"
                    class="flex items-center w-full px-4 py-4 space-x-2 text-sm font-medium text-gray-700 bg-white border-t border-b border-gray-300 dark:border-gray-500 dark:bg-gray-900 dark:text-gray-400 whitespace-nowrap"
                >
                    <a href="/home" class="hover:text-gray-900">
                        <div class="flex items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                                />
                            </svg>
                            <span class="mx-1"> Home</span>
                        </div>
                    </a>
                    <svg
                        aria-hidden="true"
                        width="24"
                        height="24"
                        fill="none"
                        class="flex-none text-gray-300"
                    >
                        <path
                            d="M10.75 8.75l3.5 3.25-3.5 3.25"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        ></path>
                    </svg>
                    <a href="/settings" class="hover:text-gray-900">
                        <div class="flex items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                                />
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                                />
                            </svg>
                            <span class="mx-1"> Settings</span>
                        </div>
                    </a>
                    <svg
                        aria-hidden="true"
                        width="24"
                        height="24"
                        fill="none"
                        class="flex-none text-gray-300"
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
                        href="/home/settings/user"
                        aria-current="page"
                        class="truncate hover:text-gray-900"
                    >
                        <div class="flex items-center text-indigo-500">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                                />
                            </svg>
                            <span class="mx-1">User</span>
                        </div>
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
            name: "Iconic",
            code: `                <nav
                    aria-label="Breadcrumb"
                    class="flex items-center w-full px-4 py-4 space-x-2 text-sm font-medium text-gray-700 border-t border-b border-gray-300 dark:border-gray-500 dark:text-gray-400 whitespace-nowrap"
                >
                    <a href="/home" class="hover:text-gray-900">
                        <div class="flex items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
                                />
                            </svg>
                            <span class="mx-1"> Home</span>
                        </div>
                    </a>
                    <svg
                        aria-hidden="true"
                        width="24"
                        height="24"
                        fill="none"
                        class="flex-none text-gray-300"
                    >
                        <path
                            d="M10.75 8.75l3.5 3.25-3.5 3.25"
                            stroke="currentColor"
                            stroke-width="1.5"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                        ></path>
                    </svg>
                    <a href="/settings" class="hover:text-gray-900">
                        <div class="flex items-center">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
                                />
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
                                />
                            </svg>
                            <span class="mx-1"> Settings</span>
                        </div>
                    </a>
                    <svg
                        aria-hidden="true"
                        width="24"
                        height="24"
                        fill="none"
                        class="flex-none text-gray-300"
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
                        href="/home/settings/user"
                        aria-current="page"
                        class="truncate hover:text-gray-900"
                    >
                        <div class="flex items-center text-indigo-500">
                            <svg
                                xmlns="http://www.w3.org/2000/svg"
                                class="w-4 h-4"
                                fill="none"
                                viewBox="0 0 24 24"
                                stroke="currentColor"
                            >
                                <path
                                    stroke-linecap="round"
                                    stroke-linejoin="round"
                                    stroke-width="2"
                                    d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
                                />
                            </svg>
                            <span class="mx-1">User</span>
                        </div>
                    </a>
                </nav>`,
        };
    },
};
</script>
