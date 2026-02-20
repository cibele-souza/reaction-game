# REFLEX // Reaction Timer

A browser-based reaction time trainer with a 3D animated interface built using Three.js.

## How to Play

1. Click **START** (or press Space/Enter)
2. Wait for the 3D shape to turn **green**
3. Click as fast as you can — your reaction time is recorded in milliseconds

Clicking too early triggers a **false start** penalty with a red alert on the shape.

## Features

- 3D icosahedron with dynamic lighting that changes color by game state (amber → green → blue → red)
- Tracks average, best time, and session history with color-coded attempt dots
- Performance rankings: Warming Up / Average / Pro / Elite / Superhuman

## Stack

Single HTML file — no build step required. Dependencies: [Three.js r128](https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js) (CDN) and Google Fonts.
