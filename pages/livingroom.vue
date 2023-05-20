<template>
  <div class="livingroom-container">
    <div class="livingroom-pasted-image">
      <nuxt-link to="/vid" class="livingroom-youtube-vid button">
        Button
      </nuxt-link>
      <nuxt-link to="/chanson" class="livingroom-frankie-playing-guitar button">
        Button
      </nuxt-link>
      <nuxt-link to="/franklin-pic" class="livingroom-picture button">
        Button
      </nuxt-link>
      <button class="livingroom-game button">Button</button>
      <nuxt-link to="/" class="livingroom-exit button">Button</nuxt-link>
      <nuxt-link to="/book11" class="livingroom-info button">Button</nuxt-link>
    </div>
    <img
      alt="pastedImage"
      src="/playground_assets/pastedimage-vmd6-200h.png"
      class="livingroom-frank-and-fam"
    />
    <img
      alt="pastedImage"
      src="/playground_assets/pastedimage-i4bp-200h.gif"
      class="livingroom-fireplace"
    />
  </div>
</template>

<script>
export default {
  name: 'Livingroom',
  head: {
    title: 'livingroom - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'livingroom - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.livingroom-container {
  width: auto;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-end;
}
.livingroom-pasted-image {
  top: 0px;
  left: -1px;
  width: 1177px;
  height: 735px;
  display: flex;
  position: absolute;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  background-size: cover;
  justify-content: center;
  background-image: url("/playground_assets/pastedimage-hkz-800h.png");
  background-position: center;
}
.livingroom-youtube-vid {
  top: 293px;
  left: 66px;
  color: rgba(0, 0, 0, 0);
  width: 192px;
  height: 164px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  text-decoration: none;
  background-color: rgba(255, 255, 255, 0);
}
.livingroom-frankie-playing-guitar {
  top: 207px;
  left: 427px;
  color: rgba(0, 0, 0, 0);
  width: 89px;
  height: 168px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  padding-right: 83px;
  text-decoration: none;
  background-color: rgba(255, 255, 255, 0);
}
.livingroom-picture {
  top: 49px;
  left: 705px;
  color: rgba(0, 0, 0, 0);
  width: 105px;
  height: 86px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  text-decoration: none;
  background-color: rgba(255, 255, 255, 0);
}
.livingroom-game {
  top: 43px;
  color: transparent;
  right: 71px;
  width: 171px;
  height: 216px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  border-width: 0px;
  padding-bottom: 0px;
  background-color: transparent;
}
.livingroom-exit {
  left: 0px;
  color: transparent;
  width: 314px;
  bottom: -2px;
  height: 282px;
  z-index: 100;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  border-width: 0px;
  text-decoration: none;
  background-color: transparent;
}
.livingroom-info {
  color: transparent;
  right: 4px;
  width: 264px;
  bottom: 34px;
  height: 424px;
  position: absolute;
  border-width: 0px;
  border-radius: 0px;
  text-decoration: none;
  background-color: transparent;
}
.livingroom-frank-and-fam {
  top: 53px;
  flex: 0;
  left: 705px;
  width: 93px;
  height: 70px;
  position: absolute;
}
.livingroom-fireplace {
  top: 270px;
  left: 677px;
  width: 117px;
  height: 107px;
  position: absolute;
}
</style>
