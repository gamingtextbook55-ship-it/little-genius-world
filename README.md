# Little Genius World

A lightweight bilingual (Hindi + English) preschool learning game for ages 3–5.

## Included learning worlds
- ABC Adventure (A–Z with picture/emoji associations)
- Number Garden (1–20)
- Colour Party
- Shape Explorer
- Animal Kingdom

## Run locally
This is a static website and has no build step or runtime dependencies.
1. Extract the ZIP.
2. Open `index.html` in a modern browser, or run a local static server:
   - `python -m http.server 8000`
   - Visit http://localhost:8000

## Deploy to Vercel
1. Create a GitHub repository and upload `index.html` and `vercel.json`.
2. In Vercel, choose **Add New → Project**.
3. Import the GitHub repository.
4. Framework Preset: **Other**.
5. Build Command: leave empty.
6. Output Directory: leave empty (project root).
7. Deploy.

You can also drag and drop the extracted folder into Vercel's project upload flow.

## Privacy and safety notes
- No accounts, chat, ads, analytics, tracking pixels, external links, or backend endpoints.
- No personal information is requested or transmitted.
- Score is session-only and resets when the game is restarted.
- Voice uses the browser's built-in Web Speech API when available. Voice availability and pronunciation depend on the device/browser language packs. The game remains playable with sound disabled.
- Emoji illustrations are system-rendered; this version does not download third-party images or audio.

## Accessibility and age suitability
- Large touch targets and responsive layout.
- Keyboard-focus outlines and screen-reader status updates.
- Reduced-motion preference respected.
- Adult supervision is recommended for preschool use.
