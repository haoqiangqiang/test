<template>
    <div class="header">
        <p class="head-tit t1">{{ title }}</p>
        <p class="head-tit t2">{{ title2 }}</p>
    </div>
</template>

<script>
export default {
    name: 'Header',
    data() {
        return {
            title: '5G通信',
            title2: '智能空开通信'
        }
    }
}
</script>

<style scoped>
    .header {
        display: flex;
        justify-content: center;
        flex-direction: column;
        width: 100%;
        height: 10rem;
        color: white;
        background: url(../../images/header.jpg) center center no-repeat;
        background-size: cover;
    }
    .head-tit {
        display: flex;
        justify-content: center;
    }
    .t1 {
        font-size: 2rem;
        font-weight: bold;
    }
    .t2 {
        font-size: 1.5rem;
    }
    p{
        margin: 0 0 10px
    }
</style>