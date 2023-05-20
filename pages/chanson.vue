<template>
  <div class="chanson-container">
    <div>
      <DangerousHTML
        html="<iframe width='1200' height='997' src='https://www.youtube.com/embed/q7LKEW8r8A4' title='YouTube video player' frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share' allowfullscreen></iframe>"
      ></DangerousHTML>
    </div>
  </div>
</template>

<script>
import DangerousHTML from 'dangerous-html/dist/vue/lib.mjs'

export default {
  name: 'Chanson',
  components: {
    DangerousHTML,
  },
  head: {
    title: 'chanson - frankie',
    meta: [
      {
        property: 'og:title',
        content: 'chanson - frankie',
      },
    ],
  },
}
</script>

<style scoped>
.chanson-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
</style>
