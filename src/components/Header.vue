<template>
  <nav class="navbar is-link">
    <div class="container">
      <div class="navbar-start">
        <a class="navbar-item">Blog</a>
      </div>
      <div class="navbar-end">
        <span class="navbar-item">
          <a
            class="button is-primary is-inverted"
            href="https://github.com/laurazard"
          >
            <font-awesome-icon :icon="['fab', 'github']" />
            <span style="margin-left: 5px">GitHub</span>
          </a>
        </span>
        <span class="navbar-item">
          <a
            class="button is-primary is-inverted"
            href="https://www.linkedin.com/in/laura-fbrehm/"
          >
            <font-awesome-icon :icon="['fab', 'linkedin']" />
            <span style="margin-left: 5px">LinkedIn</span>
          </a>
        </span>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
</style>