# AR Birthday Card

Group 39

## About

An augmented reality birthday card for Apsara, made with A-Frame and AR.js. Point a phone or webcam at the Hiro marker and a birthday scene appears on top of it, with a cake, candles, a balloon and a gift. You can tap the balloon and the gift to interact with the card.

## Features

1. **Hiro marker scene:** `<a-marker preset="hiro">` holds the floor (`a-plane`), a two-layer cake and three candles (`a-cylinder`), three flames (`a-cone`), the balloon (`a-sphere`), the gift and ribbon (`a-box`), and the label "Happy Birthday Apsara!" (`a-text`).
2. **Animation:** the balloon bounces (`position`), the candle flames flicker (`scale`) and the 3D model spins (`rotation`).
3. **3D model:** a present loaded from `models/present.glb` (see [3D Model Credit](#3d-model-credit)).
4. **Interaction:**
   - Tapping the balloon cycles its colour (the workshop `color-changer` component).
   - Tapping the gift shows or hides a surprise message (our own `surprise-toggle` component).
5. **Status banner:** the `marker-status` component changes the banner text and colour when the marker is found (green) or lost (red).
6. **Hosting:** published over HTTPS on GitHub Pages and tested on a phone (see [Live Demo](#live-demo)).

## How to use

1. Open the live link on your phone and allow the camera.
2. Point the rear camera at the [Hiro marker](markers/hiro.png), either printed or shown on another screen.
3. When the banner turns green, tap the balloon to change its colour.
4. Tap the gift to show or hide the surprise message.

## 3D Model Credit

- **Model:** Present
- **Author:** [CreativeTrio](https://poly.pizza/u/CreativeTrio)
- **Licence:** Public Domain (CC0 1.0)
- **Source:** [Poly Pizza](https://poly.pizza/m/LVg3ynJDxa)

## Libraries

- [A-Frame](https://aframe.io/) 1.3.0
- [AR.js](https://github.com/AR-js-org/AR.js) 3.4.5

## Live Demo

The link will be added once GitHub Pages is enabled.

**Tested on:** [DEVICES]
