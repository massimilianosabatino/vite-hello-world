<script>
    export default {
        data() {
            return {
                url: 'src/assets/6208958.webp'
            }
        }
    }
</script>
<template>
    <div>
        <img :src="url" alt="foto">
    </div>
</template>
<style>
div {
    width: 90%;
    margin: 0 auto;
}

img {
    width: 100%;
}
</style>