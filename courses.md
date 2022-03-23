---
layout: post
title: Courses
description: Lorem ipsum dolor est
image: assets/images/pic11.jpg
nav-menu: true
---

Courses

{% for course in site.data.courses %}
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>{{ course.name }}</h2>
		</header>
	
		<p>{{ course.image }}</p> 
		<p>{{ course.github }}</p> 
		<p>{{ course.description }}</p> 
	</div>
</section> 
{% endfor %}


