# Smartroof Construction Ltd — GitHub & Vercel Production Package

This package is pre-configured for **zero-crash static deployment** on **GitHub + Vercel**.
Every asset—including `hero.mp4` (Hero Showreel), `work.mp4` (Roof-Level Inspection Showcase with audio), the official Smartroof 3D logo, all 25 project & video frames, the Three.js 3D roof scenes, GSAP scroll effects, and pre-compiled Tailwind CSS styles—is embedded directly inside `index.html` so no video, image, animation, or text style can ever break or return a `404` error.

## Which Files to Extract & Upload to GitHub

Extract `smartroof-construction-vercel-fixed.zip` and upload the top-level files to the **root** of your GitHub repository:

1. **`index.html`** *(Required — Mandatory)*: The complete, self-contained website entry point.
2. **`vercel.json`** *(Recommended)*: Configures Vercel static routing and headers with zero Node/npm build step.
3. **`README.md`** *(Optional)*: Documentation for your repository.
4. **`assets/`** *(Optional backup folder)*: Standalone copies of `hero_opt.mp4`, `work_opt.mp4`, `logo_opt.jpg`, and all 25 project photographs for your own backup (not required for `index.html` to run).
