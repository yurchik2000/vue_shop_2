<template>
    <div class="main__wrapper">           
        <CatalogView /> 
        <CartView />        
    </div>
</template>

<script>

    import CatalogView from '@/components/CatalogView.vue'
    import CartView from '@/components/CartView.vue'
    
    export default {
        name: 'MainWrapper',
        components: {
            CatalogView,
            CartView
        },
        props: {

        },
        data() {
            return {
                
            }
        },
        computed: {

        },
        methods: {

        },
        watch: {

        },
        mounted() {
            
        }
    }

</script>

<style lang="scss" scoped>
    .main__wrapper{
        display: flex;
        justify-content: center;
        align-items: center;
        background: $primary-bg;
        max-width: 900px;
        margin: 0 auto;
    }
</style>
