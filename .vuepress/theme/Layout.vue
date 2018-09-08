<template>
<div>
    <sidebar></sidebar>
    <!--<right></right>-->
</div>
</template>

<script>
import sidebar from './common/sidebar'
import right from './right'
export default {
    name: "Layout",
    components: {
      sidebar,
      right
    },
    mounted() {
        // console.log(this.$page)
        // console.log(this.$site)
    }
}
</script>
<style lang="scss">
@import "./assets/scss/style";
</style>