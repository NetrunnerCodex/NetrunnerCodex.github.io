---
parent: test
title: Test
slug_title: 
subtitle: 
header_image: "/assets/images/slugs/adn01_preview.jpg"
layout: default
has_children: false
nav_order:
---
<div class="slug">
    <div class="title-container">
        <h1 class="page-title">{{ page.slug_title }}</h1>
        <p class="page-subtitle">{{ page.subtitle }}</p>
    </div>
    <div class="image-container faded-left">
        <img src="{{ page.header_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>


<span class="text-grey-dk-000 fs-9 fw-700">TEST</span>

