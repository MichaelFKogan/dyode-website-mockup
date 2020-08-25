<template>

<div>

	<div class="collection-list-wrapper">
		<div class="collection-list-box col-sm-6">
			<div class="inner-container">
			<img class="collection-list-image" :src="require('../assets/img/Womens-Image.jpg')" />
			<div class="bottom-banner-text">Womens</div></div>
		</div>

		<div class="collection-list-box col-sm-6">
			<div class="inner-container">
			<img class="collection-list-image" :src="require('../assets/img/Mens-Image.jpg')" />
			<div class="bottom-banner-text">Mens</div>
		</div>
		</div>

		<div class="collection-list-box col-sm-12">
			<div class="inner-container">	
			<img class="collection-list-image mobile-hide" :src="require('../assets/img/Accessories-Image-Desktop.jpg')" />
			<img class="collection-list-image desktop-hide" :src="require('../assets/img/Accessories-Image-Mobile.jpg')" />			
			<div class="bottom-banner-text">Accessories</div>
		</div>
	</div>
	</div>	

</div>

</template>

<script>

  
  export default {
    name: 'CollectionList',
}
</script>

