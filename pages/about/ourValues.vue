<template>
  <div class="content">
    <CategoryNav :categoryIndex="categoryIndex" :activeIndex="selectedIndex"></CategoryNav>
    <OurValuesMain></OurValuesMain>
    <OurValuesContent></OurValuesContent>
  </div>
</template>

<script>
export default {
  layout: 'default',
  data() {
    return{
      categoryIndex: 7,
      selectedIndex: 8,
    }
  }
}
</script>
