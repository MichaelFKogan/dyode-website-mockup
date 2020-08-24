<template>

<div>


	<div class="featured-collection-wrapper">
		<div class="feature-title">New Arrivals</div>

				<div class="">
					<img class="" :src="require('../assets/img/Arrow-Left.png')" />
				</div>

				<div class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
					<div class="product-title">Product Title</div>
					Women's T-Shirt
					$19.99 
				</div>


				<div class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
				</div>

				<div class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
				</div>


				<div class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
				</div>		

				<div class="">
					<img class="" :src="require('../assets/img/Arrow-Right.png')" />
				</div>		
	</div>

</div>

</template>

<script>

  
  export default {
    name: 'FeaturedCollection',
}
</script>

