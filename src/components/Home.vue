<template>
    <div class="main">
        
    </div>
</template>

<script>
// @ is an alias to /src
// import {gsap} from 'gsap';
// import ScrollTrigger from 'gsap/ScrollTrigger';
export default {
  name: 'home',
  mounted(){
      this.firstAnimations()
  },
  components:{
  },
  methods: {
    //   firstAnimations(){
    //       var tl = gsap.timeline();
    //       tl.from(this.$refs.first, {y:2000, autoAlpha: 0, duration:1});
    //       tl.from(this.$refs.second, {y:-2000, autoAlpha: 0, duration:1},)
    //       tl.from(this.$refs.third, {y:2000, autoAlpha: 0, duration:1},)
    //       tl.from(this.$refs.circleSmall, {x:-500, duration:1},);
    //       tl.from(this.$refs.circleLarge, {x:1000, duration:1},"-=1");
    //       tl.from(this.$refs.watch, {x:1000, y:500, duration:1,},"-=0.5");
    //       tl.from(this.$refs.heading, {x:-1000, duration:1,}, "-=1");
    //       tl.from(this.$refs.lifestyle, {width:0, duration:1},"-=0.5");
    //   }
  }
}
</script>
<style lang="scss" scoped>




</style>
