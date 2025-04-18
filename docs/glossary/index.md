---
title: Glossary
slug_title: Glossary
slug_subtitle:
slug_image: "/assets/images/slugs/adn32_preview.jpg"
layout: home
has_children: true
nav_order: 90
---
<div class="slug">
    <div class="title-container">
        <h1 class="page-slug_title">{{ page.slug_title }}</h1>
        <p class="page-slug_subtitle">{{ page.slug_subtitle }}</p>
    </div>
    <div class="image-container faded-left">
        <img src="{{ page.slug_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>

{: .no_toc }
