<template>
  <div class="franklin-pic-container">
    <div class="franklin-pic-pasted-image">
      <a
        href="https://youtu.be/rrwVY35juZc"
        target="_blank"
        rel="noreferrer noopener"
        class="franklin-pic-youtube-vid button"
      >
        Button
      </a>
      <button class="franklin-pic-frankie-playing-guitar button">Button</button>
      <button class="franklin-pic-picture button">Button</button>
      <button class="franklin-pic-game button">Button</button>
      <nuxt-link to="/" class="franklin-pic-exit button">Button</nuxt-link>
      <button class="franklin-pic-info button">Button</button>
      <img
        alt="pastedImage"
        src="/playground_assets/pastedimage-vmd6-600h.png"
        class="franklin-pic-frank-and-fam"
      />
      <nuxt-link to="/livingroom" class="franklin-pic-back button">
        Button
      </nuxt-link>
    </div>
    <img
      alt="pastedImage"
      src="/playground_assets/pastedimage-i4bp-200h.gif"
      class="franklin-pic-fireplace"
    />
    <img
      alt="pastedImage"
      src="/playground_assets/pastedimage-vmd6-600h.png"
      class="franklin-pic-frank-and-fam1"
    />
    <img
      alt="pastedImage"
      src="/playground_assets/pastedimage-mykh-1100w.png"
      class="franklin-pic-pasted-image1"
    />
  </div>
</template>

<script>
export default {
  name: 'FranklinPic',
  head: {
    title: 'franklin-pic - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'franklin-pic - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.franklin-pic-container {
  width: auto;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
  justify-content: flex-end;
}
.franklin-pic-pasted-image {
  top: -3px;
  left: 1px;
  width: 1177px;
  height: 735px;
  display: flex;
  position: absolute;
  align-items: center;
  padding-top: var(--dl-space-space-halfunit);
  background-size: cover;
  justify-content: flex-start;
  background-image: url("/playground_assets/pastedimage-hkz-800h.png");
  background-position: center;
}
.franklin-pic-youtube-vid {
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
.franklin-pic-frankie-playing-guitar {
  top: 207px;
  left: 427px;
  color: rgba(0, 0, 0, 0);
  width: 89px;
  height: 168px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  padding-right: 83px;
  background-color: rgba(255, 255, 255, 0);
}
.franklin-pic-picture {
  top: 49px;
  left: 705px;
  color: rgba(0, 0, 0, 0);
  width: 105px;
  height: 86px;
  position: absolute;
  border-color: rgba(0, 0, 0, 0);
  background-color: rgba(255, 255, 255, 0);
}
.franklin-pic-game {
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
.franklin-pic-exit {
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
.franklin-pic-info {
  color: transparent;
  right: 4px;
  width: 264px;
  bottom: 34px;
  height: 424px;
  position: absolute;
  border-width: 0px;
  border-radius: 0px;
  background-color: transparent;
}
.franklin-pic-frank-and-fam {
  top: 53px;
  flex: 0;
  left: 706px;
  width: 93px;
  height: 70px;
  position: absolute;
}
.franklin-pic-back {
  top: 0px;
  left: -1px;
  color: transparent;
  right: 0px;
  width: 1177px;
  bottom: 0];
  height: 735px;
  position: absolute;
  border-width: 0px;
  text-decoration: none;
  background-color: transparent;
}
.franklin-pic-fireplace {
  top: 267px;
  left: 679px;
  width: 117px;
  height: 107px;
  position: absolute;
}
.franklin-pic-frank-and-fam1 {
  top: 100px;
  flex: 0;
  left: 204px;
  width: 809px;
  height: 520px;
  position: absolute;
}
.franklin-pic-pasted-image1 {
  top: -5px;
  left: 92px;
  width: 1040px;
  height: 713px;
  position: absolute;
}
</style>
