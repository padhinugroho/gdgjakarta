<template>
  <div>
    <Navbar/>
    <nuxt/>
    <my-footer/>
  </div>
</template>

<script>
import Navbar from '~/components/Navbar.vue'
import Hero from '~/components/Hero.vue'
import About from '~/components/About.vue'
import PhotoHighlight from '~/components/PhotoHighlight.vue'
import VideoTeaser from '~/components/VideoTeaser.vue'
import Partners from '~/components/Partners.vue'
import MyFooter from '~/components/Footer.vue'
import NextEvent from '~/components/NextEvent.vue'

export default {
  components: {
    Navbar,
    Hero,
    About,
    PhotoHighlight,
    VideoTeaser,
    NextEvent,
    Partners,
    MyFooter
  }
}
</script>