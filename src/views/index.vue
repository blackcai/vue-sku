<template>
  <div>
    <sku-wrap></sku-wrap>
  </div>
</template>

<script>
  export default {
    name: 'sku-index',
    components: {
      SkuWrap: resolve => {
        return require(['@/components/sku.vue'], resolve)
      }
    },
    data() {
      return {
      }
    }
  }
</script>
