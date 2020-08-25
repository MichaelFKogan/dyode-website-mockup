<template>
	

	<div class="instagram-wrapper">
		<div class="feature-title">Follow us on Instagram</div>

		<div class="image-container col-sm-3">
			<div class="inner-insta-container">
			<img class="insta-image" :src="require('../assets/img/Social-1.jpg')" />
			</div>
		</div>

		<div class="image-container col-sm-3">
			<div class="inner-insta-container">
			<img class="insta-image" :src="require('../assets/img/Social-2.jpg')" />
			</div>
		</div>

		<div class="image-container col-sm-3">
			<div class="inner-insta-container">
			<img class="insta-image" :src="require('../assets/img/Social-3.jpg')" />
			</div>
		</div>		


	</div>

</template>

<script>

  
  export default {
    name: 'Instagram',
}
</script>

