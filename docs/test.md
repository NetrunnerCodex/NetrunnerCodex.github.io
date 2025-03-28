---
parent: test
title: Test
slug_title: Testing
subtitle: A Journey Through Modern Design
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

Font size 10
{: .fs-10 } {: .green-200 }

Font size 10 {: .fs-10 } {: .green-200 }
