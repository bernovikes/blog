<template>
    <img src="@assets/images/avatar.jpg" alt="">
</template>

<script>
export default {
    name: "sidebar",
    data(){
      return {
          logo:''
      }
    },
    mounted(){
        this.logo = this.$site.themeConfig.logo
        console.log(this.logo)
    }
}
</script>