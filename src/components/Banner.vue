<template>

<div>

<div class="hero-banner">
	<img class="hero-banner-image" :src="require('../assets/img/Hero-Image-1.jpg')" />
</div>

<div class="hero-inner-text-left">
	<div class="hero-title">Title Goes Here</div>
		<div class="hero-tagline">Tagline will go right here.</div>
	<div class="hero-button-container"><button class="hero-button">SHOP NOW</button></div>
</div>


</div>

</template>

<script>

  
  export default {
    name: 'Banner',
}
</script>

