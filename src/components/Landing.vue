<template>
    <div class="bg-gray-50">
        <div class="container mx-auto p-8 py-8 px-8 md:px-14">
            <div class="mt-4 grid grid-flow-col grid-rows-4 gap-4 md:grid-cols-12 lg:grid-rows-5">
                <div
                    class="relative grid rounded-lg bg-white p-4 shadow-md md:col-span-8 md:row-span-4 lg:col-span-6 lg:row-span-5"
                >
                    <Carousel />
                </div>

                <div
                    class="grid rounded-lg bg-white p-2 shadow-md md:col-span-4 md:row-span-2 lg:col-span-3 lg:row-span-3"
                >
                    <img
                        class="h-full w-full rounded-md object-cover"
                        src="https://bilder.bild.de/fotos/lieferprobleme-und-kunden-wut-hier-steckt-bei-samsung-der-wurm-drin-dce0e18ddfb144efba828ae07f4b0442-79273756/Bild/10.bild.jpg"
                        alt=""
                    />
                    <h4 class="title px-2 pt-4 text-justify font-semibold leading-6">
                        Lieferprobleme und Kunden-Wut: Hier steckt bei Samsung der Wurm drin - BILD
                    </h4>
                </div>
                <div
                    class="grid h-48 rounded-lg bg-white p-2 shadow-md md:col-span-4 md:row-span-2 lg:col-span-3 lg:row-span-2"
                >
                    <img
                        class="h-2/3 w-full rounded-md object-cover"
                        src="https://imgix.gizmodo.com.au/content/uploads/sites/2/2022/03/11/dd083809a974ef2366146a3b780a2667-e1646952230362.gif?ar=16%3A9&auto=format&fit=crop&q=65&w=1200"
                        alt=""
                    />
                    <p class="title -mt-14 px-2 text-justify font-semibold leading-4">
                        Here's How Different Gran Turismo 7 Looks on PS4 Versus PS5 - Gizmodo
                        Australia
                    </p>
                </div>

                <div
                    class="grid h-48 rounded-lg bg-white p-2 shadow-md md:col-span-3 md:row-span-2 md:hidden lg:grid"
                >
                    <img
                        class="h-2/3 w-full rounded-md object-cover"
                        src="https://images.hindustantimes.com/tech/img/2022/03/12/1600x900/Untitled_design_(6)_1647061389520_1647061427293.jpg"
                        alt=""
                    />
                    <p class="title -mt-14 px-2 text-justify font-semibold leading-4">
                        iPhone SE 3 vs iPhone SE 2: Know the key differences before buying iPhone SE
                        2022 - HT Tech
                    </p>
                </div>
                <div
                    class="hidden rounded-lg bg-white p-2 shadow-md md:col-span-3 md:row-span-3 lg:grid"
                >
                    <img
                        class="h-full w-full rounded-md object-cover"
                        src="https://mm.netinfo.bg/branding/dbrand.php?p=aDE1UTNyWEtkWWZ3YWRpN09YV25aTld3Zy82RFBhbDhxTE5PZFlubzZna0tqMjRPdlMyNmVLM0Z6eGZraXM1SGprOE82cGVkdTAxS29VYjEvT0djNjFSdGdmSS85V3FBV2E3WDFueEVZa3hSV2pra2d4bVN6NUw3YTN2cERqbGh2UDIxS2czNVNXQlNSank4TWJMVjJzOERlNTZmNzVZOUpIL1E2bzllODFEazlYcVRhY0VqYW50a24zeFhleTh4"
                        alt=""
                    />
                    <h4 class="title px-2 pt-4 text-justify font-semibold leading-6">
                        Microsoft оправи \"бъг\" с личните данни в Windows - Vesti.bg - Новини от
                        България и света
                    </h4>
                </div>
            </div>
            <div class="mt-4 grid grid-flow-row gap-4 md:grid-cols-12 md:grid-rows-6">
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    06
                </div>
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    07
                </div>
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    08
                </div>
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    09
                </div>
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    10
                </div>
                <div
                    class="col-span-4 row-span-3 grid h-52 place-content-center rounded-lg bg-white p-4 shadow-md sm:h-48"
                >
                    11
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Carousel from './Carousel.vue'
export default {
    components: { Carousel },
}
</script>

<style></style>
