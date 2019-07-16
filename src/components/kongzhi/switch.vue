<template>
    <div class="block">
        <p class="main-word">{{title}}</p>
        <div id="sw-content" class="butt">
            <input type="checkbox" class="make-switch"  checked data-on-color="primary" data-off-color="default">
        </div>
    </div>
</template>

<script>
    export default {
        name: "Kaiguan",
        data() {
            return {
                title: '开关控制'
            }
        }
    }
</script>

<style scoped>

</style>