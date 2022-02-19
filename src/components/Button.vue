<template>
  <div class="button">
    <p class="button-text">Primary Button</p>
  </div>
</template>

<script>
export default {
  name: "Button"
};
</script>

<style lang="scss" scoped>
.button {
  background-color: rgba(4, 125, 149, 1);
  border-radius: 4px;
  padding: 12px 24px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.button-text {
  font-family: "Inter";
  font-size: 20px;
  font-weight: 700;
  line-height: 24px;
  color: rgba(255, 255, 255, 1);
  letter-spacing: 0.8px;
}
</style>