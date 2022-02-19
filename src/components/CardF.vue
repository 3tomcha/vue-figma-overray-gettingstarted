<template>
  <div class="cardf">
    <img
      alt=""
      class="image"
      src="https://static.overlay-tech.com/assets/fb9675ff-465b-4fb2-8c55-568a59f91ff8.png"
    />
    <div class="card-area">
      <p class="classic-long-sleeve-t-shirt">
        Classic Long Sleeve T-Shirt
      </p>
      <div class="ratings">
        <Rating class="rating" />
        <p class="num-72">72</p>
      </div>
      <div class="ratings">
        <Badge class="badge" /><Badge class="badge" /><Badge
          class="badge"
        />
      </div>
      <p class="information-about-this-product">
        Information about this product.
      </p>
      <div class="quote">
        <Icon class="icon" />
        <p class="this-is-a-quote">“This is a quote.“</p>
      </div>
      <Divider class="divider" />
      <div class="cardf">
        <div class="feature">
          <Icon class="icon" />
          <p class="this-is-a-quote">Fast</p>
        </div>
        <div class="feature">
          <Icon class="icon" />
          <p class="this-is-a-quote">Fun</p>
        </div>
        <div class="feature">
          <Icon class="icon" />
          <p class="this-is-a-quote">Flirty</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Rating from "./Rating.vue"
import Badge from "./Badge.vue"
import Icon from "./Icon.vue"
import Divider from "./Divider.vue"
export default {
  name: "Cardf",
  components: { Rating, Badge, Icon, Divider }
};
</script>

<style lang="scss" scoped>
.cardf {
  display: flex;
  align-items: flex-start;
}
.image {
  width: 320px;
  align-self: stretch;
  object-fit: cover;
}
.card-area {
  background-color: rgba(255, 255, 255, 1);
  padding: 32px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  flex: 1;
}
.classic-long-sleeve-t-shirt {
  font-family: "Inter";
  font-size: 32px;
  font-weight: 700;
  line-height: 40px;
  color: rgba(13, 26, 38, 1);
  align-self: stretch;
  margin-bottom: 24px;
}
.ratings {
  margin-bottom: 24px;
  display: flex;
  align-items: center;
}
.rating {
  margin-right: 16px;
}
.num-72 {
  width: 19px;
  font-family: "Inter";
  font-size: 16px;
  font-weight: 400;
  line-height: 22px;
  color: rgba(13, 26, 38, 1);
  text-decoration: underline;
}
.badge {
  &:not(:last-of-type) {
    margin-right: 16px;
  }
}
.information-about-this-product {
  font-family: "Inter";
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  color: rgba(13, 26, 38, 1);
  align-self: stretch;
  margin-bottom: 24px;
  letter-spacing: 0.16px;
}
.quote {
  margin-bottom: 24px;
  display: flex;
  align-items: flex-start;
  align-self: stretch;
}
.icon {
  margin-right: 16px;
  width: 24px;
  height: 24px;
}
.this-is-a-quote {
  font-family: "Inter";
  font-size: 16px;
  font-weight: 400;
  line-height: 24px;
  color: rgba(48, 64, 80, 1);
  flex: 1;
  letter-spacing: 0.16px;
}
.divider {
  margin-bottom: 24px;
  height: 1px;
  align-self: stretch;
}
.feature {
  display: flex;
  align-items: flex-start;
  &:not(:last-of-type) {
    margin-right: 32px;
  }
}
</style>