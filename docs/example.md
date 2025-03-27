---
parent: Overview
title: Game Example
slug_title: Game in Progress Example
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
  <!-- Previous Button -->
  <a href="/docs/tutorial_setup" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/introduction/basic_concepts" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>
