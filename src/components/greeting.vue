<template>
    <div>
<!--        插值表达式-->
        <p>{{msg}}</p>
    </div>
</template>

<script>
    export default {
        name: "greeting",
        data(){
            return {
                msg: "Hello July"
            }
        }
    }
</script>

<style scoped>
    p {
        color: #42b983;
    }
</style>