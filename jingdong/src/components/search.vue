<template>
  <div id="search">

    <input class="input" type="text"/>
    <svg class="icon camera" aria-hidden="true">
      <use xlink:href="#icon-xiangji"></use>
    </svg>
    <button class="btn">
      <svg class="icon" aria-hidden="true">
        <use xlink:href="#icon-sousuo"></use>
      </svg>
    </button>
  </div>
</template>

<script>
export default {
  name: "search",
};
</script>

<style scoped>
#search {
  position: relative;
  height: 35px;
  border: 2px solid red;
  margin-bottom: 5px;
}

.input {
  width: 85%;
  height: 100%;
  border: none;
}

.btn {
  width: 14.6%;
  height: 100%;
  float: right;
  border: 1px solid rgb(191, 31, 31);
  background-color: red;
  box-sizing: content-box;
}

.icon {
  font-size: 25px;
  color: white;
}

.camera {
  position: absolute;
  top: 10px;
  right: 90px;
  font-size: 15px;
  color: var(--darkgray);
}
</style>