# Anushka Singh — Cinematic Portfolio Hero

A fullscreen, video-driven hero section for a developer portfolio, built with
Next.js (App Router), React, Three.js, and GSAP.

## What's inside

app/
  layout.jsx        → root layout, loads Fraunces + Inter fonts
  page.jsx           → renders <VideoHero /> with your name/role
  globals.css        → minimal reset
components/
  VideoHero.jsx       → the hero section itself (video, overlay, controls)
  VideoHero.module.css→ design tokens + all hero styling
  CinematicLayer.jsx  → Three.js ambient particle layer (signature visual)
public/
  hero-video.mp4      → your talking-head video (already included)

## Running it locally

npm install
npm run dev
