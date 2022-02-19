<template>
  <div class="rating">
    <Icon class="icon" /><Icon class="icon" /><Icon
      class="icon"
    /><Icon class="icon" /><Icon class="icon" />
  </div>
</template>

<script>
import Icon from "./Icon.vue";

export default {
  name: "Rating",
  components: { Icon }
};
</script>

<style lang="scss" scoped>
.rating {
  display: flex;
  align-items: center;
}
.icon {
  width: 24px;
  height: 24px;
  &:not(:last-of-type) {
    margin-right: 8px;
  }
}
</style>