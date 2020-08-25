<template>

<div>


	<div class="featured-collection-wrapper">
		<div class="feature-title">New Arrivals</div>
	

	<div class="arrow-container">
					<div class="featured-collection-arrow arrow-left">
						<img class="arrow-image" :src="require('../assets/img/Arrow-Left.png')" />
					</div>

					<div class="featured-collection-arrow arrow-right">
						<img class="arrow-image" :src="require('../assets/img/Arrow-Right.png')" />
					</div>	
	</div>

			<div class="slider-wrap">
				<div class="featured-collection-image-wrap col-sm-6">
				<div class="featured-inner-container">	
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
					<div class="product-info">
						<div class="product-title">Product Title</div>
						<div class="product-item">Women's T-Shirt</div>
						<div class="price">$19.99</div>
					</div> 
				</div>
				</div>

				<div class="featured-collection-image-wrap col-sm-6">
					<div class="featured-inner-container">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
					<div class="product-info">
						<div class="product-title">Product Title</div>
						<div class="product-item">Women's T-Shirt</div>
						<div class="price">$19.99</div>
					</div> 
				</div>
			</div>

				<div style="display:none;" class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
				</div>


				<div style="display:none;" class="featured-collection-image-wrap">
					<img class="featured-collection-image" :src="require('../assets/img/Product-Image-1.jpg')" />
				</div>		
			</div>
	
	</div>

</div>

</template>

<script>

  
  export default {
    name: 'FeaturedCollection',
}
</script>

