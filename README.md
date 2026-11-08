# cartoon-short-kit
Audio in, finished vertical cartoon short out. 2D bean-head cards in an inked, painted 3D world
(three.js in headless Chromium, no Remotion and no GPU needed), with a synthesized music bed and SFX.

- `engine/` renderer: world helpers, cards, ink pass, lens blur, grade (`main.js`), painted textures (`paint.js`),
  cast drawing (`roman.js` on top of the Pen library from mromidev/claude-animated-shorts, fetched by setup),
  motion helpers (`motion.js`).
- `example/soldier/` the worked example "The Soldier Who Never Left" (story.js shot plan + audio.py cue table).
- `tools/` setup.sh (new project), timing.py (word timings), render.mjs (frames), sheet.py (contact sheets), finish.sh (encode + QA).

Quick start: `bash tools/setup.sh ~/shorts/my-short && cd ~/shorts/my-short && python3 timing.py voice.mp3 script.txt --out work`
Built on github.com/mromidev/claude-animated-shorts (MIT): toon.ts, look values and readability rules.

# ✂️ Cutout Short Skill

**An AI-powered skill for creating engaging, story-driven 2D cutout animation videos optimized for YouTube Shorts, Instagram Reels, and TikTok.**

## 🚀 Overview

Cutout Short Skill transforms simple ideas into complete animated short-form video production packages. It combines storytelling, character design, scene planning, visual prompts, and animation direction to create engaging content using a 2D cutout animation style.

## ✨ Features

- **Topic Generation:** Discover creative and viral video ideas.
- **Scriptwriting:** Generate engaging, short-form scripts with strong hooks.
- **Character Design:** Create consistent 2D cutout characters.
- **Scene Breakdown:** Divide scripts into structured visual scenes.
- **Image Prompts:** Generate detailed character and background prompts.
- **Animation Prompts:** Define character movements, expressions, and transitions.
- **Camera Direction:** Add cinematic framing and movement.
- **Narration & SFX:** Include voiceover, sound effects, and background music suggestions.
- **YouTube Optimization:** Generate titles, descriptions, and hashtags.

## 🎬 Workflow

1. Choose a topic or concept.
2. Generate an engaging script.
3. Design characters and environments.
4. Break the story into individual scenes.
5. Generate image and animation prompts.
6. Add narration, sound effects, and music.
7. Prepare the final short-form video.

## 🎯 Supported Platforms

- YouTube Shorts
- Instagram Reels
- TikTok

## 🛠️ AI Video Workflows

Designed to support creative workflows using AI tools such as:

- Google Flow
- Veo
- Kling
- Seedance
- Other AI image and video generation tools

## 🎨 Animation Style

- 2D Cutout Animation
- Flat Character Illustrations
- Layered Character Design
- Expressive Facial Animation
- Simple Backgrounds
- Smooth Character Movement

## 📌 Purpose

To simplify animated short-form content creation by turning ideas into structured, production-ready animation workflows.

---

**Built for creators who want to turn ideas into animated stories.**

Developed with creativity and AI by **Mayur Gawade**.
