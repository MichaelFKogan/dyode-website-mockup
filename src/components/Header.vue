<template>

<header class="site-header">
   
<div class="navbar-container">

	<div class="grid_item-left desktop-hide">    
		<i class="fa fa-bars fa-3x"></i>
	</div>

	<div class="header-logo">
		<a href="/">
			<img class="header-logo-img" :src="require('../assets/img/Logo.png')" />
		</a>
	</div>
        
	<nav class="" id="navbar-menu" role="navigation">
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

    <i class="fa fa-shopping-cart desktop-hide"></i>	

</div>   

</header>

</template>

<script>

  
  export default {
    name: 'Header',
}
</script>

