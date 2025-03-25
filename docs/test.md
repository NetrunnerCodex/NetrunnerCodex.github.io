---
parent: test
title: Test
subtitle: "A Journey Through Modern Design"
header_image: "/assets/images/slugs/adn-magnum-opus-preview3.jpg"
layout: default
has_children: false
nav_order:
---
<div class="slug">
    <div class="title-container">
        <h1 class="page-title">{{ page.title }}</h1>
        <p class="page-subtitle">{{ page.subtitle }}</p>
    </div>
    <div class="image-container">
        <img src="{{ page.header_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>
