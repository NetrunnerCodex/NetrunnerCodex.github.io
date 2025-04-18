---
parent: Introduction
title: The Corp’s Turn
slug_title: The Corp’s Turn
slug_subtitle:
slug_image: "/assets/images/slugs/adn49_preview13.jpg"
layout: default
has_children: false
nav_order: 26
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

## Nodes
{: .no_toc .text-delta }
1. TOC
{:toc}

{: .note-title }
> Corp Terms
>
> The Corp’s deck is called R&D (research and development), the Corp’s hand is called HQ (headquarters), and the Corp’s discard
pile is called Archives. Cards in Android: Netrunner will specifically use these terms when referring to the Corp’s deck, hand, and
discard pile, as appropriate.

During the Corp’s turn, the Corp resolves the following three phases in order: Draw Phase, Action Phase, and Discard Phase.

## Draw Phase
During the Draw Phase, the Corp draws a card from R&D (their deck) and places it in HQ (their hand). After drawing a card, the Corp proceeds to the Action Phase of this turn.

## Action Phase
During the Action Phase, the Corp has 3 clicks to spend on performing actions and resolving abilities on cards. The Corp can perform the same action or resolve the same ability multiple times during the same turn provided they have enough clicks to spend. The
actions that the Corp can perform during the Action Phase are described in detail in The Corp's Actions. When the Corp has no remaining clicks to spend, they proceed to the Discard Phase of this turn.

## Discard Phase
During the Discard Phase, the Corp must choose and discard cards from HQ down to their maximum hand size. The Corp’s maximum hand size is five unless modified by other effects. When the Corp discards a card from HQ, they place the card facedown in Archives and orient it
sideways. However, if the card was in play faceup when discarded, it is placed faceup into Archives. The facedown cards are oriented sideways so players can see how many facedown cards are in Archives—this information may be useful to the Runner later. After the Corp has discarded down to their maximum hand size, if necessary, the Runner begins their turn.

{: .note-title }
> Corporation Action Overview
>
> <span class="nric click"></span> Draw One Card<br>
> <span class="nric click"></span> Gain One Credit<br>
> <span class="nric click"></span> Play One Operation<br>
> <span class="nric click"></span> Install One Card<br>
> <span class="nric click"></span><span class="blue-font"> **1**</span><span class="nic credit"></span>Advance One Card<br>
> <span class="nric click"></span><span class="blue-font"> **2**</span><span class="nic credit"></span>Trash One Resource if the Runner is Tagged<br>
> <span class="nric click"></span><span class="nic click"></span><span class="nic click"></span> Purge All Virus Counters

<hr>

# The Corp’s Actions

During the Action Phase, the Corp spends clicks to perform the actions described in this section.

## Draw One Card
The Corp can spend one click to draw one card from R&D. They take the top card from R&D and place it in HQ.

## Gain One Credit
The Corp can spend one click to gain one credit <span class="blue-font"> **1**</span><span class="nic credit"></span>. They take one credit from the token bank and place it in their credit pool.

## Play One Operation
The Corp can spend one click to play one operation card from HQ. Operations represent various transactions, interactions, and corporate initiatives that provide the Corp with a variety of one-time effects.

To play an operation, the Corp must pay the card’s credit cost in addition to spending a click. Then, they read and resolve the effect described on the card. After resolving an operation’s effect,the Corp places the operation faceup in Archives.

## Corp Card Types
- Agenda
- Asset
- Ice

## Corp’s HQ and Remote Servers with Ice

<div style="text-align: center; margin-top: 0; padding-top: 0;">
    <img src="/assets/images/introduction/corps_turn/servers.jpg" alt="Image" style="margin: 10px;" />
</div>

## Install One Card
The Corp can spend one click to install an agenda, asset, or ice card. Unlike operations which are resolved immediately and placed in Archives, installed cards remain in play and typically provide the Corp with a variety of persistent effects. To install a card, the Corp places it facedown. Where it is placed depends on the card’s type, as follows:

### Installing Assets and Agendas (Remote Servers)
A remote server is a location where the Corp can install assets, agendas, and/or ice. When the Corp installs an agenda or asset, they place it facedown in their play area, creating a new remote server (or in a remote server that already exists). Each remote server can contain either one agenda or one asset. The Corp may have any number of remote servers.

The Corp must trash any installed assets or agendas in the server where they are installing a new asset or agenda. To trash a card, the Corp places the card in Archives—either faceup or facedown—as it existed in the play area.

### Installing Ice
Ice defends the Corp’s servers against intrusions by the Runner.

When the Corp installs ice, they must place it above a central or remote server of their choice. The ice protects the chosen server and is placed horizontally to distinguish it from other cards. A server can be protected by multiple ice cards. When installing ice
above a server that already has ice above it, the Corp must pay one credit for each ice that was already protecting that server. Then, they must place the ice they are installing in the outermost position above that server.

The Corp can install ice above a server that does not have any cards in it, creating a new remote server where they can install an asset or agenda during a subsequent action.

The Corp may trash any installed pieces of ice abovethe server where they are installing a new piece of ice. If the Corp trashes a piece of ice, it is placed in Archives in the same state—either faceup or facedown—as it existed in the play area.

The Corp’s identity card functions as the play-area representation of HQ. As such, if the Corp wishes to install ice that protects HQ, they place that ice above their identity card.

## Advance One Card
The Corp can spend one click and one credit to advance one of their installed cards. Agendas can always be advanced. Any other card can only be advanced if it is specifically stated on the card. To advance a card, the Corp places an advancement token on the card they wish to advance.

If there are ever a number of advancement tokens on an agenda equal to its advancement requirement, the Corp may score that agenda during their turn by revealing it and placing it faceup in their score area.

## Trash One Resource
This action is not used during the tutorial. It is described in the “Advanced Rules” section.

## Purge All Virus Counters
This action is not used during the tutorial. It is described in the “Advanced Rules” section.

<HR>

# Rezzing Cards

The Corp’s installed cards have two play states: **REZZED**, which means that the card is faceup and active, and **UNREZZED**, which means that the card is facedown and inactive. Each asset, ice, and upgrade (see “Upgrades”) card has a rez cost. To **REZ** a card, the Corp must pay its rez cost and turn that card faceup. Agendas do not have a rez cost and cannot be rezzed.

After a card is rezzed, it remains rezzed for the duration of the game unless an effect states otherwise. The Corp can rez asset and upgrade cards at any time without spending a click. The Corp can only rez ice during a run, which is described later (see “Making
Runs”).

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/introduction/playing" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/introduction/runners_turn" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>
