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
> If the Runner has both <a href="https://nrdb.reteki.fun/en/card/02069" target="_blank">Underworld Contact </a> installed and <a href="https://nrdb.reteki.fun/en/card/06056" target="_blank">The Supplier</a> installed hosting a <a href="https://nrdb.reteki.fun/en/card/02028" target="_blank">Dyson Mem Chip</a>, both <a href="https://nrdb.reteki.fun/en/card/02069" target="_blank">Underworld Contact </a> and <a href="https://nrdb.reteki.fun/en/card/06056" target="_blank">The Supplier</a> meet their trigger conditions at the same time. The Runner can trigger <a href="https://nrdb.reteki.fun/en/card/06056" target="_blank">The Supplier</a> first, so when <a href="https://nrdb.reteki.fun/en/card/02069" target="_blank">Underworld Contact </a> triggers its resolution will see that the Runner has 2 link and give them 1 credit.

