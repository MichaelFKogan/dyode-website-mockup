<template>
  <div id="app">
	<AnnouncementBar />
	<Header />
	<Banner />
	<CollectionList />	
	<FeaturedCollection />
	<ImageWithTextOverlay />
	<Instagram />
	<Newsletter />	
	<Footer />	

  </div>
</template>

<script>
import '@/assets/styles/scss/custom.scss'

import AnnouncementBar from './components/Announcement-bar.vue'
import Header from './components/Header.vue'
import Banner from './components/Banner.vue'
import CollectionList from './components/Collection-list.vue'
import FeaturedCollection from './components/Featured-collection.vue'
import ImageWithTextOverlay from './components/Image-with-text-overlay.vue'
import Instagram from './components/Instagram.vue'
import Newsletter from './components/Newsletter.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
  AnnouncementBar, Header, Banner, CollectionList, FeaturedCollection, ImageWithTextOverlay, Instagram, Newsletter, Footer,
  }
}
</script>

<style>
#app {}
</style>
