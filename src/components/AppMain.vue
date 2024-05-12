<script>
import {store} from "/src/store.js"
import MovieCard from "/src/components/MovieCard.vue";
import TvSeriesCard from "/src/components/TvSeriesCard.vue"

export default {
    components: {
        MovieCard,
        TvSeriesCard
    },

    data(){
        return {
            store,
        }
    }
}

</script>

<template>
<MovieCard />
<TvSeriesCard />

</template>

<style>

</style>