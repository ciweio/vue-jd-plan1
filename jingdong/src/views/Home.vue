<template>
  <div class="root">

    <ShortCut class="w"></ShortCut>
    <indexHeader class="w"></indexHeader>
    <top class="w"></top>
  </div>
</template>

<script>
import ShortCut from "../components/ShortCut.vue"
import indexHeader from '../components/indexHeader.vue'
import top from '../components/top.vue'

export default {
  name: "Home",
  components: {
    ShortCut,
    indexHeader,
    top,
  }
}
</script>

<style>

.w {
  width: 1190px;
  margin: 0 auto;
}

.root {
  background-color: var(--gray-bg);
}

li {
  list-style: none;
}
</style>