<template>
  <div class="container mx-auto mt-6 text-white text-center">
      <div ref="heading">
        <div class="text-3xl">iPhone 12 Pro</div>
        <div class="text-6xl mb-6">Its a leap year.</div>
      </div>
      <div class="ml-48">
        <video src="../assets/large.mp4"  class="w-full" muted autoplay></video>
      </div>
  </div>
</template>

<script>
import {gsap} from 'gsap';
import ScrollTrigger from 'gsap/ScrollTrigger';
gsap.registerPlugin(ScrollTrigger);
export default {
mounted(){
    this.firstAnimations();
},
methods:{
    firstAnimations(){
    gsap.from(this.$refs.heading, {autoAlpha:0, x: -50, delay:4, duration: 1,});
        var tl = gsap.timeline({ScrollTrigger: {
            trigger: ".heading",
            scrub: true
        }});
        tl.from(this.$refs.heading, {y: 500})
    }
}
}
</script>

<style>

</style>