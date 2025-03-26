# 🎥 Lazyload Video FORK WEB AGENCY - Hosting for External Use - fork-agency.fr

This folder contains optimized video files (`.mp4` and `.webm`) used exclusively for implementing **lazy loading background videos** on websites.

## 🎯 Purpose

- Provide a lightweight and centralized **external hosting solution**.
- Enable **autoplay / muted / loop** behavior without self-hosting on each deployment.
- Ensure compatibility across multiple environments (staging, production, etc.).

## 📁 Videos Description

1. **blurred-call.mp4 / .webm**
   - A woman making a phone call, intentionally blurred.
   - Used to evoke mystery, human interaction, and focus on voice presence.

2. **call-center.mp4 / .webm**
   - A woman actively handling calls.
   - Represents professionalism and communication.

3. **fork-river.mp4 / .webm**
   - A river with branches merging.
   - Symbolizes the concept of "Fork" — multiple paths converging into one.

## 🌐 Usage

These videos can be embedded using a standard `<video>` element with lazy loading enabled. Both formats (`.mp4` and `.webm`) are provided for cross-browser compatibility.

```html
<video autoplay loop muted playsinline preload="auto">
  <source src="URL_TO_VIDEO.webm" type="video/webm" />
  <source src="URL_TO_VIDEO.mp4" type="video/mp4" />
</video>
