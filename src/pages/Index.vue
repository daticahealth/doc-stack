<template>
  <Layout>
    <home-basic />
    <!-- <home-intro />
    <home-features />
    <home-fast />
    <home-how-it-works />
    <home-tabs />
    <home-blog /> -->
  </Layout>
</template>

<script>
import HomeBasic from '@/components/home/HomeBasic.vue'
// import HomeIntro from '@/components/home/HomeIntro.vue'
// import HomeFeatures from '@/components/home/HomeFeatures.vue'
// import HomeTabs from '@/components/home/HomeTabs.vue'
// import HomeFast from '@/components/home/HomeFast.vue'

// import HomeBlog from '@/components/home/HomeBlog.vue'
// import HomeHowItWorks from '@/components/home/HomeHowItWorks.vue'

export default {
  components: {
    HomeBasic,
    // HomeIntro,
    // HomeFeatures,
    // HomeTabs,
    // HomeFast,
    // HomeBlog,
    // HomeHowItWorks,
  },
  
  metaInfo: {
    title: 'Basic Documentation Stack',
    meta: [
      { name: 'description', content: 'This is a demo for a documenation stack solution; built with Gridsome (gridsome.org)'
      }
    ],
  }
}
</script>


