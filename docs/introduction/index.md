---
title: Introduction
slug_title: Introduction
slug_subtitle: Begin your journey into a world of strategy
slug_image: "/assets/images/slugs/adn11_preview.jpg"
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

# Basic Concepts

## Identity (ID)
Identity cards start the game in play and represent the specific Runner or Corp that a player is controlling. A player’s Identity card defines their faction and provides them with a special ability to use throughout the game.

{: .note-title }
> Note
>
> The Corp’s Identity card also represents their HQ for the purposes of card installation.

## Agendas
An Agenda is a type of Corp card that represents valuable pieces of data. Over the course of the game, the Runner must find and steal these Agendas, and the Corp must Advance and score them.

Each Agenda is worth a number of Agenda points. The first player to score or steal 7 Agenda points wins the game.

## Clicks and Credits
During a game, both the Corp and Runner will have to manage their resources, which are represented by Clicks and Credits.

A Click is the basic work resource in Android: Netrunner. Both the Corp and Runner have a finite number of Clicks to spend during each of their turns. Clicks are used to perform actions and resolve abilities. A Credit is the basic wealth resource that each player uses to play cards and pay for various abilities. Credits are represented by tokens in values of one or five Credits.

Most Runner cards and some Corp cards have a Credit cost that a player must pay to play the card. A card’s Credit cost is presented on the upper-left corner of the card and is encircled by a Credit icon.

When a player spends Credits, they return them to the Token Bank.

{: .note-title }
> Paid Abilities
>
> Some card abilities have costs that a player must pay before the effect of that ability can be resolved. These abilities are called **PAID ABILITIES**. An ability’s cost is always listed in **bold** before its effect, using the format “**cost**: effect."

## Tracking Clicks
Both the Corporation and Runner track the Clicks they spend during their turns by using a Click Tracker card. The Corporation’s Click Tracker contains three numbered spaces, and the Runner’s Click Tracker contains four numbered spaces. As the Corporation or Runner spends Clicks during a turn, they flip one of their click tokens facedown (blue and gold side up).

## Servers
For the Runner to win the game, they need to steal Agenda cards from the Corp player. These cards can be stolen from the Corp player’s hand (HQ), deck (R&D), or discard pile (Archives). Each of these locations are referred to as central servers. The Corp player may also play Agenda cards on the table in remote servers, described in detail: [The Corp's Actions](/docs/introduction/corps_turn/#the-corps-actions)

<div class="nav-buttons">
  <a href="/docs/example" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/introduction/playing" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>
