<template>
  <div class="home-container">
    <div class="home-container1">
      <div class="home-pasted-image">
        <nuxt-link to="/livingroom" class="home-navlink button">
          Button 
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  head: {
    title: 'frankie',
    meta: [
      {
        property: 'og:title',
        content: 'frankie',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-container1 {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-pasted-image {
  width: 100%;
  height: 752px;
  display: flex;
  position: relative;
  align-items: center;
  background-size: cover;
  justify-content: center;
  background-image: url("/playground_assets/pastedimage-wzro-800h.png");
  background-position: center;
}

.home-navlink {
  top: 402px;
  flex: 1;
  left: 505px;
  color: rgba(0, 0, 0, 0);
  width: 117px;
  height: 140px;
  position: absolute;
  box-shadow: 5px 5px 10px 0px rgba(212, 212, 212, 0),5px 5px 10px 0px rgba(212, 212, 212, 0);
  border-color: rgba(0, 0, 0, 0);
  border-width: 0px;
  padding-right: 42px;
  text-decoration: none;
  background-color: rgba(255, 255, 255, 0);
}
</style>
