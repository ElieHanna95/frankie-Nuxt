<template>
  <div class="book2-container">
    <div class="book2-pasted-image">
      <nuxt-link to="/book11" class="book2-navlink button">Button</nuxt-link>
      <nuxt-link to="/livingroom" class="book2-navlink1 button">Button</nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Book2',
  head: {
    title: 'book2 - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'book2 - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.book2-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.book2-pasted-image {
  top: 1px;
  left: -1px;
  width: 1151px;
  height: 1002px;
  display: flex;
  position: absolute;
  align-items: center;
  background-size: cover;
  justify-content: flex-start;
  background-image: url("/playground_assets/pastedimage-o3q-1100h.jpeg");
  background-position: center;
}
.book2-navlink {
  color: transparent;
  width: 309px;
  height: 863px;
  border-width: 0px;
  border-radius: 0px;
  text-decoration: none;
  background-color: transparent;
}
.book2-navlink1 {
  top: -4px;
  color: transparent;
  right: 10px;
  width: 257px;
  height: 942px;
  position: absolute;
  border-width: 0px;
  text-decoration: none;
  background-color: transparent;
}
</style>
