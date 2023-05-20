<template>
  <div class="book11-container">
    <div class="book11-pasted-image">
      <nuxt-link to="/book2" class="book11-other-page button">Button</nuxt-link>
      <nuxt-link to="/livingroom" class="book11-back-book button">
        Button
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Book11',
  head: {
    title: 'book11 - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'book11 - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.book11-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.book11-pasted-image {
  top: 13px;
  right: -8px;
  width: 1155px;
  height: 875px;
  display: flex;
  position: absolute;
  align-items: center;
  background-size: cover;
  justify-content: flex-start;
  background-image: url("/playground_assets/pastedimage-tw4-900h.jpeg");
  background-position: center;
}
.book11-other-page {
  top: 79px;
  color: transparent;
  right: 22px;
  width: 501px;
  height: 587px;
  position: absolute;
  border-width: 0px;
  border-radius: 0px;
  text-decoration: none;
  background-color: transparent;
}
.book11-back-book {
  top: 241px;
  left: 2px;
  color: transparent;
  width: 221px;
  height: 312px;
  z-index: 100;
  position: absolute;
  border-width: 0px;
  border-radius: 0px;
  text-decoration: none;
  background-color: transparent;
}
</style>
