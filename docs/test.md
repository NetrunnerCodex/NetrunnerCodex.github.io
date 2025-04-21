---
parent: test
slug_title: Test
slug_title: Testing
slug_subtitle: 123
slug_image: "/assets/images/slugs/nrcx-slug.png"
layout: default
has_children: false
nav_order:
---
<div class="slug unified-background">
    <div class="slug-left">
        <h1 class="page-slug_title">{{ page.slug_title }}</h1>
        <p class="page-slug_subtitle">{{ page.slug_subtitle }}</p>
    </div>
    <div class="slug-right">
        <img src="{{ page.slug_image | relative_url }}" alt="{{ page.title }}" />
    </div>
</div>

<span class="text-grey-dk-000 fs-9 fw-700">TEST</span>

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/welcome" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/guide" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>
