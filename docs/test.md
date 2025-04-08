---
parent: test
title: Test
slug_title: 
subtitle: 
header_image: "/assets/images/slugs/nrcx-slug.png"
layout: default
has_children: false
nav_order:
---
<div class="slug shared-background" style="background-image: url('{{ page.slug_image | relative_url }}');">
    <div class="title-container">
        <h1 class="page-slug_title">{{ page.slug_title }}</h1>
        <p class="page-slug_subtitle">{{ page.slug_subtitle }}</p>
    </div>
    <div class="clr-image-container">
        <img src="{{ page.slug_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>

<span class="text-grey-dk-000 fs-9 fw-700">TEST</span>

