---
title: Glossary
toc: false
toc_levels: 1..1
slug_title: Glossary
slug_subtitle: Core mechanics and terminolgy
slug_image: "/assets/images/slugs/adn32_preview.jpg"
layout: home
has_children: true
nav_order: 90
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

{:.custom-toc}
1. TOC
{:toc}

The following is an alphabetical list of entries for game rules, terms, and situations that may occur during play.

# Abilities
## Triggered Abilities

In order to use a triggered ability a prerequisite must be met. This prerequisite is either a trigger cost that must be paid (paid ability) or a trigger condition that must be met (conditional ability). Once an ability is triggered, its effect is resolved and can only be stopped by prevent or avoid effects, even if another ability is already in the process of resolving. Players must follow all restrictions on the cards when triggering abilities.

### Paid Abilities

In order to trigger a paid ability, a trigger cost must be paid. The most common trigger costs are spending clicks, credits, or hosted counters, and trashing cards. Some effects feature a combination of costs.

A card’s trigger cost is always listed in its text box before the effect, following the format “cost: effect.” A paid ability can be triggered an unlimited number of times as long as the cost is paid and any restrictions specified by the effect are observed. Paid abilities can be triggered at a variety of timing structures over the course of the game, including at the beginning and end of each turn, before and after each action, and during runs. If an ability requires any number of clicks as part of its cost, it can only be triggered as an action during a player’s action phase and not during the resolution of another click action. See the timing structures at the back of the Rules Reference for a full list of opportunities to use paid abilities.

### Conditional Abilities

In order for a conditional ability to trigger, a trigger condition must be met while the card with the ability is active. A conditional ability can only be resolved once per trigger condition. The trigger condition for a conditional ability is defined in its text by a preceding clause with one of the words when, whenever, before, or after. Some conditional abilities use ordinal events as trigger conditions (e.g. “The first time each turn…”). Multiple abilities can meet their trigger conditions at the same time. 

If a conditional ability uses a permissive word like “may” or “allows”, it is an optional conditional ability. The decision to trigger the ability belongs to the player who owns the card, provided the ability’s trigger condition is met. If a conditional ability does not contain any permissive words, it is a required conditional ability. It must be triggered when its trigger condition is met, although the exact timing of resolution may vary. Conditional abilities that can only be used “once per turn” are also optional, and the choice of when to trigger these abilities is up to the owner of the card. 

Ice subroutines are required conditional abilities that can be broken, in which case they do not resolve.

### “If… when” vs “When...if”

Some conditional abilities stipulate additional requirements for their usage.

If a requirement is part of the ability’s trigger condition, then the ability only meets its trigger condition if that requirement is met at the moment that the trigger condition would occur.

{: .note-title }
> Example
>
>  Quantum Predictive Model can only meet its trigger condition if the Runner is tagged at the time the access occurs. Even if Casting Call is hosted on Quantum Predictive Model, the tag will be given after the access occurs, and no ordering of the abilities will result in Quantum Predictive Model triggering.

If a requirement is part of the ability’s effect, then that requirement only needs to be met when the conditional ability resolves, even if that requirement is not met at the time the ability meets its trigger condition.

{: .note-title }
> Example
>
> If the Runner has both Underworld Contact installed and The Supplier installed hosting a Dyson Mem Chip, both Underworld Contact and The Supplier meet their trigger conditions at the same time. The Runner can trigger The Supplier first, so when Underworld Contact triggers its resolution will see that the Runner has <span class="grey-font-b">2</span> <span class="nric-grey link"></span><span class="grey-font-b">LINK</span> and give them <span class="grey-font-b">1</span><span class="nric-grey credit"></span><span class="grey-font-b">CREDIT</span>

### Trigger Steps

Triggered abilities follow three steps for taking effect:

**Trigger Met**: The trigger condition of a conditional ability has occurred or the trigger cost of a paid ability has been paid, and the ability is ready to trigger. If a paid ability or an optional conditional ability enters the “trigger met” state, the ability is considered to have been “used”. Note that multiple conditional abilities can have their trigger met at the same time. Whenever one or more abilities are in this state, a player must trigger one of them. If the active player controls any of the abilities, that player chooses one of their abilities to trigger; if not, the inactive player chooses one of the abilities they control to trigger. After that ability is triggered and resolved, another ability in the “trigger met” state (if any) should be triggered in the same way.

**Trigger**: The ability is ready to resolve and becomes independent of its source card. An ability that has triggered must resolve and can continue to affect the game, even if the source card becomes inactive. Once an ability is triggered, players can use prevent/avoid effects to modify what they would do, but no other actions can be taken. Once no more prevent/avoid effects are being applied, the ability resolves.

**Resolve**: The ability’s instructions are carried out and affect the game state.

If a card becomes inactive after its trigger is met but before it triggers, then the ability fails to trigger and resolve. This can occur in situations involving simultaneous effects or chain reactions.

{: .note-title }
> Example
>
> The Runner has both Aesop’s Pawnshop and Drug Dealer installed. Both cards meet their trigger conditions when the Runner’s turn begins. If the Runner chooses to trigger Aesop’s Pawnshop first, and then uses it to trash Drug Dealer, Drug Dealer ability never reaches the point where it triggers, so the Runner does not lose a credit.

If the trigger condition of a conditional ability is met by a specific timing structure of the game (for example, “When your turn begins...”) and that timing structure becomes invalid between the trigger condition being met and the ability triggering, then the triggered ability never triggers and does not resolve. A timing structure becomes invalidated by that structure ending prematurely, usually due to simultaneous effects or chain reactions.

{: .note-title }
> Example
>
> The Runner encounters a Tollbooth that they can bypass with Femme Fatale. Both cards have the same trigger condition, but because it is the Runner’s turn the Femme Fatale triggers first. The ice is bypassed, and because the encounter timing structure has ended and the pass timing structure has begun, the trigger condition for Tollbooth is no longer valid. The ability to force the Runner to pay credits or end the run does not trigger or resolve.

## Constant Abilities

Any ability that is not a triggered ability (does not specify a trigger cost or a trigger condition as described above) is a constant ability. Constant abilities continually affect the game as long as the card they appear on is active. Some constant abilities stipulate additional requirements with one of the words “if”, “while”, or “until”. Such constant abilities only affect the game as long as those requirements are met.

## Using Abilities

Any time an ability is optional, regardless of whether it is a triggered ability or a constant ability, then the player is considered to be “using” that ability and the card it is on if they choose to resolve it. A player can only use an ability if its effect has the potential to change the game state. This potential is assessed without taking into account the consequences of paying any costs or triggering any other abilities.

{: .note-title }
> Example
>
> The Corp has one unrezzed piece of ice installed and Liquidation in HQ. As Liquidation requires the Corp to have at least one rezzed card to trash, the Corp cannot play Liquidation as it cannot change the game state.

{: .note-title }
> Example
>
> The Corp has one rezzed piece of ice installed and Liquidation in HQ. Because the Corp has at least one rezzed card that could be trashed (which would change the game state), they play Liquidation, spending a click and paying its play cost. The Corp then chooses any number - including zero - of their rezzed cards to trash.

{: .note-title }
> Example
>
> The Runner is playing Armand “Geist” Walker" and has Forger installed. As the Runner has no tags and is not currently in the process of taking a tag, the Runner cannot trash Forger to trigger Armand “Geist” Walker ability.

{: .note-title }
> Example
>
> The Runner is playing Ele “Smoke” Scovak. They have Switchblade and Net Mercurinstalled. Though the Runner is not currently running, they may use Ele “Smoke” Scovak ability to boost Switchblade strength, as a boost in strength is a change in the game state.

**Related**: Action, Active, All, Avoid, Chain Reactions, Cost, Inactive, Ordinal Events, Paid Ability Window, Prevent, Run, Simultaneous Effects, Subroutines, Timing Structures.

# Accessing

Accessing is the act of the Runner looking at and interacting with the Corp’s cards. Accessing usually occurs during a successful run.

## Accessing Multiple Cards in a Server

When the Runner chooses to access cards in a server, they will access a set number of cards. Upon choosing to access, that number is determined by the total number of cards a successful run on that server would normally access, any active modifiers that may be adding to or reducing the number, plus all cards in a central server’s root.

During access to a central server, if cards are added to the server in the middle of access, the number of cards to be accessed does not change, even if the total number of potential cards to be accessed was greater than the actual number of cards.

If the number of cards available to access is reduced during access, the Runner’s total number of cards to be accessed remains the same, but once the total number of accesses is set the Runner will attempt to access that number.

{: .note-title }
> Example
>
> The Runner playing Leela Patel makes a successful run on HQ, and the access number is set at 3. Disposable HQ is accessed with the first access, placing all the cards in HQ but an agenda to the bottom of R&D. Leela accesses the agenda and bounces a card in play. Leela would still be able to access the bounced card, since the total number of set access was 3.

When the Runner accesses multiple cards from HQ, the cards are accessed one at a time, and do not return to HQ until the Runner is finished accessing.

When the Runner accesses multiple cards from R&D, the Runner must access the cards in the order that they appear in the server (often starting with the topmost card of R&D). If the order of R&D is changed during an access, the Runner continues accessing cards from R&D as normal, starting with whatever card is now on top of R&D, and proceeding down through as many cards as they have accesses remaining.

{: .note-title }
> Example
>
> The Runner makes a run on R&D using The Maker’s Eye. The second card that the Runner accesses is Bacterial Programming. They steal it, allowing the Corp to rearrange, draw, and trash the top 7 cards of R&D (including the first card that the Runner accessed). Once the Corp has finished this process, the Runner then accesses one final card, starting with the topmost card of R&D.

When the Runner accesses cards in Archives, the Runner turns all cards faceup in Archives, then accesses and resolves each card in Archives one by one in the order of their choosing.

The Runner can intersperse accessing cards from a central server with any upgrades installed in the root of the server.

{: .note-title }
> Example
>
> The Runner plays The Maker’s Eye and makes a successful run on R&D. They access the top card of R&D, and afterward choose and access an upgrade installed in the root of R&D. The Runner then finishes accessing cards by accessing two more cards from R&D.

When the Runner accesses cards in a remote server, the Runner accesses and resolves each card in that server in the order of their choosing.

## “When Accessed” Abilities

A card with an ability that triggers when the card is accessed does not have to be active in order for the ability to trigger. When resolving such an ability, simply follow the instructions on the card.

{: .note-title }
> Example
>
> The Corporation does not have to rez Project Junebug before the Runner accesses it in order to use its ability.

**Related**: Abilities, Archives, Facedown, Faceup, Headquarters (HQ), Replacement Effect, Research and Development (R&D), Root, Run, Server

# Action

An action is any paid ability that requires a player to spend at least one <span class="nric-grey click"></span>, including the standard actions available to each player during their action phases. An action can only be used during an action phase.

While an action is resolving, no other <span class="nric-grey click"></span> can be spent and no other actions can be taken until the currently resolving action completes. A player can only take an action if its effect has the potential to change the game state. This potential is assessed without taking into account the consequences of paying any costs or triggering any abilities.

**Related**: Abilities, Action Phase, Costs Action Phase

The action phase is the timing structure in which a player can take actions by spending their clicks. A player may take actions in any combination and order as long as they pay the appropriate costs. A player must spend all of their available clicks during their action phase; once they have no remaining clicks, the action phase ends.

During a player’s action phase, they take actions by spending clicks. The action phase is the only time in which actions can be taken, and a player must spend all of their available clicks. Once an action is initiated, no other actions or abilities may be used or triggered, no cards may be rezzed, and no agendas may be scored, until the action is finished resolving or unless the action initiates a new timing structure (such as initiating a run).

A player can only take an action if its effect has the potential to change the game state. This potential is assessed without taking into account the consequences of paying any costs or triggering any abilities.

The Corp’s action phase follows these steps in order:

1. Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-ice cards <span class="nric-grey rez"></span> and score agendas <span class="nric-grey agenda"></span>.
1. The Corp takes actions until they have no <span class="nric-grey click"></span> remaining. After each action, players may use paid abilities <span class="nric-grey paid"></span>, the Corp may rez non-ice cards <span class="nric-grey rez"></span>, and the Corp may score agendas <span class="nric-grey agenda"></span>. Actions include:

<table class="sml-table">
  <tr>
    <td><span class="nric-grey click"></span></td>
    <td>Gain <b>1</b><span class="nric-grey credit"></span></td>
  </tr>
  <tr>
    <td><span class="nric-grey click"></span></td>
    <td>Draw 1 card from R&D.</td>
  </tr>
  <tr>
    <td><span class="nric-grey click"></span></td>
    <td>Install 1 agenda, asset, upgrade, or piece of ice.</td>
  </tr>
  <tr>
    <td><span class="nric-grey click"></span></td>
    <td>Play 1 operation.</td>
  </tr>
  <tr>
    <td><span class="nric-grey click"></span> <b>1</b><span class="nric-grey credit"></span></td>
    <td>Advance 1 installed card.</td>
  </tr>
  <tr>
    <td><span class="nric-grey click"></span> <b>2</b><span class="nric-grey credit"></span></td> 
    <td>Trash 1 resource if the Runner is tagged.</td>
  </tr>
  <tr>
    <td>
      <span class="nric-grey click"></span>
      <span class="nric-grey click"></span>
      <span class="nric-grey click"></span>
    </td> 
    <td>Purge virus counters.</td> 
  </tr>
 </table>

Trigger a <span class="nric-grey click"></span> ability on an active card (cost varies).

The Runner’s action phase follows these steps in order:


1. The Runner gains allotted clicks, default: <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span>
1. Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-
ice cards <span class="nric-grey rez"></span>
1. The Runner’s recurring credits <span class="nric-grey re-credit"></span> refill.
1. The Runner’s turn begins.
- The Runner’s “When your turn begins...” conditionals meet their trigger conditions.
<ol class="custom-ol" style="--start: 5;">
<li>
Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-
ice cards <span class="nric-grey rez"></span>
</li>
<li>
The Runner takes actions until they have no <span class="nric-grey click"></span> remaining. After each action, players may use paid abilities <span class="nric-grey paid"></span> and the Corp may rez non-ice cards <span class="nric-grey rez"></span>. Actions include:
</li>
</ol>
<span class="nric-grey click"></span> Gain <b>1</b><span class="nric-grey credit"></span><br>
<span class="nric-grey click"></span> Draw <b>1</b> card from the stack.<br>
<span class="nric-grey click"></span> Install <b>1</b> program, resource, or piece of hardware.<br>
<span class="nric-grey click"></span> Play <b>1</b> event.<br>
<span class="nric-grey click"></span> Make a run.<br>
<span class="nric-grey click"></span><b> 2</b><span class="nric-grey credit"></span> Remove 1 tag.

Trigger a <span class="nric-grey click"></span> ability on an active card (cost varies).

**Related**: Abilities, Action, Agendas, Corp, Credits - Recurring, Paid Ability Windows, Rez, Runner, Score, Timing Structures.

# Active

A state in which a card’s abilities are able to be used and affect the game. This generally only applies to cards installed and faceup in the play area, but also includes the identities of both players and agendas in the Corp’s score area.

Unless otherwise stated, Runner cards are played and installed active into the play area.

Unless otherwise stated, Corp cards are installed unrezzed, and thus inactive, into the play area and are made active by rezzing them. Operations are played active into the play area while they resolve.

**Related**: Agenda, Faceup, Identity, Install, Rez, Rezzed, Score Area, Unrezzed.

# “Additional”

The word “additional” denotes a modifier to an ability or a game state. The additional modifier is resolved simultaneously with any ability it is modifying and under the same conditions as that ability.

**Related**: Cost, Simultaneous Effects.

# Advancement Requirement

The **minimum** number of advancement tokens that must be on an agenda before the Corp can score it.

**Related**: Advancing Cards, Agenda, Corp, Score.

# Advancing Cards

Advancing is the action of spending <span class="nric-grey click"></span> and **1**<span class="nric-grey credit"></span> to put one advancement token on a card that can be advanced.

Agendas can always be advanced while installed. If a card other than an agenda says that the card can be advanced, the card can be advanced even when the card is unrezzed. There is no limit to the number of times a card can be advanced.

Placing or moving advancement tokens to a card is not the same as advancing it.

{: .note-title }
> Example
>
> The Corp plays Mushin-no-Shin, choosing to install an Oaktown Renovation. Because the three advancement tokens were placed on the card, however, the Corp does not gain any credits from the ability on Oaktown Renovation.

**Related**: Action, Agenda, Corp, Install, Unrezzed.

# Agenda

Agendas represent valuable pieces of the Corp’s data and are worth agenda points.
The Corp installs agendas in remote servers. Agendas can be advanced and have an advancement requirement that must be met before the Corp can score them. Once an agenda is scored, it is added to the Corp’s score area.

Agendas cannot be rezzed. However, some agendas may be installed or turned faceup. Faceup agendas are not rezzed or unrezzed. If an agenda’s text instructs the Corp to install it faceup, that agenda’s abilities are active while it is installed; if an agenda is installed facedown, that agenda’s abilities are inactive while it is installed. There can be only one agenda OR one asset installed in a remote server at a time.

Whenever an agenda is scored or stolen, all advancement tokens are removed from it. Agendas in a player’s score area add to that player’s scored agenda points. Agendas in the Corp’s score area are active.

**Related**: Active, Advancement Requirement, Advancing Cards, Agenda Points, Asset, Corp, Facedown, Faceup, Inactive, Install, Score, Score Area, Scored Points, Server, Steal.

# Agenda Counter

A counter used to track various effects on agenda cards.

**Related**: Abilities, Agenda.

# Agenda Points

A value on an agenda card. This value is how many points an agenda is worth while it is in a score area.

A Corp deck must have a specific number of agenda points based on the size of the deck, as follows:

- 40 to 44 cards requires 18 or 19 agenda points.
- 45 to 49 cards requires 20 or 21 agenda points.
- 50 to 54 cards requires 22 or 23 agenda points.
- For decks larger than this, add 2 additional agenda points to the 54 card deck requirement each time the number of cards in the deck reaches a multiple of 5.

**Related**: Agenda, Corp, Score Area.

# “All”

If a condition refers to “all” of something and there are zero of that thing, the condition is automatically satisfied as soon as it could be satisfied for one or more of that thing.

{: .note-title }
> Example
>
> The Runner plays Forked, initiating a run on a server. The first piece of ice that the Runner encounters is Troll. As Troll has no subroutines, the Runner automatically breaks all of zero subroutines on Troll at step (3.1) of the encounter, trashing it with Forked.

**Related**: Abilities.

# Approaching Ice

The step of a run in which the Runner makes contact with a piece of ice and decides whether or not to continue the run.

If the Runner continues instead of jacking out, the Corp has the opportunity to rez the approached piece of ice and any other non-ice cards. If the Corp rezzes the approached piece of ice (or the ice is already rezzed), then the Runner encounters it.

If the Corp declines to rez the approached piece of ice, then the Runner passes it. The Runner then continues the run by either approaching the next piece of ice protecting the server or approaching the server itself if there is no more ice to approach.

Ice is always approached according to the position it occupies protecting a server, ranging from the outermost piece of ice to the innermost piece of ice. If there is one piece of ice
protecting a server, that piece of ice is both the outermost and the innermost piece of ice. The Runner always starts at the outermost position at the beginning of a run. After passing a piece of ice, the Runner approaches the next position.

If a piece of ice is added to a server during a run in a position that has already been passed, the Runner does not approach that ice.

{: .note-title }
> Example
>
> During a run on R&D, Architect fires and the Corp installs a new piece of ice in the outermost position protecting this server. The Runner does not approach that new piece of ice during this run because they have already passed that position.

If a piece of ice is added in a position the Runner has not yet passed, the Runner will approach that piece of ice.

{: .note-title }
> Example
>
> During a run on a remote server, Howler fires and the Corp installs a new piece of ice in the next position protecting the server. The Runner must approach that new piece of ice during this run because they have not passed that position.

If a piece of ice inside of the Runner’s position is uninstalled during a run, the Runner and each piece of ice outside of the uninstalled ice’s position move one position toward the server; if a piece of ice is installed inside of the Runner’s position during a run, the Runner and each piece of ice outside of the installed ice’s position move one position away from the server. In both situations, the Runner does not re-encounter any ice already passed.

{: .note-title }
> Example
>
> The Runner has passed two ice, and is approaching the innermost piece of ice which is a rezzed Himitsu-Bako. During the paid ability window of the approach, the Corp uses the ability on Himitsu-Bako to put it into HQ. All remaining ice on the server moves one position closer, and the Runner is now approaching the server.

**Related**: Accessing, Corp, Encounter, Ice, Jack Out, Pass, Protecting, Rez, Rezzed, Run, Runner, Server, Timing Structure, Uninstall, Unrezzed.

# Archives

This is the Corp’s trash pile. Archives is kept adjacent to R&D. This is where Corp cards are placed when they are trashed or discarded. Cards in Archives are uninstalled and as such are normally inactive. Cards with “When accessed...” abilities are examples of cards whose text may be active in Archives.

Some cards enter Archives faceup and some cards enter Archives facedown. If a Corp card is visible to the Runner when it is trashed or discarded, it is sent to Archives faceup. If a Corp card is not visible to the Runner when it is trashed or discarded, then it is sent to the Archives facedown. Facedown cards in Archives should be oriented horizontally so that the Runner can easily see them.

Both the Corp and Runner may look through the faceup cards stored in Archives at any time, and do not need to maintain the order of its cards while doing so. The Corp can also look at the facedown cards in Archives at any time; the Runner cannot.

When accessing cards in Archives, the Runner turns all cards faceup in Archives before accessing them. The Runner then accesses and resolves individual cards one by one in the order of their choosing until they have accessed and resolved all cards in Archives. If the Runner uses a replacement effect that either replaces the effect of accessing cards or changes which server the run is considered successful on, then they do not turn
facedown cards faceup.

**Related**: Abilities, Accessing, Active, Corp, Discard, Facedown, Faceup, Inactive, Replacement Effects, Trash, Uninstall.

# Asset

Assets represent various resources and connections at the Corp’s disposal.

The Corp installs assets in remote servers. An asset is not active until it is rezzed by paying credits equal to its rez cost. There can be only one agenda OR one asset installed in a remote server at a time.

Some assets can be advanced. Whenever an asset with advancement tokens is uninstalled, return all advancement tokens on it to the bank.

When the Runner accesses an asset, they can trash it by paying credits equal to its trash cost.

**Related**: Abilities, Active, Advancing Cards, Agendas, Corp, Cost, Install, Rez, Rezzed, Score, Server, Trash, Trash Cost.

# Attacked Server

When the Runner initiates a run, they select the server on which they wish to run at step (1), usually based on which cards they ultimately wish to access. The selected server is considered the attacked server. Card abilities can sometimes change the attacked server during the run. This does not end the run, but it can affect whether or not certain card abilities or effects apply.

**Related**: “If successful...”, Run, Server, Timing Structures.

# Avoid

Avoid (and prevent) effects are the only effects which can disrupt another effect. An avoid effect states what it is avoiding and an effect that is avoided is not resolved. Avoid effects can only be triggered whenever the effect they are avoiding is in the “triggered” state.

Avoid effects take priority over conditional abilities that would trigger from whatever is being avoided, except when a conditional ability uses the word “additional.” An “additional”
conditional ability occurs simultaneously with the trigger condition and can be avoided along with the trigger condition.

**Related**: Abilities, “Additional”, Prevent.

# Bad Publicity

For each bad publicity the Corp has, the Runner gains **1**<span class="nric-grey credit"></span> at the beginning of each run. If the Corp takes bad publicity during a run, the Runner does not gain additional bad publicity credits for that run. Unspent bad publicity credits return to the bank at the end of the run.

**Related**: Bank, Corp, Credits, Run, Runner, Timing Structures.

# Bank

The supply of credit tokens, advancement tokens, tag tokens, bad publicity tokens, brain damage tokens, and generic tokens not yet in play. Tokens in the bank are available to both players.

**Related**: Advancing Cards, Bad Publicity, Corp, Credit, Damage, Runner, Tag.

# Bypass

When an effect allows the Runner to ‘bypass’ a piece of ice, they immediately pass that ice and continue the run. Most bypass effects occur at the beginning of an encounter and cause steps (3.1) and (3.2) to be skipped, meaning that subroutines on the encountered ice are neither broken nor resolved. A few bypass effects can be triggered later: if ice is bypassed in step (3.1), subroutines may or may not have been broken, but no subroutines resolve as step (3.2) is skipped. Note that for ice with zero subroutines, the Runner has ‘broken all subroutines’ if and only if step (3.1) was reached.

{: .note-title }
> Example
>
> The Runner plays Forked and encounters a Troll that they can bypass with Femme Fatale. The Runner pays to bypass the current piece of ice with Femme Fatale. Forked does not meet its trigger condition, and Troll is not trashed, because the opportunity to break subroutines was never reached.

**Related**: All, Ice, Pass, Run, Subroutines.

# “Cannot”

Cards that use the word “cannot” prohibit an ability from resolving or an action from taking place.

If a “cannot” fully prohibits an ability, a card that has that ability is unable to be played or triggered.

If a “cannot” prohibits only part of an ability, a card that has that ability can be played or triggered, though the prohibited part does not resolve.

{: .note-title }
> Example
>
> During a run, Lockdown’s subroutine fires, preventing the Runner from drawing cards for the remainder of the turn. The Runner has a Diesel and a Process Automation in their grip. For the remainder of this turn, they cannot play Diesel as its entire ability is prohibited, but they can play Process Automation. Even though cards cannot be drawn through Process Automation, the Runner can play it to gain **2**<span class="nric-grey credit"></span>

**Related**: Abilities, Action.

# Card Conversion

Some cards are installed as counters or added to a score area as an agenda. When a card is converted into a different type of object, it keeps its name but loses all other properties and gains only those properties specified in the effect converting it. This conversion lasts until the card is either uninstalled or leaves the play area, at which point it returns to being its original printed card and is placed in its owner’s trash pile.

**Related**: Agenda, Install, Score Area, Trash, Uninstall.

# Chain Reactions

If during the resolution of an ability another ability meets its trigger condition, then a “chain reaction” is created. The ability that just met its trigger condition resolves immediately following the active effect on the current ability. If this ability results in another ability meeting its trigger condition, then that ability is also “chained.” Resolve all the abilities from the most recent trigger condition before continuing.

{: .note-title }
> Example
>
> The Runner is playing Geist and accesses a Snare! from R&D with only 2 cards in their grip. Before taking a tag or suffering any net damage, the Runner uses Forger to avoid the tag. Using the Forger causes Geist to meet its trigger condition. As it is the most recent ability to meet its trigger condition, it must trigger and resolve first before Forger avoids the tag and before Snare! finishes resolving. The Runner draws a card from Geist, avoids the tag from Snare! with Forger, and then finally suffers and survives the 3 net damage from Snare!

One exception, however, is if an effect is being resolved that causes a search, the entire effect (including shuffling) must resolve before any other chained card ability can resolve.

**Related**: Abilities, Active, Search.

# Choosing Cards

Unless otherwise noted, a card ability that requires a player to choose a card can only affect installed cards.

{: .note-title }
> Example
>
> The Corp resolves a subroutine that says “ <span class="nric-grey subroutine "></span> The Runner trashes 1 program.” The Runner must trash one of their installed programs and may not trash a program from their grip or stack.

If a specific card or card type in an inactive state is chosen by a card effect, the Corp must show the Runner which card is being affected without changing its faceup or facedown status. The Corp must also reveal the card if it was facedown and the effect relies on a specific attribute of the card.

{: .note-title }
> Example
>
> The Corp must reveal a facedown operation in Archives before adding it to before adding it to HQ with Clone Suffrage Movement.

## Batch Effects

A batch effect is one that affects multiple objects in the game at once. This can include an effect that operates on multiple chosen cards or an effect for which the multiple cards are
dictated by the effect (for example, Apocalypse). Whenever a batch effect resolves, all of the objects that will be affected are first determined (or chosen, if applicable), then all of those cards are affected simultaneously. When determining which cards will be affected, each card can only be determined or chosen once. If the cards to be affected are chosen by a player, but there are not enough cards available to be chosen, then that player chooses as many cards as possible.

{: .note-title }
> Example
>
> The Runner accesses an Aggressive Secretary with three advancement tokens on it. The Runner only has two installed programs, so the Corp chooses both of those programs for Aggressive Secretary. After programs have been chosen, they are both trashed simultaneously. 

**Related**: Abilities, Corp, Facedown, Faceup, Inactive, Install, Reveal, Runner, Simultaneous Effects.

# Click

A click <span class="nric-grey click"></span> is the basic unit of work. Players spend their clicks to perform actions and trigger abilities. Multiple clicks can be represented either by multiple symbols, such as <span class="nric-grey click"></span><span class="nric-grey click"></span>, or by a numeral and symbol, such **2** <span class="nric-grey click"></span>, both meaning “two clicks.”

Clicks are tracked as a running total and not individually, which can be increased or decreased by card effects.

**Related**: Abilities, Action.

# Click Tracker Card & Tokens

Each player has a number of two-sided click tokens that they can flip to track the number of clicks they have remaining in their running total. Click tokens can be placed on the click tracker card for ease of reference.

**Related**: Click

# Composite Effect

A composite effect is one that uses the word “and” to combine multiple effects into one. Both parts resolve simultaneously, and the opportunity to prevent either or both parts occurs before either effect.

{: .note-title }
> Example
>
> Snare! Does 3 net damage to the Runner and gives the Runner a tag simultaneously. The Runner can prevent the net damage, avoid the tag, or both before any of the remaining unprevented effects resolve.

The individual effects in a composite effect are not dependent of each other. As long as at least one of the effects in the composite effect has the potential to change the game state or is otherwise resolvable, the whole ability can be used and as much as can resolve does resolve.

{: .note-title }
> Example
>
> If the Runner accesses a rezzed card while Aeneas Informant is installed, they still gain 1< even though the rezzed card is already revealed.

**Related**: Avoid, Prevent, Simultaneous Effects.

# Console

A console is a special piece of Runner hardware with particularly powerful and unique abilities.

All consoles feature the text “Limit 1 console per player.” This restriction refers only to active consoles. A player can have multiple copies of a console, and even different consoles,
in their deck. The limit of 1 console per player prevents the Runner from installing a second console, even if the Runner wishes to trash the first.

While a console is installed, if an effect would attempt to force another console to be installed, that console is trashed instead of being installed.

**Related**: Abilities, Hardware, Install, Runner.

# Corp / Corporation

One of the two sides available to the player in Android: Netrunner. The opponent of the Runner. Referred to as “the Corp” on card text.

**Related**: Corp Cards, Runner.

# Corp Cards

There are six types of Corp cards: agendas, assets, ice, identities, operations, and upgrades. All cards except the identity card are shuffled into the Corp’s deck at the beginning of the game. Unless specified, Corp cards are installed facedown and are inactive until rezzed.

**Related**: Agenda, Asset, Facedown, Ice, Inactive, Identity, Operation, Rezzed, Unrezzed, Upgrade.

# Credit

A credit <span class="nric-grey credit"></span> is the basic unit of currency. Players spend their credits to pay for various costs, card abilities, traces, etc. Both the Corp and the Runner can spend <span class="nric-grey click"></span> to gain **1**<span class="nric-grey credit"></span> during their Action Phases.

**Related**: Abilities, Action, Bank, Corp, Cost, Runner, Trace.

# Credit - Recurring

Recurring credits <span class="nric-grey re-credit"></span> are placed on a card when the card becomes active and can be used immediately. Recurring credits do not accumulate - a player refills recurring credits up to the number listed on the card when their turn begins. This occurs at step (1.3) of the turn.

**Related**: Active, Credit, Timing Structures.

# Credit Pool

Each player has a credit pool where they keep the credit tokens they have available to spend. The number of credits in a player’s credit pool is open information.

Credits enter and leave a player’s credit pool as that player gains, takes, spends, or loses credits.

When a player “gains” credits, they move the specified number of credits from the bank to their credit pool.

When a player “takes” credits, they move the specified number of credits from the specified source (usually a card that has credits on it) to their credit pool.

When a player “loses” credits, that player is forced to move the specified number of credits from their credit pool to the bank.

When a player “spends” credits, they move the specified number of credits from their credit pool to the bank in order to to pay a cost.

Recurring credits are not considered to be in the credit pool. If an effect causes a player to lose credits, the credits are lost from their credit pool and not from their recurring credits.

**Related**: Bank, Credit, Credit - Recurring, Information.

# Cost

A cost is any resource a player must spend or requirement that must be met in order to initiate a game effect, including using an ability, taking an action, or rezzing cards. If a player cannot pay the full cost of an action or ability all at once using their own available resources, they cannot use the effect associated with that cost. If any part of a cost is prevented (for example, preventing a card from being trashed that has a paid ability with
the cost of trashing that card), then the associated effect does not occur.

There are six main types of costs: install costs (found mainly on hardware, programs, and resources, and incurred when installing ice), play costs (found on operations and events), rez costs (found on assets, upgrades, and ice), paid ability trigger costs (as denoted by “cost: effect”), additional costs, and nested costs.

## Additional Costs

An additional cost adds something to the regular cost of initiating a particular game effect. A player must pay all additional costs along with any regular costs in order to initiate an effect. However, if a player is ever forced into a game effect that has an additional cost, that player may decline to pay the additional cost, even if they are able to pay it, thus preventing that effect from occurring.

{: .note-title }
> Example
>
> The Runner accesses an Obokata Protocol. Normally the Runner is forced to steal agendas that they access, but because Obokata Protocol has an additional cost to steal, the Runner can decline to suffer the net damage and not steal the agenda.

A player must pay all additional costs simultaneously with the cost that is being added to, even if multiple cards or abilities are adding separate additional costs. A player cannot pay the original cost or any of the additional costs individually; if they cannot pay for all of the costs at once, then they do not pay any of the costs and the effect associated with the costs does not occur.

{: .note-title }
> Example
>
> The Runner accesses an Obokata Protocol while Ben Musashi and Predictive Algorithm are both active. The Runner must be able to pay 2 credits and suffer 6 net damage all at once in order to steal the Obokata Protocol, even though each of the three costs are from different card abilities. After all costs have been paid, abilities that meet their trigger conditions from the paying of any of those costs, such as I’ve Had Worse or Order of Sol, can then resolve as applicable.

## Nested Costs

Although constant and conditional abilities do not generally have costs associated with them, their individual effects can incur costs. These are usually written with the word “to” in the card text. The part of the ability preceding the “to” is considered a cost and must be paid following all the regular rules of costs in order to resolve the effect following the “to”.

## Install Cost

Found in the upper left corner of hardware, programs, and resources, an install cost is a cost that must be paid in order for a card to be installed.

When a piece of ice is installed, the Corp must pay an install cost equal to the number of pieces of ice already protecting that server.

## Paid Abilities

See page: **Abilities > Triggered Abilities > Paid Abilities**

## Play Cost

Found in the upper left corner of operations and events, a play cost is a cost that must be paid in order for an operation or event to be played.

## Rez Cost

Found in the upper left corner of assets, upgrades, and ice, a rez cost is a cost that must be paid in order for an asset, upgrade, or piece of ice to be rezzed.

## Trashing as a Cost

Some cards have paid abilities that require trashing that card to use the ability, as indicated by the <span class="nric-grey trash"></span> symbol in its cost text.

When a trash ability on a card is triggered, any reference to the game state within that resolving effect is based on the game state as it was at the moment of trashing, but with the trashed card considered a new copy of that card in Archives or the heap.

{: .note-title }
> Example
>
> The Corporation trashes Allele Repression with 3 advancement counters on it. The Corporation would be able to swap 3 cards out of Archives for 3 cards in HQ, even though the advancement counters were discarded when Allele Repression was trashed. Additionally Allele Repression itself could be swapped back to HQ.

**Related**: Abilities, Action, Archives, Asset, Corp, Event, Hardware, Heap, Ice, Install, Install Cost, Operation, Paid Ability Window, Prevent, Protecting a Server, Program, Resource, Rez, Rez Cost, Runner, Trash, Upgrade.

# Damage

Many cards and ice subroutines inflict damage on the Runner. If the Runner takes more damage than the number of cards in their grip, or if they have a maximum hand size of less than zero at the end of their turn, then they are flatlined and the Corp wins the game.

The Runner “suffers”/“takes” damage whenever damage is “done” to the Runner. However, damage is not necessarily “done” when the Runner “suffers”/“takes” damage.

{: .note-title }
> Example
>
> The Corp, playing as Argus Security, has scored The Cleaners. The Runner makes a run on R&D and steals a Hostile Takeover. Argus Security’s ability triggers and the Runner chooses to suffer 2 meat damage. As The Cleaners only adds additional damage when damage is “done” and not “suffered”, The Cleaners does not trigger.

The Runner can receive the following three types of damage:

**Brain damage**: The Runner randomly trashes one card from their grip for each point of brain damage suffered, and their maximum hand size is permanently reduced by one card. The Runner takes a brain damage token to track this.

**Meat and Net damage**: The Runner randomly trashes one card from their grip for each point of damage suffered. Functionally, meat damage and net damage are identical. The only differences between meat and net damage are the cards that inflict and prevent them.

If the Runner suffers more than 1 damage of any type, then cards are randomly trashed from the grip one at a time to maintain the order of the heap, but all of the cards are
considered trashed simultaneously.

{: .note-title }
> Example
>
> The Runner has 2 tags and four cards in their grip, one of which is I’ve Had Worse. The Corp plays BOOM!, dealing 7 meat damage to the Runner. If the Runner cannot or does not prevent at least 3 of the incoming damage, they immediately flatline as they have suffered more damage than they have cards in grip. If the Runner does prevent enough of the damage to survive, the Runner randomly trashes one card at a time for each damage suffered. After all the cards have been randomly selected and placed in the heap, I’ve Had Worse triggers if it is among those cards trashed to the damage.

**Related**: Abilities, Flatline, Grip, Maximum Hand Size, Prevent, Trash, Winning the Game

# Deckbuilding

When building a deck, players must observe the following restrictions:

1. A deck must be associated with a single identity card, and cannot contain fewer cards than the minimum deck size value listed on the chosen identity card. There is no maximum deck size, but the deck must be able to be sufficiently randomized in a short period of time. Identity cards, cards that begin the game in play because of an ability, reference cards, and click tracker cards are never counted as part of a deck and do not count against the minimum deck size.
1. A deck cannot have more than three copies of a single card (by title) unless a card ability states otherwise.
1. A deck associated with a Runner identity can never contain Corp cards, and vice versa.
1. A deck cannot contain out-of-faction cards with a total influence value that exceeds the influence limit listed on the chosen identity card. Cards that match the faction of the identity card do not count against this limit.
1. A Corp deck must have a specific number of agenda points in it based on the size of the deck, as follows:
- 40 to 44 cards requires 18 or 19 agenda points.
- 45 to 49 cards requires 20 or 21 agenda points.
- 50 to 54 cards requires 22 or 23 agenda points.
- For decks larger than this, add 2 additional agenda points to the 54 card deck requirements each time the number of cards in the deck reaches a multiple of 5 (55, 60, 65, etc.).

{: .note-title }
> Example
>
> A 66 card deck requires 6 additional agenda points (2 at 55, 2 at 60, and 2 at 65 cards). This gives a final requirement of either 28 or 29 agenda points.

**Related**: Abilities, Agenda Points, Corp, Faction, Identity, Influence, Runner.

# Derez

Derezzing is the act of flipping a rezzed Corp card facedown. It is opposite of rezzing.

**Related**: Facedown, Rez.

# Discard

Discarding is the act by which a player moves a card to their trash pile during their discard phase if they have exceeded their maximum hand size.

Cards discarded from HQ are always sent to Archives facedown, regardless of whether they have been previously accessed by the Runner.

A discarded card is not considered to have been trashed, and vice versa. Cards that prevent a card from being discarded cannot prevent a card from being trashed, and vice versa.

**Related**: Accessing, Archives, Corp, Discard Phase, Facedown, Headquarters (HQ), Heap, Maximum Hand Size, Prevent, Runner, Timing Structures, Trash.

# Discard Phase

The discard phase is the last phase of both the Corp and Runner’s turn.

During the Corp’s discard phase, they perform the following steps in order:

1. The Corp discards one card at a time from HQ until there are cards in HQ equal to their maximum hand size.
1. Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-ice cards <span class="nric-grey rez"></span>
1. The Corp loses unspent <span class="nric-grey click"></span>
1. The Corp’s turn ends.
- The Corp’s “When your turn ends...” conditionals meet their trigger conditions.

During the Runner’s discard phase, they perform the following steps in order:

1. The Runner discards one card at a time from the grip until there are cards in the grip equal to their maximum hand size.
1. Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non- ice cards <span class="nric-grey rez"></span>
1. The Runner loses unspent <span class="nric-grey click"></span>
1. The Runner’s turn ends.
- The Runner’s “When your turn ends...” conditionals meet their trigger conditions.

**Related**: Abilities, Agendas, Click, Corp, Discard, Grip, Headquarters (HQ), Maximum Hand Size, Paid Ability Windows, Rez, Runner, Score, Timing Structures.

# Draw Phase

The draw phase is the first phase of the Corp’s turn. During the draw phase, they perform the following steps in order:

1. The Corp gains allotted clicks, default: <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span>
1. Players may use paid abilities <span class="nric-grey paid"></span>. The Corp may rez non-ice cards <span class="nric-grey rez"></span> and score agendas <span class="nric-grey agenda "></span>
1. The Corp’s recurring credits <span class="nric-grey re-credit"></span> refill.
1. The Corp’s turn begins.
- The Corp’s “When your turn begins...” conditionals meet their trigger conditions.

<ol class="custom-ol" style="--start: 5;">
<li>The Corp draws 1 card from the top of R&D into HQ.
</li>
</ol>
- This does not spend <span class="nric-grey click"></span>
- The Runner wins if R&D contains no cards during this step.

**Related**: Abilities, Agenda, Click, Corp, Credit - Recurring, Headquarters (HQ), Paid Ability Windows, Research and Development (R&D), Rez, Score, Timing Structures, Winning the Game.

# Effect

The resolution of a card ability. Unless otherwise noted, each player makes the choices required by the effects on their cards. If a player is specified in the text of the effect, then that player is considered responsible for the effect’s resolution; otherwise the card’s owner is considered responsible.

{: .note-title }
> Example
>
> The Corp has a rezzed Hostile Infrastructure. Apocalypse does not specify who trashes the cards, so the Runner is assumed to have trashed the cards because Apocalypse is a Runner card, and Hostile Infrastructure triggers.

{: .note-title }
> Example
>
> Alice Merchant states that “the Corp must trash 1 card from HQ”, so the Corp is assumed to have trashed the card from HQ even though Alice is a Runner card, and therefore Hostile Infrastructure does not trigger.

**Related**: Abilities

# Encounter

The step of a run in which the Runner can interact with a piece of ice and the ice’s subroutines can resolve. 

When the Runner encounters a piece of ice, they must resolve any abilities triggered by the encounter before they can trigger paid abilities or break subroutines.

## Forced Encounters

If an effect requires the Runner to encounter a piece of ice outside of the normal progression of a run, resolve steps 3 through 3.2 of the timing structure of the run. After the encounter, if the run was not ended, return to the effect that caused the encounter and proceed from there.

{: .note-title }
> Example
>
> The Twins does not cause an extra approach phase.

This type of encounter neither affects nor is affected by the Runner’s position in the run.

{: .note-title }
> Example
>
> If Shiro causes Chrysalis to be accessed, resolve the encounter with Chrysalis and then return to resolving subroutines on Shiro.

If an effect requires the Runner to approach a piece of ice, this does not initiate any additional timing structures. It only moves the Runner’s position in the current run.

**Related**: Abilities, Ice, Paid Ability Windows, Run, Runner, Subroutine, Timing Structures.

# Event

Events represent singular occurrences and are always trashed after being played.

For <span class="nric-grey click"></span>, the Runner plays an event from the grip into the play area by paying its play cost. When played, an event’s abilitiesas listed in its text box are resolved. Then, the event is trashed. Events are never installed.

**Related**: Abilities, Grip, Install, Play, Play Cost, Runner, Trash.

# Expose

Some effects expose one or more cards. Only unrezzed installed cards can be exposed. An exposed card is shown to all players and then returned to its previous state. If multiple cards are exposed by one effect, they are considered to be exposed simultaneously.

**Related**: Information, Install, Unrezzed.

# Facedown

The opposite of faceup. A facedown card is one on the table that is turned so that the face containing the card’s information is not visible. Unless otherwise noted, Corp cards are installed facedown, unrezzed.

Runner cards are usually installed faceup, but some can be installed or turned facedown. Runner cards that are installed or turned facedown do not have a name, type, or subtypes,
and their abilities are not active. The Runner can look at their facedown cards at any time. If a facedown Runner cards is trashed, it is turned faceup as part of the trash effect, then it
is added to the heap. A Runner card turned facedown is not considered to be uninstalled and remains in the same position of the Runner’s rig.

If a Runner card is installed facedown from an out-of-play area, that card is placed in its own row (rather than in the program, hardware, or resources row).

If an installed facedown Runner card is turned faceup, the card gains its name, type, and subtypes, and its abilities become active. Turning an installed facedown Runner card faceup does not trigger install effects.

**Related**: Abilities, Active, Corp, Faceup, Heap, Inactive, Install, Rig, Runner, Subtype, Trash, Uninstall, Unrezzed.

# Faceup

The opposite of facedown. A faceup card is one on the table that is turned so that the face containing the card’s information is visible. Unless otherwise noted, Runner cards are installed faceup, while Corp cards are usually installed facedown. Some Corp cards can be turned faceup by card abilities or by rezzing them.

**Related**: Abilities, Agenda, Corp, Facedown, Install, Rez, Runner.

# Faction

Cards are divided into ten factions: four Corp factions, three Runner factions, and three Runner mini-factions. Factions and influence restrict deckbuilding options, allowing each faction to have distinct play differences from one another.

Identities are associated with specific factions. Using a card of the associated faction does not cost influence; using a card from a different faction, including Neutral cards, costs influence equal to the number of influence pips found on the card. A deck can only contain out-of-faction cards with a total influence value equal to or less than its identity’s influence limit.

**Related**: Deckbuilding, Influence.

# Flatline

A loss condition for the Runner resulting from the Runner being forced to trash more cards than they have in grip, or from having a maximum hand size that is below zero at the end of their turn.

**Related**: Damage, Grip, Maximum Hand Size, Runner, Trash, Winning the Game.

# “For Each”

When the resolution of an ability involves an effect repeated “for each” of a quantity, the full effect of the ability is first calculated, and then the ability resolves. A “for each” effect does not affect each specified item one at a time, but instead applies a single resolution of the ability as described. If the ability would resolve on an empty set or a value of 0, then nothing is counted and thus the effect does not resolve.

{: .note-title }
> Example
>
> The Runner encounters a Cortex Lock and does not break the subroutine. If the Runner has 2 unused MU, both of the net damage can be prevented with Biometric Spoofing because Cortex Lock does a single batch of 2 net damage, not 2 batches of 1 net damage each. If the Runner has no unused MU, then no net damage is dealt because there is no MU to count, and Cortex Lock does not meet its trigger condition.

# Forfeit

Some card abilities require the Corp or Runner to forfeit an agenda. When a player forfeits an agenda, that agenda is removed from the game (it does not go to Archives or the heap). The player no longer scores points for the forfeited agenda. All cards hosted on that agenda are trashed and all tokens that are hosted on that agenda are returned to the bank.

**Related**: Agenda, Archives, Corp, Heap, Host, Runner, Score Area, Scored Points, Trash.

# Grip

This is the Runner’s hand of cards. The Runner begins the game with a maximum hand size of five cards. Cards in the grip are inactive.

The number of cards in the grip is open information, though the qualities of each card (faction, name, types, subtypes, values, abilities, artwork etc.) is hidden information.

**Related**: Abilities, Faction, Inactive, Information, Maximum Hand Size, Runner, Subtype.

# Hardware

Hardware is the array of physical tools at the Runner’s disposal. The Runner installs hardware in their rig by paying an install cost. There is no limit to the amount of hardware the Runner can install in their rig.

**Related**: Install, Install Cost, Rig, Runner.

# Headquarters (HQ)

This is the Corp’s hand of cards. The Corp begins the game with a maximum hand size of five cards. Cards in HQ are inactive.

The Corp’s identity card represents their HQ for the purposes of gameplay. Ice protecting HQ is installed in front of the Corp’s identity card and upgrades installed in the root of HQ are installed behind the Corp’s identity card.

When the Runner accesses multiple cards from HQ, the cards are accessed one at a time, and do not return to HQ until the Runner is finished accessing. The Runner can intersperse accessing cards from HQ with any upgrades installed in the root of HQ.

The number of cards in HQ is open information, though the qualities of each card (faction, name, types, subtypes, values, abilities, artwork etc.) is hidden information. 

**Related**: Accessing, Faction, Ice, Identity, Inactive, Information, Install, Maximum Hand Size, Protecting a Server, Root, Runner, Subtype, Upgrades.

# Heap

This is the Runner’s trash pile. When the Runner’s cards are trashed or discarded, the Runner places those cards in their heap. Cards in the heap are faceup and inactive. Both the Runner and Corp may look through the heap at any time, but must maintain the order of its cards.

**Related**: Discard, Faceup, Heap, Inactive, Runner, Trash.

# Host

To host a card, token, or counter is to place it on top of a card, creating a relationship between those two objects. The card/token/counter on top of a card are referred to as being “hosted” on that card; the card doing the “hosting” is often referred to as the “host”.

Any card has the capability to host other objects but it takes card abilities to create host relationships. Abilities can also place restrictions on how many objects can be hosted and how they can be hosted onto cards. Cards are always hosted faceup or facedown onto other cards as they would be when installed, unless otherwise noted.

If a card states that it can host cards but has no ability that states how, it can only host a card as it is being installed. A card that is already installed cannot be moved into a host relationship with another card.

{: .note-title }
> Example
>
> Off-Campus Apartment has the ability “Off-Campus Apartment can host any number of connections.” This means that whenever the Runner installs a connection card, they can choose to place that card either into their rig natively or onto Off-Campus Apartment as a hosted connection. Connections installed before Off-Campus Apartment is installed cannot be moved onto Off-Campus Apartment.

If the card states how it hosts cards, that is the only way a card can be hosted on it.

{: .note-title }
> Example
>
> Glenn Station can only host cards through its paid ability, <span class="nric-grey click"></span> Host a card from HQ facedown on Glenn Station.”

Host relationships are not transitive. A card hosted on a card is not also considered to be hosted on that card’s host.

{: .note-title }
> Example
>
> If the Runner installs a Leprechaun hosted on a Dhegdheer, programs hosted on Leprechaun do not have their install costs reduced because they are hosted on Leprechaun and not on Dhegdheer.

## Hosted

A card, token, or counter on a card is referred to as “hosted” on that card. An object can only be hosted on one card at a time.

In card text, the word “hosted” is always self-referential and refers only to objects hosted on that card, unless otherwise noted. Hosted counters and tokens can be spent without
affecting their host. If a trigger cost requires one or more hosted counters or tokens, those counters or tokens are “spent” by being returned to the bank from the card the ability appears on.

If a host is uninstalled, all cards, counters, and tokens hosted on it are trashed. This cannot be prevented. If a host is turned facedown in any way, all cards, counters, and tokens hosted on it remain hosted.

The state of being hosted is distinct, but not exclusive from, the state of being installed. Many cards are hosted on another card at the moment they are installed. When specified, cards can be hosted but not installed; in these cases those hosted cards are inactive.

## Hosting

Any card with cards, tokens, or counters on it is referred to as “hosting” those objects.

**Related**: Abilities, Card Conversion, Facedown, Faceup, Install, Prevent, Trash, Uninstall.

# Ice

Ice defends the Corp’s servers against intrusions by the Runner.

When the Corp installs a piece of ice, they must install it in the outermost position of the server and pay an install cost equal to the number of pieces of ice already protecting that server. The outermost position is the position farthest from the server, in front of any other pieces of ice that are protecting the server. After a piece of ice is installed protecting a server, it is dedicated to that server and cannot be moved or rearranged.

A piece of ice often has one or more subroutines <span class="nric-grey subroutine "></span> in its text box that the Runner can break during a run if the ice is rezzed. Ice is inactive until it is rezzed by paying credits equal to its rez cost.

**Related**: Active, Corp, Inactive, Install, Install Cost, Protecting a Server, Rez, Rez Cost, Run, Runner, Strength, Subroutine.

# Icebreaker

Icebreakers are programs with the icebreaker subtype that the Runner can use to overcome ice encountered during a run. Each icebreaker has a strength, an install cost, and one or more subtypes that reflect which kind of ice subroutine it is designed to break.

The Runner uses icebreakers to interact with and break subroutines on ice. An icebreaker can only interact with ice that has equal or lower strength than the icebreaker.

Many icebreakers allow the Runner to temporarily increase the icebreaker’s strength by spending credits. This helps the Runner deal with stronger pieces of ice, provided they have enough credits to spend. This strength increase lasts only while the current piece of ice is being encountered, unless otherwise noted by card abilities. After an encounter with a piece of ice, the icebreaker’s strength returns to the value shown on its card. This applies to any other strength modifiers given by icebreakers as well. The Runner can boost the strength of their icebreakers outside of an encounter with a piece of ice. However, unless the icebreaker says otherwise, its strength is immediately reset to its previous value.

In addition to this strength requirement, many icebreaker abilities can only be used to break subroutines on particular subtypes of ice. It does not matter if the ice has additional subtypes, provided it has any subtypes referred to by the icebreaker’s ability. If an ability does not restrict itself to a subtype, it can be used against any piece of ice. The Runner can only break subroutines on a piece of ice during step (3.1) of a run. If step (3.1) of a run is not reached, such as when bypassing a piece of ice, then no subroutines on that piece of ice are broken.

**Related**: Abilities, Bypass, Credit, Encounter, Ice, Install Cost, Pass, Program, Run, Runner, Strength, Subtype.

# Identity

Each player has an identity card that is placed faceup in their play area. The identity card does not count toward their maximum hand or deck size and is always active during the
game.

The Corp or Runner’s identity card defines the Corp or Runner’s faction and describes the identity’s special ability. It also provides a minimum deck size that must be observed and the amount of influence available for spending on out-of-faction cards when deckbuilding.

The Corp’s identity card also represents their HQ for the purposes of gameplay. Ice protecting HQ is installed in front of the Corp’s identity card and upgrades installed in the root of HQ are installed behind the Corp’s identity card.

**Related**: Active, Corp, Deckbuilding, Faceup, Faction, Headquarters (HQ), Ice, Influence, Maximum Hand Size, Runner, Upgrade.

# “If able”

If an ability includes the phrase “...if able”, it can only either resolve completely or not at all. If the ability cannot fully resolve, then the ability has no effect.

**Related**: Abilities.

## “If successful…”

Whenever there is an “If successful...” effect tied to the outcome of a run on a given server, the run itself must have been successful against the specified server(s), if applicable. If the Runner initiates a run against the specified server but the run moves to a different server, the “If successful...” effect does not resolve when the run is successful.

If the ability including “If successful...” does not specify a server, then it does not matter if the attacked server is changed during the run, and the ability resolves as normal.

{: .note-title }
> Example
>
> The Runner plays Legwork and makes a run on HQ. During the run, Susanoo-no-Mikoto moves the Runner to Archives. Even if the Run is successful, the Runner cannot use the “If successful…” effect on Legwork because the run would not be successful against HQ.

**Related**: Attacked Server, Run, Runner, Server.

# Inactive

A state in which a card’s abilities are unable to be used or affect the game. Even though they do not affect the game, inactive cards retain their printed characteristics (name, card type, faction, cost, subtypes, influence, etc).

Runner cards are generally inactive in the heap, grip, and stack until installed into the play area. Agendas in the Runner’s score area are inactive.

In addition to being inactive in R&D, HQ, and Archives, Corp cards are generally installed unrezzed, and thus inactive. 

If an ability explicitly mentions an effect from a regularly inactive state, or if it can only work while the card is inactive, then that ability can still trigger and affect the game. This includes:

- “When accessed...” abilities on cards, which still trigger even while the card is inactive.
- Abilities that state they trigger from an inactive zone can still be triggered and used even though the card is normally inactive in that zone.
- Effects that modify how or when a card can be played or installed affect that card and the game even while the card would normally be inactive.

**Related**: Abilities, Agenda, Archives, Corp, Faction, Grip, Heap, Headquarters (HQ), Influence, Install, Research and Development (R&D), Runner, Score, Stack, Subtype.

# In a Server

Agendas, assets, and upgrades are installed in remote servers. The cards in the Corp’s hand, deck, and discard are in HQ, R&D, and Archives (respectively). Upgrades installed in the root of a central server are not in that central server. Ice is installed protecting a server, but is not in that server.

**Related**: Archives, Agenda, Asset, HQ, Ice, Install, Research and Development (R&D), Server, Upgrade.

# Infinite Loops

If a mandatory infinite loop is created (a player cannot choose to stop resolving the loop) then the player who is resolving the loop chooses a number. The loop instantaneously resolves that many times, and then ends.

{: .note-title }
> Example
>
> The Runner runs into a rezzed Wormhole. The only other piece of ice that is rezzed is a Wormhole, and so a mandatory infinite loop is created where each the Wormholes’ subroutines resolves the other. The Corp chooses how many times this loop occurs, say 2,157 times, and then the Runner continues the run.

If an optional infinite loop is created (a player can choose to stop resolving the loop) during a run then the Runner must jack out unless another card ability prevents him or her from doing so. If the Runner cannot jack out, then it is the Corp’s responsibility to end the loop by letting the Runner continue the run.

**Related**: Abilities, Corp, Jack Out, Run, Runner.

# Influence

A player may wish to include cards in their deck that do not match the faction of their identity card. They are restricted, however, by the influence limit on their identity card. The combined influence value of out-of-faction cards in their deck cannot exceed this limit. Each card’s influence value is represented by small blue pips near the bottom of the card.

Neutral cards are not part of any faction and count their influence values toward every faction’s influence limit (though many neutral cards have an influence value of 0).

Some cards, such as agendas, do not have any influence value (this is different than a card that has an influence value of zero). These cards are identified by their lack of an influence box. A card without an influence value cannot be used with an identity card that has a different faction affiliation.

**Related**: Faction, Identity.

# Information

Android: Netrunner, at its core, is a game about information. Much of the game revolves around deducing information about the opponent’s cards and strategy. Information in the game is classified as follows.

## Hidden Information

Hidden information is any information about the game, game state, or cards unavailable to one or more players. This includes facedown cards in play or in Archives, cards in HQ or R&D, cards in the Runner’s grip or stack, etc.

A player cannot learn hidden information without the aid of a game effect, rule, or another player verbally communicating the information. However, if a player that has access to information about the game or a card and chooses to verbally share it with
their opponent, that player is not required to tell the truth. Bluffing is allowed.

{: .note-title }
> Example
>
> The Runner uses Indexing. While rearranging cards, the Runner places Braintrust on top of R&D, followed by Snare!. The Corp draws at the beginning of their next turn, then spends their first click to draw a card. For their second click, the Corp installs a card in an empty remote server, telling the Runner that they should run it because it is a Braintrust.

## Open Information

Open information is any information about the game, game state, cards, or abilities that is available to both players. This includes faceup cards in Archives and the heap, the number
of cards in HQ, R&D, the stack, and the grip, the number of credits in a credit pool, and any other information continuously available to both players.

Open information cannot be hidden from an opponent. A player must allow their opponent to discover the information themselves if they attempt to do so.

{: .note-title }
> Example
>
> The Runner installs Femme Fatale, choosing a piece of ice protecting HQ with Femme’s ability. The Runner must explicity state to the Corp which ice has been chosen and must
continue to do so if the Corp asks for Femme Fatale’s target during a later turn.

**Related**: Archives, Corp, Credit, Credit Pool, Expose, Facedown, Faceup, Grip, Headquarters (HQ), Research and Development (R&D), Reveal, Rez, Runner, Stack, Unrezzed.

# Initiate vs. Make a Run

Initiating a run is the Runner’s declaration to begin a run. Once a run is initiated, each step of the run is resolved in order.

Making a run refers to the initiation of a run through a basic action or card ability.

**Related**: Abilities, Action, Click, Run, Timing Structures.

# Install

The action of placing an agenda, asset, ice, upgrade, hardware, program, or resource card into the play area. Events, operations, and identity cards are never installed. The Runner installs cards in their rig, the Corp in, in the root of, or protecting their servers.

During the Corp’s action phase, they can spend <span class="nric-grey click"></span> to install a single ice, agenda, asset, or upgrade from HQ. During the Runner’s action phase, they can spend <span class="nric-grey click"></span> to install a single program, hardware, or resource from their grip. Card abilities can also initiate install effects.

To install a card, follow these steps:

1. Choose a card to install and declare the install effect.
- The Runner always reveals the card to be installed.
- The Corp does not reveal the card to be installed.

<ol class="custom-ol" style="--start: 2;">
<li>Choose and declare the install destination appropriate to the card that will be installed, including any host relationships, if applicable.
</li>
</ol>
- Unless stated otherwise, Runner cards have predetermined locations in the rig in which they are installed: resources in the resource row, hardware in the hardware row, and programs in the program row.
- Unless stated otherwise, the install destination for a Corp
card is always in or protecting a specific server, or in the
root of a central server if installing an upgrade.
<ol class="custom-ol" style="--start: 3;">
<li>Trash like cards.
</li>
</ol>
- When installing a program, the Runner may first trash any number of programs already installed. They must do so if installing the new program would exceed their memory limit.
- When installing a card in or in the root of a server, the Corp may first trash any other cards already installed in the destination server. If the card is an asset or agenda, the Corp must trash any assets or agendas from that server.
- When installing ice, the Corp may first trash any other ice already installed protecting the destination server in order to reduce the install cost.
- If the Corp trashes any cards during an install, they are placed in Archives faceup if they were rezzed and facedown if they were unrezzed.
<ol class="custom-ol" style="--start: 4;">
<li>Pay the install cost.
</li>
</ol>
- The install cost of a Runner card is indicated in the top left corner of the card. However, if that card is installed facedown, the install cost is 0.
- The install cost of ice is one credit for each ice already installed protecting the destination server.
- If a card has an install cost of X, the value for X is chosen by the player according to any stipulations written on the card.
<ol class="custom-ol" style="--start: 5;">
<li>Place the card into the play area in the chosen destination. (“When installed...” conditionals meet their trigger conditions, including those on the installed card).
</li>
</ol>
- Corp cards are installed facedown, unrezzed, and are inactive until rezzed. The Corp can look at their unrezzed cards at any time.
- Ice is always installed in the outermost position in front of the destination server.
- Runner cards are installed faceup, active.

The Corp cannot choose to destroy a server while installing cards. By having a server to install a card into, that server by definition exists. Even if all the other cards installed in or protecting the server are trashed during the resolution of the install effect, the server still exists and is not considered a new server once the new card has been installed.

The Corp must keep the order of installs clear to the Runner. Cards in servers cannot be rearranged unless instructed by a card ability. To organize this hidden information for both players, it is important that the Corp observes the following rules for card orientation:

- Agendas, assets, and upgrades are always installed in a vertical orientation.
- Ice is always installed in a horizontal orientation.

## Installing Multiple Cards

Whenever multiple cards are installed by the same effect, those cards are chosen and installed one at a time. Install effects are an exception to the batch effect rule; if a single install effect would install more than one card, then those cards are chosen and installed one at a time.

{: .note-title }
> Example
>
> The Runner uses Mass Install to install three programs. The Runner can install Dhegdheer first, and then host one of the other two programs on Dhegdheer in order to reduce the install cost.

**Related**: Abilities, Action, Action Phase, Active, Agenda, Archives, Asset, Batch Effect, Choosing Cards, Corp, Event, Facedown, Faceup, Hardware, Ice, Identity, In a Server, Inactive, Information, Install Cost, Memory Limit, Operation, Program, Protecting a Server, Resource, Reveal, Rig, Root, Server, Trash, Unrezzed, Upgrade.

# Jack Out

Jacking out is the process by which a Runner voluntarily ends a run while approaching a piece of ice or an attacked server. If the Runner decides to jack out, they end their run and, under most circumstances, the run is considered unsuccessful. The Runner cannot jack out the first time they approach a piece of ice during a run.

**Related**: Approach, Attacked Server, Ice, Run, Runner, Timing Structures.

# Link

Link <span class="nric-grey link"></span> is a value that increases the Runner’s link strength during a trace. Link is always used with a quantity, such as **1** <span class="nric-grey link"></span>, which means “1 link.”

**Related**: Link Strength, Runner, Trace.

# Link Strength

The Runner’s total strength during a trace, calculated as the sum of their link plus the amount of credits the Runner spends on the trace.

**Related**: Link, Runner, Trace.

# Maximum Hand Size

The maximum number of cards a player can have in their hand during their discard phase. Both the Corp and the Runner begin the game with a maximum hand size of five cards, but
card effects can increase or decrease this limit.

**Related**: Corp, Discard, Discard Phase, Runner.

# Memory Cost

The number of MU that a program takes up while installed. For the purposes of card abilities, a program’s memory cost is not considered an additional cost.

{: .note-title }
> Example
>
> The Runner plays a Test Run with no free MU. They will have to trash a program to make room for the program being installed, since the memory cost of that program is not ignored.

**Related**: Additional, Cost, Install, Memory Limit, Memory Unit (MU), Program.

# Memory Limit

The sum total of memory units the Runner has for installed programs, regardless of the number of installed programs. The Runner begins the game with a memory limit of 4, provided by the Runner’s four starting MU. Card effects can modify the Runner’s memory limit.

If installing a program would increase the total MU cost of the Runner’s installed programs over their memory limit, they must trash installed programs until the total MU cost including the new program will not exceed their memory limit. If the total MU cost of the Runner’s installed programs ever exceeds their memory limit, they must trash installed programs until the total MU cost no longer exceeds their memory limit.

**Related**: Install, Memory Cost, Memory Unit (MU), Program, Runner, Trash.

# Memory Unit (MU)

A memory unit (MU) is a unit of space available to the Runner to install programs. The Runner starts the game with four MU. Memory units always appear with a quantity, such as **+**<span class="nric-grey mu2"></span>, which means “plus 2 memory units.”

**Related**: Install, Memory Cost, Memory Limit, Program, Runner.

# Mulligan

The act of drawing a new hand at the start of the game.

After drawing starting hands, the Corp may choose to take a mulligan by shuffling their hand back into their deck and then drawing a new starting hand. After the Corp decides whether to mulligan, the Runner decides whether to mulligan as well.

If a player takes a mulligan, they must keep the second hand as their starting hand.

**Related**: Corp, Grip, Headquarters (HQ), Research and Development (R&D), Runner, Stack.

# “Must”

If a card ability states that a player “must” do something, then that player is prohibited from deliberately making a choice without the intention of resolving that choice. That player is forced to make any decisions necessary to satisfy the requirement, even if it requires the use of other card abilities.

{: .note-title }
> Example
>
> The Runner has an Imp and a Scrubber installed and accesses Mumbad Virtual Tour. If the Runner only has **4**<span class="nric-grey credit"></span>, they must still choose to either spend a counter from Imp to trash Mumbad Virtual Tour if they are able to do so or spend recurring credits on Scrubber to help pay the trash cost of the Mumbad Virtual Tour.

If the “must” ability presents a player with a choice between two or more effects, that player must choose an effect that can be fully resolved. If none of the choices can be fully resolved, then the “must” ability does nothing.

{: .note-title }
> Example
>
> If the first subroutine on Fairchild 2.0 resolves while the Runner has no installed cards but **3**<span class="nric-grey credit"></span>, then the Runner must choose to lose **2**<span class="nric-grey credit"></span>. When the second subroutine on Fairchild 2.0 resolves, the Runner can neither lose 2< nor trash an installed card, so nothing happens.

Prevent/avoid abilities do not invalidate a choice made to satisfy a “must” ability. As long as a player makes the necessary choices for a “must” ability, the actual resolution of the ability can still be interrupted and even changed or prevented by a prevent/ avoid ability.

{: .note-title }
> Example
>
> If the Runner encounters a Data Raven, they must choose to either take a tag or end the run. The Runner can choose to take the tag, then avoid the tag with a Forger. This does not cause the run to end, as the decision to take the tag has already been made.

A singular “must” ability cannot force a player to pay an additional cost they wish to decline, but a player cannot avoid choosing a fully resolvable effect from among multiple options in a “must” ability by declining to pay the additional cost for one of those choices.

{: .note-title }
> Example
>
> If Service Outage is active and the Runner has Always Be Running installed, the Runner can decline to pay the additional **1**<span class="nric-grey credit"></span> to make a run with their first <span class="nric-grey click"></span> thus satisfying the “must” of Always Be Running and allowing them to take the rest of their turn normally. However, if a Runner plays a Forged Activation Orders on an unrezzed Archer, the Corporation cannot choose to rez the Archer but decline to forfeit an agenda; the Corp must either pay **4**<span class="nric-grey credit"></span> and forfeit an agenda to rez the Archer or trash the Archer.

**Related**: Abilities, Avoid, Prevent.

# Operation

Operations represent singular occurrences and are always trashed after being played.

For <span class="nric-grey click"></span>, the Corp plays an operation from HQ by paying its play cost. When played, an operation’s abilities as listed in its text box are resolved. Then, the operation is trashed. Operations are never installed.

**Related**: Headquarters (HQ), Install, Play, Play Cost, Trash.

# Ordinal Events

When an ability refers to a specific ordinal instance of something happening (e.g. “the first time”, “the second time”, etc.), it refers to that instance and only that instance. If a replacement or prevent ability happens, the game still counts it toward the number of times the replaced or prevented event has occurred.

{: .note-title }
> Example
>
> If the first instance of net damage during a run is prevented by the Runner using Feedback Filter, or if it is replaced with Tori Hanzo’s own effect, the Tori Hanzo cannot trigger on any other instances of net damage for the remainder of the run.

**Related**: Abilities, Avoid, Prevent, Replacement Effect.

# Paid Ability Window

A paid ability window is an opportunity during the game for players to use paid abilities. Many paid ability windows also allow the Corp to rez cards or score agendas.

Whenever a paid ability window opens, the player who is currently taking their turn gets the first opportunity to act. That player can use as many paid abilities, rez as many cards,
and/or score as many agendas as they wish in the order of their choosing. When that player is finished, the other player gets the opportunity to act. When that player is finished, the first player gets the opportunity to act once again, and so on.

After both players have had at least one opportunity to act and a player declines to act, then the paid ability window closes and players cannot trigger more abilities, rez more cards, or score more agendas until the next opportunity to do so.

Consult the timing structures at the back of the Rules Reference to see all the paid ability windows that open during the game.

<table class="sml-table">
      <tr>
      <td><span class="nric-grey paid"></span></td>
      <td>This symbol indicates a paid ability window.</td>
       </tr> 
       <tr>
      <td><span class="nric-grey rez"></span></td>
      <td>This symbol indicates that the Corp can rez non-ice cards during this paid ability window.</td>
       </tr>
       <tr>
      <td><span class="nric-grey agenda "></span></td>
      <td>This symbol indicates that the Corp can score agendas during this paid ability window.</td>
       </tr> 
  </table>

**Related**: Agenda, Corp, Rez, Runner, Score, Timing Structures.

# Pass

The Runner passes a piece of ice at step (4) in the Timing Structure of a Run. This usually occurs when an encounter ends after the resolution of any unbroken subroutines, but it can occur separately, such as when an approached ice is not rezzed or when the Runner bypasses a piece of ice.

**Related**: Approach, Bypass, Encounter, Ice, Rezzed, Run, Runner, Subroutine, Timing Structures, Unrezzed.

# Play

The action of placing an operation or event card onto the table, resolving its effects, and trashing it.

During the Corp’s action phase, they can spend <span class="nric-grey click"></span> to play a single operation from HQ. During the Runner’s action phase, they can spend <span class="nric-grey click"></span> to play a single event from their grip. Card abilities can also initiate play effects.

To play an operation or event, follow these steps:

1. Choose and reveal a card to play, and declare the play effect.
1. Pay the play cost.
- The play cost of an operation/event is indicated in the top left corner of the card.
- If a card has a play cost of X, the value for X is chosen by the player according to any stipulations written on the card.
<ol class="custom-ol" style="--start: 3;">
<li>Place the card faceup into the play area. It becomes active. (“When played...” conditionals meet their trigger conditions).</li>
<li>Resolve the effects of the card.</li>
</ol>
- Operations and events can create lasting effects. Once those effects exist, they become independent of the source operation or event and the card is considered fully resolved and ready to be trashed.
- An operation or event that initiates a run remains active in the play area for the duration of that run. It is not considered fully resolved until the run is completed and “When the run ends...” effects on the card are resolved.

{: .note-title }
> Example
>
> Test Run has an ability that will trigger at the end of the turn, but once the program is installed and the stack is shuffled, Test Run is considered fully resolved even though the exact timing of its end of turn ability may come later.
<ol class="custom-ol" style="--start: 5;">
<li>Trash the card (“After you resolve...” conditionals meet their trigger conditions).
</li>
</ol>

## Playing Multiple Cards

Whenever multiple cards are played by the same effect, those cards are chosen and played one at a time. Play effects are an exception to the batch effect rule. If a single play effect would play more than one operation or event, then those cards are chosen and played one at a time.

{: .note-title }
> Example
>
> The Corp uses Subcontract to play two operations, including Hedge Fund. The Corp can use the credits gained from Hedge Fund to pay for the second operation.

**Related**: Abilities, Action, Action Phase, Active, Batch Effects, Corp, Event, Faceup, Grip, Headquarters (HQ), Operation, Play Cost, Reveal, Runner, Timing Structures, Trash.

# Prevent

Prevent (and avoid) effects are the only effects which can disrupt another effect. A prevent effect states what it is preventing and an effect that is prevented is not resolved. Prevent effects can only be triggered whenever the effect they are avoiding is in the “triggered” state.

Prevent effects take priority over conditional abilities that would trigger from whatever is being prevented, except when a conditional ability uses the word “additional.” An “additional” conditional ability occurs simultaneously with the trigger condition and can be prevented along with the trigger condition.

**Related**: Abilities, “Additional”, Avoid.

# Program

Programs are digital tools at the Runner’s disposal, primarily used as a means of intrusion. The Runner installs programs in their rig by paying an install cost.

Programs are the only card type that have a memory cost. The Runner cannot have programs installed that have a combined memory cost greater than their memory limit. When installing a new program, the Runner may trash any number of programs already installed.

**Related**: Ice, Icebreaker, Install, Install Cost, Memory Cost, Memory Limit, Memory Unit (MU), Rig, Run, Subroutine, Subtype.

# Protecting a Server

Ice is installed in a horizontal orientation protecting a server, in front of the cards that are in that server. Agendas, assets, and upgrades are installed in servers or the root of a central server and not installed protecting servers.

**Related**: Agenda, Asset, Ice, Install, Server, Upgrade.

# Purge

The act of removing all virus counters hosted on cards, returning them to the bank. During the Corp’s action phase, they can spend <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span> as an action to purge virus counters. Card abilities can also initiate a purge effect. The Corp can always use a purge effect, even if there are no virus counters currently hosted on any cards.

**Related**: Abilities, Action, Action Phase, Bank, Corp, Host, Virus Counter.

# Replacement Effects

An ability that uses the word “instead” is a replacement effect. Once an effect has been replaced with a new one, no other effects can be triggered off the original effect, regardless if they are regular effects or additional replacement effects.

{: .note-title }
> Example
>
> The Runner cannot use two Bank Jobs during the same run. When the run is successful, the Runner may either access cards or use the ability of a Bank Job. Using Bank Job replaces accessing cards, so once the Runner triggers one of the Bank Jobs, they cannot trigger the other.

**Related**: Abilities.

# Research and Development (R&D)

This is the Corp’s draw deck. R&D is kept facedown within reach of the Corp. Cards in R&D are inactive.

When the Runner accesses multiple cards from R&D, the cards are accessed one at a time, and do not return to R&D until the Runner is finished accessing. The Runner cannot choose to access the cards in R&D out of order. The Runner can intersperse accessing cards from R&D with any upgrades installed in the root of R&D.

The number of cards in R&D is open information, though the qualities of each card (faction, name, types, subtypes, values, abilities, artwork etc.) are hidden information.

**Related**: Accessing, Corp, Facedown, Faceup, Faction, Inactive, Information, Install, Root, Runner, Subtype, Upgrade

# Resource

Resources are a wide variety of connections and skills that aid the Runner. The Runner installs resources in their rig by paying an install cost. There is no limit to the number of resources the Runner can install in their rig.

While the Runner is tagged, the Corp may spend <span class="nric-grey click"></span> and **2**<span class="nric-grey credit"></span> to trash an installed resource.

**Related**: Corp, Install, Install Cost, Rig, Tagged, Trash.

# Reveal

Some effects reveal one or more cards. Only uninstalled cards can be revealed. A revealed card is shown to all players, and then returned to its previous state. If multiple cards are revealed by one effect, they are considered to be revealed simultaneously.

**Related**: Archives, Corp, Discard, Facedown, Faceup, Information, Runner, Trash.

# Rez

The process by which the Corp turns an unrezzed card faceup to make it active. In order to rez an unrezzed card, the Corp must pay its rez cost, though rezzing a card does not cost <span class="nric-grey click"></span>. Assets and upgrades can be rezzed during a variety of timing structures over the course of the game, including at the beginning and end of each turn, before and after each action, and during runs. Ice can only be rezzed when the Runner approaches it during a run. Agendas are never rezzed. See the timing structures in Rules Reference for a full list of opportunities to rez cards.

**Related**: Action, Active, Agenda, Approach, Asset, Corp, Faceup, Ice, Rez Cost, Run, Runner, Timing Structures, Unrezzed, Upgrade.

# Rezzed

The state in which a Corp card is installed, faceup, and active. The opposite of unrezzed. Corp cards are installed unrezzed and can become rezzed by rezzing them. A rezzed card can sometimes be derezzed back into an unrezzed state by card abilities.

**Related**: Active, Derez, Faceup, Install, Rez, Unrezzed.

# Rig

Where the Runner installs their cards. The rig is separated into four rows: one for programs, one for hardware, one for resources, and one for facedown Runner cards.

With the exception of facedown Runner cards, cards in the rig are active.

**Related**: Active, Facedown, Hardware, Inactive, Install, Program, Resource, Runner.

# Root

The area of a central server where upgrades for the server are installed. When an upgrade is installed in the root, it should be placed below the server. If a root has no cards installed in it, it is considered to be empty.

**Related**: Corp, Install, Server, Upgrade.

# Run

A run is a Runner’s attack on a server that consists of seven steps that are resolved in the following order: 

1. Initiation.
1. Approach Ice.
1. Encounter Ice.
1. Pass Ice.
1. Approach Server
1. The Run Ends
1. The Run Ends Unsuccessfully.

## Step 1: Initiation

The Runner initiates a run and declares the attacked server. The Runner then gains **1**<span class="nric-grey credit"></span> to spend during the run for each bad publicity the Corp has.

If the attacked server has at least one piece of ice protecting it,
the Runner proceeds to step **2**, Approach Ice; if the attacked
server is not protected by ice, the Runners moves to step **4**, Pass Ice.

## Step 2: Approach Ice

The Runner approaches the next piece of ice protecting the attacked server, going from the outermost piece of ice to the innermost piece.

If this is not the first time that the Runner has approached a piece of ice during this run, then the Runner may choose to either jack out (moving to step **7**, The Run Ends Unsuccessfully) or continue the run. However, if this is the first time the Runner has approached a piece of ice during this run, the Runner cannot jack out.

If the run continues and the approached ice is unrezzed, the Corp has the opportunity to rez that ice. If the Corp does so or if the ice was already rezzed, the Runner goes to step **3** of the run, Encountering Ice; if the ice remains unrezzed, the Runner proceeds to step **4**, Pass Ice.

## Step 3: Encounter Ice

The Runner encounters the rezzed piece of ice. During this step, the Runner can break subroutines on the ice (often by using icebreaker programs). Broken subroutines do not resolve their abilities; unbroken subroutines trigger and resolve one by one in order.

If the run ends during this step, the encounter also ends, at which point the Runner goes to step **7**, The Run Ends Unsuccessfully; otherwise, the encounter ends and the Runner continues to step **4**, Pass Ice.

## Step 4: Pass Ice

The Runner passes the piece of ice. If there is another piece of ice protecting the server in a position more inward than the ice just passed, the Runner proceeds to step **2** again; if there are no more pieces of ice protecting the server in positions more inward than the ice just passed, the Runner continues to step **5** of the run, Approach Server.

## Step 5: Approach Server

The Runner approaches the attacked server. The Runner may either jack out, moving to step **7** of the run, or continue the run, at which point the run is successful.

If the run is successful, the Runner determines the number of cards that they will access from the attacked server, then accesses that many cards from the attacked server one at a time.

If an accessed card has a trash cost, the Runner may pay that cost to trash the card; if an accessed card is an agenda, the Runner must steal it; if the accessed card does not have a trash cost and is not an agenda, the Runner sets the card aside.

Once the Runner has accessed a total of cards equal to the number determined before accessing, the cards that were set aside are returned to the server in their previous states and the Runner continues to step **6**, The Run Ends.

## Step 6: The Run Ends

The Runner loses unspent bad publicity credits and the run ends.

## Step 7: The Run Ends Unsuccessfully

The Runner loses unspent bad publicity credits and the run ends unsuccessfully.

**Related**: Accessing, Agenda, Approach, Asset, Bad Publicity, Corp, Encounter, Ice, Icebreaker, “If successful...”, Initiate vs. Make a Run, Jack Out, Protecting a Server, Rez, Runner, Server, Steal, Strength, Subroutine, Timing Structures, Trash, Trash Cost.

# Runner

One of the two sides available to the player in Android: Netrunner. The opponent of the Corp. Referred to as “the Runner” on card text.

**Related**: Corp, Runner Cards

## Runner Cards

There are five types of Runner cards: events, hardware, identities, programs, and resources. All cards except the identity card are shuffled into the Runner’s deck at the beginning of the game. Faceup Runner cards are always active while installed; facedown Runner cards are inactive while installed.

**Related**: Active, Event, Facedown, Hardware, Identity, Inactive, Install, Program, Resource.

# Score

Scoring is the act of the Corp adding an agenda to their score area.

When the number of advancement tokens on an agenda is equal to or higher than its advancement requirement, the agenda is fully advanced and the Corp can score it.

To score an agenda, the Corp turns it faceup (if it is facedown) and places it in their score area, resolving any conditional “When you score...” abilities. While scoring an agenda does not cost <span class="nric-grey click"></span> and is not an action, an agenda can only be scored during a scoring paid ability window <span class="nric-grey agenda "></span>

An agenda sometimes has an ability that rewards advancement beyond the agenda’s advancement requirement, or an ability that encourages the Corp to delay scoring the agenda. The Corp is not required to score an agenda immediately upon satisfying its advancement requirement. They may instead advance it more or wait for a more opportune time to score it.

Advancement tokens are removed from an agenda when it is scored.

**Related**: Abilities, Action, Advance, Advancement Requirement, Agenda, Agenda Points, Bank, Click, Corp, Facedown, Faceup, Score Area, Scored Points.

# Score Area

Each player has a score area that holds their scored or stolen agendas. While an agenda is in the Corp’s score area, it is active and adds its agenda points to their score. While an agenda is in the Runner’s score area, it adds its agenda points to their score.

Adding a card to a score area is not the same as scoring or stealing an agenda.

**Related**: Active, Agenda, Agenda Points, Corp, Runner, Score, Steal.

# Scored Points

The total number of agenda points a player has in their score area.

**Related**: Agenda, Agenda Points, Corp, Runner, Score, Score Area, Steal.

# Search

If a player is searching for a card, they must find the card, if able. If a player is unable to fulfill the condition of the search, then nothing happens, but the deck is always reshuffled.

Once a player completes a search (whether a card is found or not), any found cards are set aside and the deck must be immediately reshuffled before continuing to resolve any remaining effects from the ability that initiated the search. The shuffling takes precedence over any installing or playing of the searched card as well as any chain reactions that occur as a result of the search.

{: .note-title }
> Example
>
> The Corp is playing Near-Earth Hub and uses the ability on Tech Startup to search their deck for an asset and install it. After finding the asset, R&D must be immediately shuffled before installing the asset or triggering Near-Earth Hub.

**Related**: Abilities, Chain Reactions, Install, Play, Research, Stack.

# Self-Referential Language

If the card title referenced on a card matches the title of that card, and the reference is not plural and/or does not include an additional modifier (e.g., “other copies” or “all”), then the card title only refers to that copy of the card, and not to any other copies of it.

If a card copies the text of another card, and the copied text includes a self-reference, the copied text does not function unless it explicitly says so.

{: .note-title }
> Example
>
> The Runner uses Media Blitz to copy the text of a Private Security Force in the Runner’s score area. Because the self-reference in Private Security Force does not match the title of the card Media Blitz, the ability has no effect.

**Related**: Abilities.

# Server

Servers are where the Corp installs their cards. There are two types of servers: central servers and remote servers. Servers can have cards in or protecting them which are active while rezzed and inactive while unrezzed. Generally, assets, agendas, and upgrades are installed in servers, while ice are installed protecting server.

## Central Servers

The Corp has three central servers at all times: Headquarters (HQ), Research and Development (R&D), and Archives. Ice can be installed protecting each of the central servers. Assets and agendas cannot be installed in central servers. Instead, the cards in the Corp’s hand are the cards in HQ, the cards in the Corp’s deck are the cards in R&D, and the cards in the Corp’s trash pile are the cards in Archives.

Each central server also has a root where upgrades that affect that central server can be installed.

## Remote Servers

The Corp has no remote servers at the beginning of the game. The Corp creates new remote servers by installing cards into or protecting them. There is no limit to the number of remote servers the Corp can have at any given time.

A remote server can have any number of upgrades installed into it, but only either one asset or one agenda can be installed in a remote server at any given time.

If there are no cards installed in or protecting a remote server, then the server immediately ceases to exist. If a server ceases to exist during a run, then the run ends after any currently open paid ability window closes. Unless the run has already been declared either successful or unsuccessful, it is not considered either.

**Related**: Active, Agena, Archives, Asset, Corp, Headquarters (HQ), Ice, In a Server, Inactive, Install, Paid Ability Windows, Protecting a Server, Research and Development (R&D), Rezzed, Root, Run, Unrezzed, Upgrade.

# Simultaneous Effects

When one or more abilities have the same timing or meet their trigger conditions at the same time, first apply all the constant abilities, then resolve all the conditional abilities. For the conditional abilities, first the player who is currently taking their turn chooses and triggers their abilities one at a time until all of them have triggered or otherwise failed to resolve. After all of the current player’s conditional abilities have triggered, then the other player chooses and triggers their abilities one at a time until all of them have triggered or otherwise failed to resolve. A player can choose to trigger an optional conditional ability before a required conditional ability if they both have the same trigger condition.

If more than one constant ability attempts to modify the same card or value, add up all the modifiers and use the sum or difference to determine the end result.

**Related**: Abilities.

# Stack

This is the Runner’s draw deck. The stack is kept facedown within reach of the Runner. Cards in the stack are inactive.

**Related**: Facedown, Inactive, Runner.

# Steal

Stealing is the act of the Runner adding an accessed agenda to their score area.

If the Runner accesses an agenda, they steal it and place it faceup in their score area, resolving any conditional abilities on the agenda that use the language “When you steal...”. The Runner cannot decline to steal agendas they access, unless they cannot or do not wish to pay an additional cost that is applied to stealing that agenda.

Advancement tokens are removed from an agenda whenever it is stolen.

**Related**: Abilities, Accessing, Additional, Agenda, Agenda Points, Bank, Cost, Faceup, Runner, Score Area, Scored Points.

# Strength

Strength is an attribute found on the bottom left corner of icebreakers and ice. An icebreaker can only interact with ice that has equal or lower strength than the icebreaker. Both ice and icebreakers can have negative strength. 

**Related**: Ice, Icebreaker.

# Subroutine

Subroutines <span class="nric-grey subroutine "></span> are required conditional abilities of a piece of ice. Subroutines can be broken during step (3.1) of a run, in which case they do not resolve. If the Runner encounters a piece of rezzed ice and does not or cannot break its subroutines, the unbroken subroutines trigger and resolve one by one in order. Unless specified otherwise, the Corp always chooses the effects of a subroutine, when necessary.

{: .note-title }
> Example
>
> Ichi 1.0 has “ <span class="nric-grey subroutine "></span> Trash 1 program.” If this subroutine triggers, then the Corp chooses and trashes one of the Runner’s installed programs.

**Related**: Abilities, Corp, Encounter, Ice, Rezzed, Run, Runner, Timing Structures.

# Subtype

A card descriptor. A card has all of its subtypes while it is inactive, with the exception of facedown installed Runner cards. Gaining and losing subtypes are tracked as a running total, but having a subtype is a binary state.

{: .note-title }
> Example
>
> The Runner plays Tinkering on a Wendigo with an advancement token on it. Wendigo has two instances of Code Gate, one printed and one from Tinkering, and has lost one instance of Code Gate from its own ability, thus it is still considered to be a Code Gate.

**Related**: Active, Inactive.

# “Swap”

An exchange of two named things or groups of things (cards, counters, tokens, etc.). When they are swapped, both exchange places simultaneously. A swapped card is not considered installed or uninstalled by default, unless explicitly stated, or it is swapped with another card in the opposite state. If a swapped card becomes uninstalled by the swap, any hosted items are trashed.

**Related**: Host, Trash, Uninstall.

# Tag

Certain card effects result in a tag being placed on the Runner. As long as the Runner has at least one tag, they are considered to be tagged.

**Related**: Abilities, Runner, Tagged.

# Tagged

A state which describes a Runner when they have one or more tags. Certain card effects can trigger off of the Runner being tagged.

While the Runner is tagged, the Corp may, as an action, spend <span class="nric-grey click"></span> and **2**<span class="nric-grey credit"></span> to trash one of the Runner’s resources, and the Runner may, as an action, spend <span class="nric-grey click"></span> and **2**<span class="nric-grey credit"></span> to remove one tag, returning it to the bank.

**Related**: Abilities, Action, Bank, Corp, Resource, Runner, Tag, Trash.

# Trace

Some card abilities initiate a trace on the Runner. Traces are marked by the language “**Trace X**” on a card, with **X** equaling the base trace strength of the trace. Traces pit the Corp’s trace strength against the Runner’s link strength, both of which can be increased by spending credits.

The Corp acts first during a trace, openly spending any number of credits to increase their trace strength by one point for each credit spent.

After the Corp spends their credits, the Runner has the opportunity to openly spend credits to increase their link strength. The Runner’s base link strength is equal to the number of links <span class="nric-grey link"></span> they have in play. The Runner increases their link strength by one point for each credit spent.

After the Runner finishes increasing their link strength, it is compared to the Corp’s trace strength. If the trace strength exceeds the link strength, the trace is successful and any “If
successful” effects associated with the trace are resolved. If the link strength is equal to or greater than the trace strength, then the trace is unsuccessful, and any “If unsuccessful” effects associated with the trace are resolved.

**Related**: Abilities, Corp, Credit, Link, Link Strength, Runner, Trash Strength.

# Trace Strength

The Corp’s total strength during a trace, calculated as the sum of the base strength on the card initiating the trace and the amount of credits the Corp spends on the trace.

**Related**: Corp, Credit, Trace.

# Trash

Trashing is the act of moving a card to its owner’s trash pile. Trashing can also refer to the Runner paying the trash cost of an accessed card to put it into Archives. Trashing cards that “cannot normally be trashed” only refers to trashing cards that do not have a trash cost. A card that is already in Archives cannot be trashed.

A trashed card is not considered to have been discarded, and vice versa. Cards that prevent a card from being trashed cannot prevent a card from being discarded.

<span class="nric-grey trash"></span> This symbol stands for trash. It is used as a self-referentialtrigger cost in a card text, such as “<span class="nric-grey trash"></span> Draw 2 cards,” which means “trash this card to draw 2 cards.”

**Related**: Archives, Corp, Discard, Heap, Prevent, Runner, Trash Cost

# Trash Cost

Primarily found in the lower right corner <span class="nric-grey trash"></span> of assets, upgrades, ice, and operations, a trash cost is an optional cost that the Runner may pay while accessing a card to trash that card.

**Related**: Accessing, Asset, Cost, Ice, Operation, Runner, Trash, Upgrade.

# Turn

A turn is a duration of time during which a player may take actions and receives priority to act during paid ability windows.

The Corp’s turn consists of three phases. During the draw phase, the Corp draws the top card of R&D into HQ; during the action phase, the Corp has <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span> to spend on performing actions; during the discard phase, the Corp discards until the number of cards in HQ is equal to their maximum hand size. Once the Corp’s turn ends, the Runner’s turn begins.

The Runner’s turn consists of two phases. During the action phase, the Runner has <span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span><span class="nric-grey click"></span> to spend on performing actions; during the discard phase, the Runner discards until the number of cards in their grip is equal to their maximum hand size. Once the Runner’s turn ends, the Corp’s turn begins.

**Related**: Action, Action Phase, Archives, Corp, Discard Phase, Draw Phase, Heap, Headquarters (HQ), Maximum Hand Size, Paid Ability Windows, Research and Development (R&D), Runner.

# Uninstall

Whenever an installed card enters HQ, R&D, Archives, the Runner’s grip, stack, or heap, either player’s score area, or is removed from the game, the card has been “uninstalled”.

If a piece of ice is uninstalled during an approach or encounter with that piece of ice, then the ice is immediately passed and the run continues after any currently open paid ability window closes.

If the last card installed in or protecting a remote server is uninstalled, then the server immediately ceases to exist.

Whenever a card is uninstalled, there is no memory of its previous state and it is considered to be a new copy of the card.

**Related**: Approach, Archives, Encounter, Grip, Heap, Headquarters (HQ), Ice, In a Server, Install, Paid Ability Windows, Pass, Protecting a Server, Research and Development (R&D), Run, Server, Stack.

# Unique

Some cards have a unique symbol <span class="nric-grey unique"></span> in front of their title. There can be only one unique card of the same title active at a time. If a card with a unique title becomes active, any other card that shares its title is immediately trashed. This trashing cannot be prevented.

**Related**: Active, Prevent, Trash.

# Unrezzed

The state in which a Corp card is installed, facedown, and inactive. The opposite of rezzed. Corp cards are installed unrezzed and can become rezzed by rezzing them. A rezzed card that is derezzed becomes unrezzed again.

**Related**: Corp, Derez, Facedown, Inactive, Install, Rez, Rezzed.

# Upgrade

Upgrades are improvements to a server that provide the Corp with a wide variety of benefits and bonuses.

The Corp installs upgrades in remote servers or the roots of central servers. Upgrades are the only card type that can be installed in the root of a central server. An upgrade is inactive until it is rezzed by paying credits equal to its rez cost.

An upgrade is installed in a remote server in the same position as an agenda or asset. The Runner should not be able to tell what type of card is installed in a remote server by its position. This is different than installing an upgrade in a central server, where it is always installed in the root.

There is no limit to the number of upgrades that can be installed in a server or a root. When the Runner accesses an upgrade, they can trash it by paying credits equal to its trash cost.

**Related**: Accessing, Active, Agenda, Archives, Asset, Corp, Credit, Headquarters (HQ), Inactive, Install, Research and Development (R&D), Rez, Rez Cost, Rezzed, Root, Runner, Server, Trash, Trash Cost.

# Virus Counter

A token that is typically hosted on virus-related cards. When virus counters are purged, all virus counters are returned to the token bank.

**Related**: Bank, Purge.

<div class="nav-buttons">
  <a href="/docs/deckbuilding/influence" class="nav-button prev" aria-label="Previous page">
    <div class="nav-item"></div>
  </a>
  <a href="/docs/glossary/actions" class="nav-button next" aria-label="Next page">
    <div class="nav-item"></div>
  </a>
</div>

{: .no_toc }
