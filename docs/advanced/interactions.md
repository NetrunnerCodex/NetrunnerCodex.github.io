---
parent: Advanced Concepts
title: Interactions
slug_title: Interactions
slug_subtitle:
slug_image: "/assets/images/slugs/silhouette-plans-her-run.jpg"
layout: default
has_children: false
nav_order: 35
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

# Tags

Some game effects give the Runner a tag. When the Runner receives a tag, they place a tag token in their play area.

A Runner can have multiple tags. While a Runner has one or more tags, they are tagged. While the Runner is tagged, the Corp can spend one click and two credits during their turn to trash one of the Runner’s resources. Tags have no other inherent effects, but some card abilities may effect a Runner who is tagged. As an action, a Runner can spend one click and two credits during their turn to remove one tag (see Addtional Actions).

# Traces and Link

Some Corp abilities cause the players to resolve a trace. A trace compares the Corp’s trace strength to the Runner’s link strength. 

A trace is denoted on cards by the word “Trace” followed by a number; that number is the base trace strength.

The Runner’s base link strength is equal to the link <span class="nric-grey link"></span> they have in play. Links can be gained from a Runner’s identity card or from other installed cards.

To resolve a trace, players follow these steps:

1. Increase Trace Strength: The Corp can spend any number of their credits to increase the trace strength from its base value by one for each credit spent, or they can pass if they do not want to spend any credits.
1. Increase Link Strength: The Runner can spend any number of their credits to increase their link strength from its base value by one for each credit spent, or they can pass if they do not want to spend any credits.
1. Compare Strengths: The players compare the Corp’s trace strength to the Runner’s link strength. If the trace strength exceeds the link strength, the trace is successful. If the link strength is equal to or greater than the trace strength, the trace is unsuccessful.
1. Resolve Trace Effects: Each trace ability has one or more effects that are triggered based on the outcome of the trace. If a trace is successful, any “If successful” effects associated with that traceare resolved. If the trace is unsuccessful, any “If unsuccessful” effects associated with that trace are resolved.

# Hidden Information

Android: Netrunner is a game of information and bluffing. A player can always look at the cards they have installed as well as any cards in their hand or discard pile. Any faceup cards, including those found in either the Runner’s heap or Corp’s Archives, are open information and can be viewed by both players at any time. The number of cards in a player’s hand or deck as well as the amount of credits in a player’s credit pool is also open information. All other information must be acquired through effects while playing the game.

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/advanced/resources" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/advanced/mechanics" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>