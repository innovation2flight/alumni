---
layout: page
title: JPL i2F Alumni
---

Innovation to Flight Projects seek to facilitate a rapid maturation of new concepts, and their test and validation in flight demonstrations. 2018 pilot studies will involve fast development and prototyping, with regular flight tests at the end of the summer, or a plan to test soon after. Prototypes will be mechanical, electrical or robotics systems, and would be tested in an atmospheric platform, some in balloon and some in UAVs. The candidates will assist in preparing technology for flight tests and validation and improve flight. Skills in the areas of systems engineering, mechanical, electrical, power, communications or computer engineering.

## Class of 2018

<section class="people">
	{% for member in site.members %}
	<a href="{{ site.baseurl }}{{ member.url }}">
		<span class="image">
			<img src="images/headshots/{{ member.image }}" alt="" />
		</span>
		<h3>{{ member.name }}</h3>
		<p>{{ member.school }} | {{ member.major}}</p>
		<p>{{ member.project }}</p>
	</a>
	{% endfor %}
</section>

<br>


