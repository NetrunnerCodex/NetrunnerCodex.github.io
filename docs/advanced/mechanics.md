---
parent: Advanced Concepts
title: Mechanics
slug_title: Mechanics
slug_subtitle: Ever-shifting tactics
slug_image: "/assets/images/slugs/adn49_preview7.jpg"
layout: default
has_children: false
nav_order: 37
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

## Derez

Some Runner abilities force the Corp to derez a card. To derez a card, the Corp flips it back to its unrezzed state.

## Hosting

Some cards can only be installed on other cards, and some cards allows other cards to be installed on them. A card that has one or more cards installed on it is a host card. A card that is installed on another card is a hosted card. These terms also refer to a card that has one or more counters on it - the card is a host and the counters are hosted. Hosted cards and counters can be removed from the play area without affecting their host. However, if a host is removed from the play area, all of that host’s hosted cards and counters are also removed from play.

Some abilities require a player to spend a hosted counter. To trigger such an ability, the counters must be spent from the card on which the ability appears. When a hosted counter is spent, it is placed in the token bank.

### Virus Counters

A virus counter is a specific type of hosted counter. The generic tokens can be used to represent virus counters. During their turn, the Corp can spend three clicks to remove all hosted virus counters from the play area.

## Exposing Cards

Some effects force the Corp to expose one or more cards. When a card is exposed, it is flipped faceup so the Runner can examine it. After the Runner has examined the card, it is placed facedown in the same state and location it was in prior to being exposed. If multiple cards are exposed by the the same effect, those cards are exposed simultaneously. The Runner cannot examine a facedown card that they exposed during a previous action without using another expose effect.

<div class="nav-buttons">
  <a href="/docs/advanced/interactions" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/advanced/additional" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>
