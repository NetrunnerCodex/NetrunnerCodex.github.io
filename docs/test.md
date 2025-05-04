---
parent: test
slug_title: Test
slug_title: Testing
slug_subtitle: testing
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


1. **Draw Phase**
<ol class="custom-ol" style="--start: 1.1;">
<li>The Corp gains allotted clicks, default: <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span></li>
<li>Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-ice cards <span class="nric-grey rez"></span> and score agendas <span class="nric-grey agenda "></span></li>
<li>The Corp’s recurring credits <span class="nric-grey re-credit"></span> refill.</li>
<li>The Corp’s turn begins.
</ol>
- The Corp’s “When your turn begins...” conditionals meet their trigger conditions.
<ol class="custom-ol" style="--start: 1.5;">
<li>The Corp draws 1 card from the top of R&D into HQ.</li>
</ol>
- This does not spend <span class="nric-grey click"></span>
- The Runner wins if R&D contains no cards during this step.

<ol class="custom-ol" style="--start: 2;">
<li><b>Action Phase</b></li>
</ol>
<ol class="custom-ol" style="--start: 2.1;">
<li>Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-ice cards <span class="nric-grey rez"></span> and score agendas <span class="nric-grey agenda "></span></li>
</ol>
