<template>

<div class="hero-banner">
	<img class="hero-banner-image mobile-hide" :src="require('../assets/img/Hero-Image-2-Desktop.jpg')" />
	<img class="hero-banner-image desktop-hide" :src="require('../assets/img/Hero-Image-2-Mobile.jpg')" />	
</div>

</template>

<script>

  
  export default {
    name: 'ImageWithTextOverlay',
}
</script>

