<template>
  <div>
    <div class="card-bkgrnd">
      <div class="card-top">
        Hello
        <object
          type="image/svg+xml"
          data="../../assets/bg-pattern-card.svg"
          width="100"
          height="100"
        ></object>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ProfileCard",
  components: {},
};
</script>

<style>
.card-bkgrnd {
  width: 24rem;
  height: 24rem;
  background: white;
  z-index: 3;
  border-radius: 1rem;
  box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.15);
  display: flex;
  flex-direction: column;
}
.card-top {
  z-index: 4;
}
</style>