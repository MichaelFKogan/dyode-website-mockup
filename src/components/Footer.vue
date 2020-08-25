<template>
	
<footer>	
	<div class="footer-container">
		<div class="minus-icon desktop-hide">-</div>

		<p class="feature-title footer-title">Customer Service</p>

		<p class="footer-menu-item">Accessibility</p>
		<p class="footer-menu-item">Contact Us</p>
		<p class="footer-menu-item">Return Policy</p>
		<p class="footer-menu-item">FAQ</p>
		<p class="footer-menu-item">Gift Certificates</p>
		<p class="footer-menu-item">Wishlist</p>
		<p class="footer-menu-item">About Us</p><div class="plus-icon desktop-hide">+</div>

		<p class="feature-title footer-title desktop-hide">Company</p>
		<p class="feature-title footer-title desktop-hide">Follow Us</p>

		<img class="social-icon desktop-hide" :src="require('../assets/img/Facebook-icon.png')" />
		<img class="social-icon desktop-hide" :src="require('../assets/img/Instagram-icon.png')" />
		<img class="social-icon desktop-hide" :src="require('../assets/img/Twitter-icon.png')" />		


	</div>
</footer>	

</template>

<script>

  
  export default {
    name: 'Footer',
}
</script>

