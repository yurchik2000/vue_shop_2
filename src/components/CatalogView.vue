<template>
    <div class="catalog__view">
        <h1 class="catalog__title">Catalog</h1>
        <CatalogItem />
    </div>
</template>

<script>

import CatalogItem from '@/components/CatalogItem.vue'

export default {
    name: "CatalogView",
    components: {
        CatalogItem
    }

}
</script>

<style lang="scss" scoped>
    .catalog__view{
        text-align: center;
    }
    .catalog__title{
        font-size: 24px;
    }
</style>