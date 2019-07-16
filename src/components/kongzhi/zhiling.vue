<template>
    <div>
        <div class="block" v-for="item in items" :key="item.id">
            <p class="main-word">{{item.title}}</p>
            <div class="rad-sor">
                <div class="radio rad">
                    <label>
                        <input type="radio" name="item.inpname" checked>不启用
                    </label>
                </div>
                <div class="radio rad">
                    <label>
                        <input type="radio" name="item.inpname"/>30分钟
                    </label>
                </div>
                <div class="radio">
                    <label>
                        <input type="radio" name="item.inpname"/>60分钟
                    </label>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Zhiling",
        data() {
            return {
                items: [{
                    id: '001',
                    title: '定时开启',
                    inpname: 'Radio',
                    inpid1: 'Radioson1',
                    inpid2: 'Radioson2',
                    inpid3: 'Radioson3',
                    inpval1: 'option1',
                    inpval2: 'option2',
                    inpval3: 'option3',
                }, {
                    id: '002',
                    title: '定时关闭',
                    inpname: 'Radio1',
                    inpid1: 'Radiosoff1',
                    inpid2: 'Radiosoff2',
                    inpid3: 'Radiosoff3',
                    inpval1: 'option1',
                    inpval2: 'option2',
                    inpval3: 'option3',
                }]
            }
        }
    }
</script>

<style scoped>

</style>