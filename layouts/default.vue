<template>
  <div id="wrap">
    <WebHeader />
    <div ref="Top"></div>
    <Nuxt />
    <WebFooter />
  </div>
</template>

<script>
export default{
  watch: {
    '$route' () {
      this.scrollToTop();
    }
  },
  methods: {
    scrollToTop() {
      this.$refs.Top.scrollIntoView();
    }
  }
}
</script>

<style scoped>
#wrap {
  @apply w-full max-w-[1920px] min-w-[1640px] mx-auto overflow-x-hidden;
}
</style>