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

{: .note-title }
> Example
>
> If the Runner has both {% include card.html id="02069" nm="Underworld Contact" %} installed and {% include card.html id="06056" nm="The Supplier" %} installed hosting a {% include card.html id="02028" nm="Dyson Mem Chip" %}, both {% include card.html id="02069" nm="Underworld Contact" %} and {% include card.html id="06056" nm="The Supplier" %} meet their trigger conditions at the same time. The Runner can trigger {% include card.html id="06056" nm="The Supplier" %} first, so when {% include card.html id="02069" nm="Underworld Contact" %} triggers its resolution will see that the Runner has <span class="grey-font-b">2</span> <span class="nric-grey link"></span><span class="grey-font-b">LINK</span> and give them <span class="grey-font-b">1</span><span class="nric-grey credit"></span><span class="grey-font-b">CREDIT</span>

<span class="nric-grey flatline"></span>

<span class="nric-grey ice"></span>
