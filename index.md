---
layout: home
title: Home
landing-title: Portfolio
description: Take a look around.
image: 
author: 
nav-menu: 
---

<!-- Banner -->
<section id="banner">
	<div class="inner">
		<header class="major">
			<h2>{{ page.landing-title }}</h2>
		</header>
		<p>{{ page.description }}</p>
		<ul class="actions">
			<li><a href="#one" class="button next scrolly">View Work</a></li>
		</ul>
	</div>
</section>

<!-- Main -->
<div id="main">



<!-- One -->
{% include tiles.html %}

</div>

