---
parent: Overview
title: Game Example
slug_title: Game Example
slug_subtitle:
slug_image: "/assets/images/slugs/adn49_preview5.jpg"
layout: default
has_children: false
nav_order: 18
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

<div style="text-align: center; margin-top: 0; padding-top: 0;">
    <img src="/assets/images/overview/example.jpg" alt="Image 1" style="margin: 10px;" />
</div>

<div class="nav-buttons">
  <a href="/docs/tutorial_setup" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/introduction" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>
