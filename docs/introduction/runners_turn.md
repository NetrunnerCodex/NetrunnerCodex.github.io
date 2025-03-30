---
parent: Introduction
title: The Runner’s Turn
slug_title: The Runner’s Turn
slug_subtitle:
slug_image: "/assets/images/slugs/adn34_preview2.jpg"
layout: default
has_children: false
nav_order: 28
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

{: .notered-title }
> Runner Terms
>
> The Runner’s deck is called the stack, the Runner’s hand is called the grip, and the Runner’s discard pile is called the heap.
Many cards in Android: Netrunner will specifically use these terms when referring to the Runner’s deck, hand, and discard pile, as
appropriate.

During the Runner’s turn, they resolve the following two phases in order: Action Phase, and Discard Phase. Unlike the Corp, the Runner does not perform a Draw Phase.

## Action Phase
During the Action Phase, the Runner has 4 clicks <span class="nic-red click"></span>to spend on performing actions and resolving abilities on cards. The actions that the Runner can perform during the Action Phase are described in detail in the next column.

When the Runner has no remaining clicks to spend, they proceed to the Discard Phase of their turn.

## Discard Phase
During the Discard Phase, the Runner must choose and discard cards from their grip down to their maximum hand size. The Runner’s maximum hand size is five unless modified by other effects.

After the Runner has discarded down to their maximum hand size, if necessary, the Corp begins their turn.

<HR>

# The Runner’s Actions

During their action phase, the Runner can spend clicks to perform the actions described in this section. The Runner can perform the same action multiple times per turn provided they have enough clicks to spend for each action.

## Draw One Card
The Runner can spend one click to draw one card from their stack. They take the top card from their stack and place it in their grip.

## Gain One Credit
The Runner can spend one click to gain one credit. They take one credit from the token bank and place it in their credit pool.

## Play One Event
The Runner can spend one click to play an event card from their grip. Events represent various jobs, transactions, and behaviors that provide the Runner with a variety of one-time effects.

To play an event card, the Runner must pay the card’s credit cost in addition to spending a click. Then, they read and resolve the effect described on the card. After resolving an event’s effect, the Runner places it in the heap.

{: .notered-title }
> Runner Action Overview
>
> <span class="nic-red click"></span>Draw One Card<br>
> <span class="nic-red click"></span>Gain One Credit<br>
> <span class="nic-red click"></span>Play One Event<br>
> <span class="nic-red click"></span>Install One Card<br>
> <span class="nic-red click"></span><span class="red-font"> **2**</span><span class="nic-red credit"></span>Remove One Tag<br>
> <span class="nic-red click"></span>Make One Run

## Install One Card
The Runner can spend one click to install a program, resource, or hardware card. Each of these cards contains a credit cost that the Runner must pay in addition to spending a click. Unlike an event that is resolved immediately and placed in the heap, installed
cards remain in play and typically provide the Runner with a variety of persistent effects. To install a card, the Runner places it faceup in their play area.

## Runner Card Types
- Program
- Hardware
- Resource

## Remove One Tag
This action is not used during the tutorial. It is described in the “Advanced Rules” section.

## Make One Run
To make a run, the Runner spends one click and chooses a server to run against. Runs are the heart of Android: Netrunner. Making a run is the main way the Runner can steal agendas needed to win the game. Runs are described in detail next.

<HR>

# Making Runs

When the Runner makes a run against a server, they must pass all of the ice protecting that server in order, starting at the outermost piece of ice. If a piece of ice is rezzed, the Runner must **ENCOUNTER** it (see Encountering Ice) before passing it. The Corp has an opportunity to rez each piece of ice as the Runner **APPROACHES** it. Once rezzed, ice remains rezzed for all future runs.

After a piece of ice is passed, the Runner approaches the next piece of ice and repeats this process until all ice is passed. Once all ice protecting a server is passed, the Runner chooses to either **JACK OUT** (see Jacking Out), or access the server (see Successful Runs). Accessing the server results in a **SUCCESSFUL** run.

## Encountering Ice
Each piece of ice contains one or more **SUBROUTINES**. A subroutine is an effect that, if triggered, either negatively impacts the Runner or benefits the Corp.

When the Runner encounters a piece of ice, they have an opportunity to **BREAK** any subroutines on that card. Then, any subroutines that they did not break are triggered in order, from top to bottom. Rules for breaking subroutines are described below.

To trigger a subroutine, the Corp reads and resolves its effects. Some subroutines contain the phrase, “End the run.” When such a subroutine triggers, the run ends immediately. After all unbroken subroutines trigger, if the run has not ended, the Runner passes the ice and the run continues.

## Breaking Subroutines
The Runner can use icebreaker program cards to break subroutines on ice they are encountering.

To break a subroutine, an icebreaker must be able to **INTERACT** with that subroutine’s ice. Ice and icebreakers each have a strength value. If the icebreaker’s strength is equal to or greater than the ice’s strength, that icebreaker can interact with that ice. Most icebreakers have an ability that allows the Runner to increase that icebreaker’s strength by spending credits. The Runner can use these abilities as many times as they can pay for them.

If an icebreaker is able to interact with a piece of ice, the Runner can use the icebreaker to break subroutines as described on that icebreaker. There are three primary subtypes of ice: barrier, sentry, and code gate. Many icebreakers can only break specific
subtypes of ice. For example, an icebreaker that has the ability "<span class="red-font">**0**</span><span class="nic-red credit"></span>Break sentry subroutine” can only be used to break a subroutine on ice with a sentry subtype.

The Runner can choose and break any number of subroutines on a piece of ice, and the Runner can use any number of icebreakers to do so, though in most cases, they will likely only want to use a single icebreaker.

After an encounter with a piece of ice ends, the strength of each icebreaker resets to the value printed on the card. The Runner can increase that icebreaker’s strength again during the same run if they need to.

## Successful Runs
After the Runner has passed all pieces of ice protecting a server, they may choose to continue the run and **ACCESS** cards from the server. This is a successful run.

## Accessing
The card, or cards, accessed from a successful run depends on the server that was attacked.

## R&D
The Runner accesses the top card of R&D. When accessing multiple cards from R&D, those cards are returned in their original order after all of the cards have been accessed.

## HQ
The Runner accesses one random card from HQ. When accessing multiple cards from HQ, the Runner does not return any of them to HQ until all of the cards have been accessed.

## Archives
The Runner flips all cards in theArchives faceup. Then, the Runner accesses all cards in the Archives in the order of their choosing.

## Remote Server
The Runner accesses all asset, agenda, and/or upgrade cards in the remote server.

## Stealing and Trashing
If the Runner accesses an agenda, they immediately steal it. When the Runner steals an agenda, they set it aside, faceup, in their score area. The Runner wins the game if they have seven or more agenda points in their score area.

If the Runner accesses any other type of card, they look at that card. Then, if the card has a trash cost printed in the lower-right corner, the Runner has the option to spend a number of credits equal to the trash cost to trash that card, placing it faceup in
Archives.

If the Runner chooses not to pay the trash cost, or if that card does not have a trash cost, return it to where it was before it was accessed.

## Jacking Out
The Runner has several opportunities to **JACK OUT**, which ends the run. They may wish to do this in order to avoid taking more damage or if they fear the Corp has laid a trap for them. The Runner can jack out during a run at the following times:
- After each encounter with a piece of ice, before encountering the next ice (before the Corp chooses to rez it).
- Before accessing cards in a server.

If at any time the Runner jacks out, even after having passed all ice, the run is considered unsuccessful.

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/introduction/corps_turn" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/introduction/run_example" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>
