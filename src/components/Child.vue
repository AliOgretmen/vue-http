<template>
    <div>
        <h2>Child Component</h2>
    </div>
</template>

<script>
    export default {
        name:'Child',
        beforeCreate(){
            console.log('Child befofeCreatehdhd()')
        }, 
        created(){
            console.log('Child created()')
        },
        beforeMount() {
            console.log('Child beforeMountlelel()')
        },
        mounted() {
            console.log('Child mounted()')
        },
        beforeUpdate() {
            console.log('Child beforeUpdatekekek()')
        },
        updated() {
            console.log('Child updated()')
        },
        beforeUnmount() {
            console.log('Child beforeUnmount()')
        },
        unmounted() {
            console.log('Child unmounted()')
        },
        
    }
</script>

<style scoped>

</style>