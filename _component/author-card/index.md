---
title: Author Card
layout: component
path_slug: author-card
category: content
iframe_height: medium
---

{% include_relative _notes.md %}

<div class="cf">
	<a href="{{ site.baseurl }}/component/{{ page.path_slug }}/example.html" target="_blank" class="example-link">Open example in new window</a>
</div><!--/.cf-->

<iframe {% if page.iframe_height %}class="h-{{ page.iframe_height }}"{% endif %} src="{{ site.baseurl}}/component/{{ page.path_slug }}/example.html"></iframe>

<h3>HTML <span class="link"><a href="component.html" target="_blank">View Generated HTML</a></span></h3>

{% include partials/html-tabs.md %}

<h3>SCSS <span class="link"><a href="scss/component.scss" target="_blank">Download SCSS</a></span></h3>

{% include partials/scss-component.md %}


<h3>Resources</h3>

{% include_relative _resources.md %}
