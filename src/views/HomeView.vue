<script setup>
    import HomeCard from '../components/HomeCard.vue';
</script>

<template>
    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
            Podcasts to make you smarter
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-stretch">
            <HomeCard image="/public/albumCovers/disturbed.jpg" title="Title is here" subTitle="Subtitle is here"  class="flex-1"/>
            <HomeCard image="/public/albumCovers/soad.webp" title="Title is here" subTitle="Subtitle is here" class="flex-1"/>
            <HomeCard class="flex-1 md:block hidden" image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here"  />
            <HomeCard class="flex-1 lg:block hidden" image="/public/albumCovers/Sabaton-Heroes-2014.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="flex-1 xl:block hidden" image="/public/albumCovers/nirvana.jpg" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended radio
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-center">
            <HomeCard image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here" class="flex-1"/>
            <HomeCard image="/public/albumCovers/nirvana.jpg" title="Title is here" subTitle="Subtitle is here" class="flex-1"/>
            <HomeCard class="flex-1 md:block hidden" image="/public/albumCovers/gameshow-two-door-cinema.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="flex-1 lg:block hidden" image="/public/albumCovers/Queen-Greatest-Hits-Cover-Art.jpeg.webp" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="flex-1 xl:block hidden" image="/public/albumCovers/soad.webp" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>

    <div class="p-8">
        <button
            type="button"
            class="text-white text-2xl font-semibold hover:underline cursor-pointer"
        >
        Recommended songs
        </button>

        <div class="py-1.5"></div>

        <div class="flex items-stretch">
            <HomeCard image="/public/albumCovers/DiariesOfAHero.png" title="Title is here" subTitle="Subtitle is here" class="flex-1"/>
            <HomeCard image="/public/albumCovers/30sectomars.jpg" title="Title is here" subTitle="Subtitle is here" class="flex-1"/>
            <HomeCard class="flex-1 md:block hidden" image="/public/albumCovers/disturbed.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="flex-1 lg:block hidden" image="/public/albumCovers/Sabaton-Heroes-2014.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="flex-1 xl:block hidden" image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>
</template>