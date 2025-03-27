---
parent: Introduction
title: Playing the Game
slug_title: Playing the Game
slug_subtitle:
slug_image: "/assets/images/slugs/chp03-04_preview2.png"
layout: default
has_children: false
nav_order: 24
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

Android: Netrunner is played over a series of turns. The Corp always takes the first turn of the game.

The Corp and the Runner each resolve their turn using slightly different rules. However, both the Corp and the Runner must spend all of their clicks each turn.

The actions that the Corp and Runner can perform by spending clicks are described on page 8 for Corps and on page 12 for Runners. After player spends all of their clicks, their turn ends. Then, the next player begins their turn. Players alternate taking turns until
the game ends.

## Winning the Game
The primary way that a player wins a game is by gaining agenda points. The Runner wins if they can steal seven agenda points from the Corp, and the Corp wins if they can score seven agenda points. Each player can also win the game if their opponent is not careful. If the Corp must draw a card and they have no cards remaining in R&D, the Runner immediately wins the game. Additionally, the Corp
wins the game if the Runner suffers too much damage, which is described in Advanced Concepts.


<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/introduction/basic_concepts" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/introduction/corps_turn" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>
