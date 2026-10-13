# Launch

<p align="center"><img src="media/gameplay/2-2-over-the-fence.gif" width="270" alt="A wooden toy cat is lobbed over a fence and lands in a basket"></p>

**Launch** is a first-person throwing game for iPhone where the phone *is* your hand. Hold it like the object, swing, and the game reads your real throw from the motion sensors: speed, angle and spin. Toss a ping-pong ball into a cup, lob a jointed wooden toy cat over a fence (it rights itself mid-air and lands on its feet), and throw knives at a spinning carnival wheel, all inside a hand-painted *Clockwork Carnival* booth.

This repo is the public window into the game's development. The source is private.

## Latest builds

<!-- builds:start -->
- 2026-10-13 · build 2 · Art: 13 new models (basket, booth_post, bulb +10), cat, prop textures, style exploration +2 · Levels · Throwables · Motion controls · Engine · UI · Art pipeline · Project · Docs — 2 commits

[Full build log →](BUILDLOG.md)
<!-- builds:end -->

Each push to the game's main branch adds a line automatically, written from which *areas* changed (art, levels, engine…), never from commit messages.

## Gameplay

The clips below are **scripted throws**: real committed builds running in the iOS Simulator, driven through the game's own swipe-to-throw input with aim and speed picked by the game's physics checker. On a phone you throw with your arm instead. Click a GIF for the full-quality MP4.

| 1-2 The cup | 1-3 Side ramps | 2-2 Over the fence | 2-4 Hole & kick *(setup only)* |
|:---:|:---:|:---:|:---:|
| [<img src="media/gameplay/1-2-the-cup.gif" width="170">](media/gameplay/1-2-the-cup.mp4) | [<img src="media/gameplay/1-3-side-ramps.gif" width="170">](media/gameplay/1-3-side-ramps.mp4) | [<img src="media/gameplay/2-2-over-the-fence.gif" width="170">](media/gameplay/2-2-over-the-fence.mp4) | [<img src="media/gameplay/2-4-hole-and-kick-setup.gif" width="170">](media/gameplay/2-4-hole-and-kick-setup.mp4) |
| A soft underhand toss | Land on a ramp, roll in | The cat rights itself and lands | Through the hole, then slow-mo: *tap to kick* |

*2-4 stops at the kick prompt: the kick needs split-second timing by the player, which the capture rig can't script yet.*

## Progress timelapse

<p align="center"><img src="media/timelapse/timelapse.gif" width="270" alt="The same level, captured at the end of each day of development"></p>

The same scene (1-2 *The cup*), built from the last commit of each active day and stamped with its date. It gains a frame every day there's work.

## Cast & art

### Finding the look
Three art directions were explored for the same scene. **Clockwork Carnival** (right) won.

<img src="media/art/style-exploration.jpg" width="100%" alt="Three style concepts: Pocket Toybox, Kinetic Comic, Clockwork Carnival">

### The cat: concept → turnaround → 3D model
<img src="media/art/cat-concept-to-model.jpg" width="100%" alt="The approved cat concept and side view, then renders of the 3D model">
<img src="media/art/cat-turnaround.jpg" width="100%" alt="Front, back, left and right turnaround of the cat">

<details><summary>Concept candidates that didn't make it</summary>

<img src="media/art/cat-concept-candidates.jpg" width="100%" alt="Two cat concept candidates">
</details>

### Shipped models
Every prop as it ships in the game, rendered by SceneKit straight from the build's `.usdz` files.

<img src="media/reels/models.gif" width="600" alt="Turntable of the cat, cup, basket, table, lantern and crate">

### The booth: concept vs. game
<img src="media/art/booth-concept-vs-game.jpg" width="100%" alt="Booth concept painting next to the in-game view">

<details><summary>Booth concept candidates</summary>

<img src="media/art/booth-concept-candidates.jpg" width="100%" alt="Two booth concept candidates">
</details>

### Textures
<img src="media/art/textures.jpg" width="100%" alt="Tabletop, backdrop, cup and basket wraps, felt, wood, floorboards, canvas and panel textures">

## Devlog

Longer posts about how things were built: see **[DEVLOG.md](DEVLOG.md)**.

---

© 2026 Marco Battiato. **All rights reserved.** Everything here (images, video, text) is shown for viewing only. No licence is granted to copy, modify or redistribute it.
