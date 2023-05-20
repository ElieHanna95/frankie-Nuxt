<template>
  <div class="vid-container">
    <div class="vid-div">
      <DangerousHTML
        html="<iframe width=1200' height='997' src='https://www.youtube.com/embed/rrwVY35juZc' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share' allowfullscreen></iframe>"
      ></DangerousHTML>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.mjs'

export default {
  name: 'Vid',
  components: {
    DangerousHTML,
  },
  head: {
    title: 'vid - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'vid - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.vid-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: flex-start;
  flex-direction: column;
  justify-content: center;
}
.vid-div {
  width: 1200px;
  height: 997px;
}
</style>
