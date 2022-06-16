<script setup>
</script>

<template>
    <div class="w-full h-full relative background">
        <div class="vignette hidden lg:block"></div>
        <img class="w-2/3 lg:w-1/4 m-auto pt-16 lg:pt-28 pb:10 lg:pb-20" src="../assets/images/Logo_White.png" alt="">
        <div class="w-2/3 lg:w-1/2 m-auto text-center leading-6 text-2xl lg:text-5xl">
            <p>We are a videogames development studio that loves videogames and now we want to contribute with our own.
            </p>
            <p class="pt-2 lg:pt-10">More news comming soon :)</p>
        </div>
        <div class="floor"></div>
        <img class="decoration smallTree smallTreeLeft hidden lg:w-2/10" src="../assets/images/small_tree.png" alt="">
        <img class="decoration smallTree smallTreeRight hidden lg:w-2/10" src="../assets/images/small_tree.png" alt="">
        <img class="decoration bigTree bigTreeRight w-96 lg:w-2/5" src="../assets/images/big_tree.png" alt="">
        <img class="decoration bigTree bigTreeLeft w-96 lg:w-2/5" src="../assets/images/big_tree.png" alt="">
        <img class="decoration decoration1 hidden lg:block" src="../assets/images/decoration1.png" alt="">
        <img class="decoration decoration2" src="../assets/images/decoration2.png" alt="">
        <img class="decoration decoration4 hidden lg:block" src="../assets/images/decoration4.png" alt="">
        <img class="decoration decoration5 hidden lg:block" src="../assets/images/decoration5.png" alt="">
        <img class="decoration decoration6 hidden lg:block" src="../assets/images/decoration6.png" alt="">
    </div>
</template>


<style scoped>
.background {
    background: url("../assets/images/background.png") no-repeat;
    background-size: cover;
    overflow: hidden;
}

.vignette {
    position: absolute;
    width: 100%;
    height: 100%;
    background: radial-gradient(transparent 40%, black), rgba(0, 0, 0, 0);
}

.decoration {
    position: absolute;
    bottom: 4em;
}

.smallTreeLeft {
    left: 4.5em;
}

.smallTreeRight {
    right: 3em;
}

.bigTreeRight {
    right: -10em;
}

.bigTreeLeft {
    left: -15em;
}

.floor {
    position: absolute;
    bottom: 0;
    height: 4em;
    width: 100%;
    background: url('../assets/images/floor.png') no-repeat top;
    background-size: cover;
}

.decoration1 {
    left: 20em;
    width: 25em;
}

.decoration2 {
    left: 50em;
    /* width: 25em; */
}

.decoration4 {
    right: 22em;
    width: 12em;
}

.decoration5 {
    right: 16em;
    width: 8em;
}

.decoration6 {
    left: 16em;
    width: 8em;
}
</style>