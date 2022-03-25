<template>
  
  <theHeader />
  <theSmallHeader />
  <theSidebar />
  <theMobileSidebar />
  <theCategories />
  <theVideos />
  
</template>
<script>
import theHeader from './components/header/header.vue'
import theSmallHeader from './components/header/smallHeader.vue'
import theSidebar from './components/sidebar/theSidebar.vue'
import theMobileSidebar from './components/sidebar/theMobileSidebar.vue'
import theCategories from './components/categories/theCategory.vue'
import theVideos from './components/videos/theVideo.vue'


export default {
  components:{
    theHeader, theSmallHeader, theSidebar, theMobileSidebar, theCategories, theVideos
  }
}
</script>