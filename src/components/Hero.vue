<template>
  <section class="hero is-medium is-link is-fullheight-with-navbar">
    <div class="container">
      <div class="hero-body">
        <!-- <b-image :src="require('@/assets/avataaars.png')" :rounded="true" /> -->
        <img src="../assets/avataaars.png" />
        <div>
          <p class="title">Laura Brehm</p>
          <p class="subtitle">Software Engineer</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
img {
  width: 30%;
  height: 30%;
}
</style>