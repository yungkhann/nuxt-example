<template >
    <div>
        <Navigation></Navigation>
        <h1>Here is page of user {{id}} </h1>
    </div>
</template>
<script>
export default {
    data() {
        return {
            id:null
        }
    },
    mounted() {
        // this.id = this.$route.params.id
    },
    async asyncData(context) {
        const id  = context.params.id

        return {id}
    },
}
</script>
<style lang="">
    
</style>