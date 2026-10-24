# Hali Post Generator

A browser-based tool for making Hali social media posts.

- **Sports News** and **Moosun**: video posts with a timeline (intro, your clips and images, outro), a Dhivehi headline bar, and music or voiceover tracks. Export as MP4 (WebM in browsers without MP4 recording) or GIF.
- **Religious Quote**: image posts with Thaana text layers, preset or uploaded backgrounds, suggested text and logo colors, and a logo. Export as JPEG or PNG.

Everything runs in the browser. Files you upload never leave your computer, and **Save** keeps the project in that browser only.

## Fonts

Faruma, MV Waheed and MV Typewriter are used from the computer when installed. If they aren't, use **Add font** in the editor to load the .ttf file; until then text falls back to Noto Sans Thaana.

## Deploy

This is a static site with no build step. On Vercel, import the repository with the framework preset set to **Other**; every push to the main branch redeploys.

Open `index.html` directly in a browser to use it locally.
