<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>


export default {}
</script>

<style lang='less'>
//@darkgray:rgb(153,153,153);
* {
  margin: 0;
  padding: 0;
  font: 12px/1.5 Microsoft YaHei, Heiti SC, tahoma, arial, Hiragino Sans GB,
  "\5B8B\4F53", sans-serif;
}

:root {
  --gray: rgb(227, 228, 229);
  --red: rgb(225, 37, 27);
  --darkgray: rgb(153, 153, 153);
  --gray-bg: rgb(244, 244, 244);
}

a {
  text-decoration: none;
  color: inherit;
  font-size: inherit;
}

</style>