<template>
  <div class="icon">
    <div class="group"></div>
    <img
      alt=""
      class="vector"
      src="https://static.overlay-tech.com/assets/4c1a1be5-a98c-4115-9218-7c69aa7ea908.svg"
    />
  </div>
</template>

<script>
export default {
  name: "Icon"
};
</script>

<style lang="scss" scoped>
.icon {
  position: relative;
}
.group {
  width: 24px;
  height: 24px;
  position: relative;
}
.vector {
  width: 83.33%;
  height: 79.17%;
  position: absolute;
  left: 2px;
  top: 2px;
}
</style>