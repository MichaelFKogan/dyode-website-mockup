<template>

<div class="newsletter-wrapper">

<div class="email-icon-wrapper">	
	<img class="email-icon-image" :src="require('../assets/img/Email-icon.png')" />
</div>	
	<div class="feature-title newsletter-title">Sign up & stay connected</div>	

	<div class="newletter-text-wrapper">
		<p class="newsletter-text">Sign up for the newsleTer and get 20% off! Get access to exclusive offers and be the first to know when new stuff drops.</p>
	</div>

	<div class="email-container">
		<div class="search-padder">
		<input class="email-input" type="email" name="email" placeholder="Your Email Address">
		</div>
		<button class="subscribe">Subscribe</button>
	</div>

</div>

</template>

<script>

  
  export default {
    name: 'Newsletter',
}
</script>
