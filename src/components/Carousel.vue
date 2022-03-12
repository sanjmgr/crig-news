<template>
    <div id="default-carousel" data-carousel="slide" class="relative rounded-md bg-gray-500">
        <!-- Carousel wrapper -->
        <div class="relative overflow-hidden rounded-lg">
            <!-- Item 1 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
                <img
                    src="https://cdn.pixabay.com/photo/2022/03/01/20/58/peace-genius-7042013_960_720.jpg"
                    class="absolute top-1/2 left-1/2 block w-full -translate-x-1/2 -translate-y-1/2"
                    alt="..."
                />
            </div>

            <!-- Item 2 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item="">
                <img
                    src="https://cdn.pixabay.com/photo/2022/02/15/00/40/lemonade-7014122_960_720.jpg"
                    class="absolute top-1/2 left-1/2 block w-full -translate-x-1/2 -translate-y-1/2"
                    alt="..."
                />
            </div>

            <!-- Item 3 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item="">
                <img
                    src="https://cdn.pixabay.com/photo/2021/12/22/02/29/motherhood-6886538_960_720.jpg"
                    class="absolute top-1/2 left-1/2 block w-full -translate-x-1/2 -translate-y-1/2"
                    alt="..."
                />
            </div>

            <!-- Item 4 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item="">
                <img
                    src="https://cdn.pixabay.com/photo/2020/03/26/10/58/norway-4970080_960_720.jpg"
                    class="absolute top-1/2 left-1/2 block w-full -translate-x-1/2 -translate-y-1/2"
                    alt="..."
                />
            </div>

            <!-- Item 5 -->
            <div class="hidden duration-700 ease-in-out" data-carousel-item="">
                <img
                    src="https://cdn.pixabay.com/photo/2019/03/18/04/53/bird-4062359_960_720.jpg"
                    class="absolute top-1/2 left-1/2 block w-full -translate-x-1/2 -translate-y-1/2"
                    alt="..."
                />
            </div>
        </div>

        <!-- Slider indicators -->
        <div class="absolute bottom-5 left-1/2 flex -translate-x-1/2 space-x-3">
            <button
                type="button"
                class="h-3 w-3 rounded-full bg-white dark:bg-gray-800"
                aria-current="true"
                aria-label="Slide 1"
                data-carousel-slide-to="0"
            ></button>
            <button
                type="button"
                class="h-3 w-3 rounded-full bg-white/50 hover:bg-white dark:bg-gray-800/50 dark:hover:bg-gray-800"
                aria-current="false"
                aria-label="Slide 2"
                data-carousel-slide-to="1"
            ></button>
            <button
                type="button"
                class="h-3 w-3 rounded-full bg-white/50 hover:bg-white dark:bg-gray-800/50 dark:hover:bg-gray-800"
                aria-current="false"
                aria-label="Slide 3"
                data-carousel-slide-to="2"
            ></button>
            <button
                type="button"
                class="h-3 w-3 rounded-full bg-white/50 hover:bg-white dark:bg-gray-800/50 dark:hover:bg-gray-800"
                aria-current="false"
                aria-label="Slide 4"
                data-carousel-slide-to="3"
            ></button>
            <button
                type="button"
                class="h-3 w-3 rounded-full bg-white/50 hover:bg-white dark:bg-gray-800/50 dark:hover:bg-gray-800"
                aria-current="false"
                aria-label="Slide 5"
                data-carousel-slide-to="4"
            ></button>
        </div>

        <!-- Slider controls -->
        <button
            type="button"
            class="group absolute top-0 left-0 flex h-full cursor-pointer items-center justify-center px-4 focus:outline-none"
            data-carousel-prev
        >
            <span
                class="inline-flex h-8 w-8 items-center justify-center rounded-full bg-white/30 group-hover:bg-white/50 group-focus:outline-none group-focus:ring-4 group-focus:ring-white dark:bg-gray-800/30 dark:group-hover:bg-gray-800/60 dark:group-focus:ring-gray-800/70 sm:h-10 sm:w-10"
            >
                <svg
                    class="h-5 w-5 text-white dark:text-gray-800 sm:h-6 sm:w-6"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 19l-7-7 7-7"
                    ></path>
                </svg>
                <span class="hidden">Previous</span>
            </span>
        </button>
        <button
            type="button"
            class="group absolute top-0 right-0 flex h-full cursor-pointer items-center justify-center px-4 focus:outline-none"
            data-carousel-next
        >
            <span
                class="inline-flex h-8 w-8 items-center justify-center rounded-full bg-white/30 group-hover:bg-white/50 group-focus:outline-none group-focus:ring-4 group-focus:ring-white dark:bg-gray-800/30 dark:group-hover:bg-gray-800/60 dark:group-focus:ring-gray-800/70 sm:h-10 sm:w-10"
            >
                <svg
                    class="h-5 w-5 text-white dark:text-gray-800 sm:h-6 sm:w-6"
                    fill="none"
                    stroke="currentColor"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                >
                    <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M9 5l7 7-7 7"
                    ></path>
                </svg>
                <span class="hidden">Next</span>
            </span>
        </button>
    </div>
</template>
