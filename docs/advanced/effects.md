---
parent: Advanced Concepts
title: Effects
slug_title: Effects
slug_subtitle:
slug_image: "/assets/images/slugs/adn51_preview2.jpg"
layout: default
has_children: false
nav_order: 31
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

# Upgrades

An upgrade is a card that represents an improvement to a server. The Corp can spend one click to install an upgrade using the “Install One Card” action. The Corp can install an upgrade in either a central server or remote server. A single server can have any number of upgrades installed in it. 

When the Corp installs an upgrade in a central server, they place the upgrade in the server’s root. A root is a dedicated space below a central server that distinguishes the upgrade from R&D, Archives, or HQ (identity card) of that central server.

When the Corp installs an upgrade in a remote server, they place that upgrade in the same location as they would place an agenda or asset—a remote server does not have a root. Upgrades can coexist in a remote server with either an agenda or asset.

If multiple cards exist in the same remote server, the Corp can arrange those cards vertically in such a way that they do not appear to be distinct remote servers. From the Runner’s perspective, an installed upgrade is indistinguishable from an agenda or asset until rezzed. However, if there is more than one card installed in a remote server, then the Runner knows that at least one of them must be an upgrade.

# Damage

Game effects can cause the Runner to suffer damage. When a Runner suffers any amount of damage, they randomly trash a number of cards from their grip equal to that amount. If the Runner cannot trash a card because they have no cards remaining in their grip, they are flatlined and the Corp wins the game. There are three types of damage: net, meat, and
brain. The Runner resolves damage identically for each of these types of damage. The only difference between the damage types is the cards that may cause or prevent them.

Additionally, brain damage causes a permanent decrease to the Runner’s maximum hand size equal to the amount of brain damage they have taken. To keep track of this, the Runner places a brain damage token in their play area for each brain damage they have taken. The Runner’s maximum hand size is reduced by the number of brain damage tokens they have.

# Bad Publicity

Some game effects give the Corp bad publicity. When the Corp receives bad publicity, they place a bad publicity token in their play area.

Each time the Runner makes a run, they gain one credit for each bad publicity token the Corp has. The Runner can only spend these credits during that run. At the end of the run, the Runner must return any unspent credits earned through bad
publicity to the token bank.

<div class="nav-buttons">
  <!-- Previous Button -->
  <a href="/docs/advanced/index" class="nav-button" aria-label="Previous page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M30 20L20 30L30 40" />
      </svg>
    </div>
  </a>

  <!-- Next Button -->
  <a href="/docs/advanced/resources" class="nav-button" aria-label="Next page">
    <div class="nav-item">
      <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" viewBox="0 0 50 50">
        <path d="M20 20L30 30L20 40" />
      </svg>
    </div>
  </a>
</div>