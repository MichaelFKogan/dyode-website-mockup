<template>

<div>

	<div class="collection-list-wrapper">
		<div class="collection-list-box">
			<img class="collection-list-image" :src="require('../assets/img/Womens-Image.jpg')" />
			<div class="bottom-banner-text">Womens</div>
		</div>

		<div class="collection-list-box">
			<img class="collection-list-image" :src="require('../assets/img/Mens-Image.jpg')" />
			<div class="bottom-banner-text">Mens</div>
		</div>

		<div class="collection-list-box">
			<img class="collection-list-image" :src="require('../assets/img/Accessories-Image.jpg')" />
			<div class="bottom-banner-text">Accessories</div>
		</div>
	</div>	

</div>

</template>

<script>

  
  export default {
    name: 'CollectionList',
}
</script>

