---
layout: post
title: Experiments
permalink: /experiments/
---


<div class="post">
	<div class="row">
		<header class="post-header">
			<h1 class="post-title">{{ experiment.title }}</h1>
			<p class="post-meta">{{ experiment.date | date: "%b %-d, %Y" }}{% if experiment.author %} • {{ experiment.author }}{% endif %}{% if experiment.meta %} • {{ experiment.meta }}{% endif %}</p>
		</header>
		<div class="col-xs-1"></div>
		<article class="post-content col-xs-*">
		{{ content }}
		</article>
		<div class="col-xs-1"></div>
	</div>
</div>
