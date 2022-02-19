<template>
  <div class="badge-two"><p class="badge">Classic</p></div>
</template>

<script>
export default {
  name: "Badge"
};
</script>

<style lang="scss" scoped>
.badge-two {
  background-color: rgba(239, 240, 240, 1);
  border-radius: 99px;
  padding: 4px 8px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.badge {
  font-family: "Inter";
  font-size: 16px;
  font-weight: 700;
  line-height: 20px;
  color: rgba(13, 26, 38, 1);
  letter-spacing: 0.64px;
}
</style>