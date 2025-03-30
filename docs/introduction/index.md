---
title: Introduction
slug_title: Introduction
slug_subtitle:
slug_image: "/assets/images/slugs/nrcx-slug.jpg"
layout: home
has_children: true
nav_order: 20
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

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/example" class="nav-button" aria-label="Previous page">
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
