<template>

<header class="site-header">
    

	<a href="/">
		<!-- <p class="site-header__logo-link" >logo</p> -->
		<img class="header-logo" :src="require('../assets/img/Logo.png')" />
	</a>

        
	<nav class="" id="" role="navigation">
		<ul>
			<li>
				<a href="/" class="sit-nav__link">
					<span class="site-nav__label">Womens</span>
				</a>
			</li>
			<li>
				<a href="/" class="sit-nav__link">
					<span class="site-nav__label">Mens</span>
				</a>
			</li>
			<li>
				<a href="/" class="sit-nav__link">
					<span class="site-nav__label">Accessories</span>
				</a>
			</li>
			<li>
				<a href="/" class="sit-nav__link">
					<span class="site-nav__label">Sale!</span>
				</a>
			</li>
		</ul>
	</nav>	

</header>

</template>

<script>

  
  export default {
    name: 'Header',
}
</script>

