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

        <div class="flex items-center">
            <HomeCard image="/public/albumCovers/disturbed.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="/public/albumCovers/soad.webp" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="/public/albumCovers/Sabaton-Heroes-2014.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="/public/albumCovers/nirvana.jpg" title="Title is here" subTitle="Subtitle is here" />
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
            <HomeCard image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="/public/albumCovers/nirvana.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="/public/albumCovers/gameshow-two-door-cinema.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="/public/albumCovers/Queen-Greatest-Hits-Cover-Art.jpeg.webp" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="/public/albumCovers/soad.webp" title="Title is here" subTitle="Subtitle is here" />
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

        <div class="flex items-center">
            <HomeCard image="/public/albumCovers/DiariesOfAHero.png" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard image="/public/albumCovers/30sectomars.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="md:block hidden" image="/public/albumCovers/disturbed.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="lg:block hidden" image="/public/albumCovers/Sabaton-Heroes-2014.jpg" title="Title is here" subTitle="Subtitle is here" />
            <HomeCard class="xl:block hidden" image="/public/albumCovers/rammstein.webp" title="Title is here" subTitle="Subtitle is here" />
        </div>
    </div>
</template>