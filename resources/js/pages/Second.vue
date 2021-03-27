<template>
    <div>
        <img
            class="w-full max-h-96 object-cover object-center transition-all hover:lighter active:darker"
            src="https://trip.ee/photos/header3.jpg"
        />
        <div class="grid">
            <a href="" class="p-4 bg-purple-500 hover:bg-purple-600 grid gap-3">
                <div class="text-purple-300 text-base">Aafrika ›</div>
                <div class="text-white text-xl">Reunion</div>
            </a>
            <div class="grid grid-cols-2">
                <div class="p-8 bg-gray-100">
                    Trip.ee on reisihuviliste kogukond, keda ühendab reisipisik
                    ning huvi kaugete maade ja kultuuride vastu.
                </div>
            </div>
            <div class="p-8 grid gap-4">
                <button
                    class="justify-self-start bg-green-500 hover:bg-green-400 active:bg-green-600 text-white py-2 px-6 rounded font-medium"
                >
                    Liitu Trip.ee-ga
                </button>

                <br />

                <a
                    href=""
                    class="grid grid-cols-1 sm:grid-cols-2 gap-x-10 gap-y-6"
                >
                    <img
                        class="w-full h-64 sm:h-full object-cover object-center transition-all hover:lighter active:darker"
                        src="https://trip.ee/images/medium/bergamo-4440781_1920_1xzs.jpeg"
                    />
                    <div class="grid gap-8">
                        <a href="" class="flex items-center gap-2">
                            <icon-rightarrow
                                class="text-green-500 hover:text-green-600 w-4"
                            />
                            <h2
                                class="tracking-wider text-sm font-medium uppercase text-green-500 hover:text-green-600"
                            >
                                Uudised
                            </h2>
                        </a>
                        <h1
                            class="font-bold text-4xl sm:text-6xl tracking-tighter hover:text-gray-600 active:text-gray-800 transition"
                        >
                            Odavlennufirmad avavad suveks massiliselt uusi liine
                        </h1>
                        <div
                            class="text-xl sm:text-2xl font-sans sm:font-serif hover:text-gray-600 active:text-gray-800 transition"
                        >
                            Viimane aasta on lennufirmadele olnud üks suur
                            kannatuste rada. Väike lootus tekkis 2020. aasta
                            suvel, kuid pärast seda on tiksutud talveune
                            režiimil. Kuid näiliselt vaikse pinna all
                            pulbitsevad arengud, mis ootavad valla päästmist.
                        </div>
                        <a href="" class="flex gap-2 items-center">
                            <icon-user
                                class="rounded-full ring-2 ring-cyan-500 text-cyan-500 hover:text-gray-300 w-5"
                            />
                            <div class="font-medium text-cyan-500">
                                Veigo Kell
                            </div>
                            <div class="font-sans sm:font-serif text-gray-500">
                                12. tundi tagasi
                            </div>
                        </a>
                    </div>
                </a>

                <br />

                <div class="grid gap-6">
                    <h1 class="font-bold text-4xl tracking-tight">
                        Odavlennufirmad avavad suveks massiliselt uusi liine
                    </h1>
                </div>
                <br />
                <a href="" class="flex items-center gap-2">
                    <icon-rightarrow
                        class="text-gray-500 hover:text-gray-700 w-4"
                    />
                    <h2
                        class="tracking-wider text-sm font-medium uppercase text-green-600 hover:text-green-600"
                    >
                        Soodsad lennupiletid
                    </h2>
                </a>
                <a href="">
                    <h2
                        class="font-medium text-2xl text-blue-500 hover:text-blue-600"
                    >
                        Edasi-tagasi lennupiletid Lufthansaga Tallinnast
                        Kreetale alates 160€
                    </h2>
                </a>
                <div class="flex gap-3 items-center">
                    <a href="" class="text-gray-200 hover:text-gray-300 w-14">
                        <icon-user />
                    </a>
                    <div class="grid gap-3">
                        <a
                            href=""
                            class="font-medium text-xl hover:text-gray-800"
                        >
                            <h3>Kas praegu saab Sardiiniasse reisida?</h3>
                        </a>
                        <div class="flex gap-2">
                            <a
                                href=""
                                class="text-sm justify-self-start rounded-full px-2 py-1 border border-gray-400 text-gray-500 hover:bg-gray-100"
                                >2 comments
                            </a>
                            <a
                                href=""
                                class="text-sm justify-self-start rounded-full px-2 py-1 border border-orange-300 text-orange-500 hover:bg-orange-100"
                                >Itaalia ja Hispaania
                            </a>
                        </div>
                    </div>
                </div>
                <br />
                <h1 class="text-4xl font-medium">
                    Kas praegu saab Sardiiniasse reisida?
                </h1>
                <div class="text-lg">
                    Äkki mõni targem oskab nõu anda. Nimelt oleks plaanis minna
                    Gran Canariale ümberistumisega Bergamos. Saan hetkel aru, et
                    Bergamos peab olema test tehtud 48h enne. Kas on veel
                    täiendavaid piiranguid, mida ei osanud lennujaama lehelt
                    välja lugeda?
                </div>
                <div
                    class="grid grid-cols-auto-6 md:grid-cols-3 gap-4 w-auto overflow-x-auto"
                >
                    <a
                        v-for="i in 6"
                        :key="i"
                        href=""
                        class="relative w-56 h-56 md:w-auto"
                    >
                        <img
                            class="w-full h-full object-cover object-center"
                            src="https://trip.ee/images/medium/bergamo-4440781_1920_1xzs.jpeg"
                        />
                        <div
                            class="absolute inset-0 bg-gradient-to-b from-white via-[#777777] to-black opacity-50 hover:opacity-0"
                        />
                        <div class="absolute inset-0 p-4 flex items-end">
                            <div class="grid gap-3">
                                <h3 class="font-bold text-xl text-white">
                                    Edasi-tagasi lennupiletid Tallinnast
                                    Réunioni saarele
                                </h3>
                                <div
                                    class="bg-orange-500 hover:bg-orange-600 text-white font-medium text-base p-1 justify-self-start rounded"
                                >
                                    al 15€
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
        <br />

        <div class="p-4 bg-blue-100">
            <div class="bg-blue-400 text-xs">XS 12px Täpselt | XS 13px</div>
        </div>
        <div class="p-4 bg-blue-200">
            <div class="bg-blue-400 text-sm">SM 14px Täpselt | SM 14px</div>
        </div>
        <div class="p-4 bg-blue-100">
            <div class="bg-blue-400 text-base">BASE 16px Täpselt | MD 16px</div>
        </div>
        <div class="p-4 bg-blue-200">
            <div class="bg-blue-400 text-lg">MD 18px Täpselt | LG 19px</div>
        </div>
        <div class="p-4 bg-blue-100">
            <div class="bg-blue-400 text-xl">XL 20px Täpselt | XL 21px</div>
        </div>
        <div class="p-4 bg-blue-200">
            <div class="bg-blue-400 text-2xl">2XL | 24px Täpselt</div>
        </div>
        <div class="p-4 bg-blue-100">
            <div class="bg-blue-400 text-3xl">3XL 30px Täpselt | XXL 30px</div>
        </div>
        <div class="p-4 bg-blue-200">
            <div class="bg-blue-400 text-4xl">4XL 36px Täpselt</div>
        </div>
        <div class="p-4 bg-blue-100">
            <div class="bg-blue-400 text-5xl">5XL 48px Täpselt | XXXL 48px</div>
        </div>
        <div class="p-4 bg-blue-200">
            <div class="bg-blue-400 text-6xl">
                6XL 60px Täpselt | XXXXL 64px
            </div>
        </div>
    </div>
</template>
