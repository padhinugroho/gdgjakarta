<template>
  <div>
    <Hero/>
    <About/>
    <VideoTeaser/>
    <CallToAction/>
    <PhotoHighlight/>
    <NextEvent/>
    <Partners/>
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue'
import About from '~/components/About.vue'
import PhotoHighlight from '~/components/PhotoHighlight.vue'
import VideoTeaser from '~/components/VideoTeaser.vue'
import Partners from '~/components/Partners.vue'
import CallToAction from '~/components/CallToAction.vue'
import NextEvent from '~/components/NextEvent.vue'
import MyFooter from '~/components/Footer.vue'

export default {
  components: {
    Hero,
    About,
    PhotoHighlight,
    VideoTeaser,
    Partners,
    CallToAction,
    NextEvent,
    MyFooter
  }
}
</script>

<style lang="sass">
  body, html
    scroll-behavior: smooth
</style>