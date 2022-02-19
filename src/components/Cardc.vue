<template>
  <div class="cardc">
    <img
      alt=""
      class="image"
      src="https://static.overlay-tech.com/assets/0e9552eb-280b-4704-b8da-c101e1b28f3d.png"
    />
    <div class="card-area">
      <div class="main-text">
        <p class="classic-long-sleeve-t-shirt">
          Classic Long Sleeve T-Shirt
        </p>
        <p class="information-about-this-product">
          Information about this product
        </p>
      </div>
      <Rating class="rating" />
      <p class="num-99-usd">$99 USD</p>
      <Button class="button" />
    </div>
  </div>
</template>

<script>
import Rating from "./Rating.vue";
import Button from "./Button.vue";
export default {
  name: "Cardc",
  components: { Rating, Button }
};
</script>

<style scoped>
.cardc {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: center;
}
.image {
  height: 408px;
  align-self: stretch;
  object-fit: cover;
}
.card-area {
  padding: 16px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.main-text {
  margin-bottom: 16px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  align-self: stretch;
}
.classic-long-sleeve-t-shirt {
  font-family: "Inter";
  font-size: 16px;
  font-weight: 700;
  line-height: 24px;
  color: rgba(13, 26, 38, 1);
  align-self: stretch;
  margin-bottom: 8px;
}
.information-about-this-product {
  font-family: "Inter";
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  color: rgba(48, 64, 80, 1);
  align-self: stretch;
  letter-spacing: 0.16px;
}
.rating {
  margin-bottom: 16px;
  width: 174px;
}
.num-99-usd {
  font-family: "Inter";
  font-size: 32px;
  font-weight: 700;
  line-height: 40px;
  color: rgba(13, 26, 38, 1);
  align-self: stretch;
  margin-bottom: 16px;
}
.button {
  align-self: stretch;
}
</style>