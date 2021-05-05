<template>
   <div class="box">
        <div class="card">
            <img :src="details.thumb" :alt="details.series">
        </div>
        <div class="title">
            {{ details.series}}
        </div>
   </div>
</template>

<script>
export default {
    name: 'Cards',
    props: ['details'],
};
</script>

<style scoped>
.box {
    flex-basis: calc(100% / 6);
}

.card {
    height: 200px;
    overflow: hidden;
}

.title {
    font-size: 18px;
    text-transform: uppercase;
    color: #fff;
    margin: 1.5rem 0;
}

</style>