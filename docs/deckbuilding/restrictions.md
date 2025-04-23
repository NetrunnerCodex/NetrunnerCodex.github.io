---
parent: Deckbuilding
title: Restrictions
slug_title: Restrictions
slug_subtitle: Balancing gameplay
slug_image: "/assets/images/slugs/adn31_preview.jpg"
layout: default
has_children: false
nav_order: 42
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

When building a deck, players must observe the following restrictions:

- A deck must be associated with a single identity card, and cannot contain fewer cards than the minimum deck size value listed on the chosen identity card. There is no maximum deck size, but the deck must be able to be sufficiently randomized in a short period of time. Identity cards, reference
cards, and click tracker cards are never counted as part of a deck and do not count against the minimum deck size.
- A deck cannot have more than three copies of a single card (by title) in it.
- A deck associated with a Runner identity can never contain Corporation cards, and vice versa.
- A Corporation deck must have a specific number of agenda points in it based on the size of the deck, as follows:

{: .highlight }
> - 40 to 44 cards requires 18 or 19 agenda points. (Note: Identities in this set all have a 45 card minimum).
> - 45 to 49 cards requires 20 or 21 agenda points.
> - 50 to 54 cards requires 22 or 23 agenda points.

- For decks larger than this, add 2 additional agenda points to the 54 card deck requirements each time the number of cards in the deck reaches a multiple
of 5 (55, 60, 65, etc.).

{: .note-title }
> Example
>
> A 66 card deck requires 6 additional agenda points (2 at 55, 2 at 60, and 2 at 65 cards). This gives a final requirement of either 28 or 29 agenda points.

- A deck cannot contain out-of-faction cards with a total influence value that exceeds the influence limit listed on the chosen identity card, see: [Influence](/docs/deckbuilding/influence). Cards that match the faction of the identity card do not count against this limit.

<div class="nav-buttons">
  <a href="/docs/deckbuilding" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/deckbuilding/influence" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>
