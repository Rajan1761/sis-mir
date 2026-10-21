# Saraswathi ❤️ Mageshwaran — Cinematic Wedding Invitation

A responsive React + TypeScript + Vite wedding invitation with an animated envelope intro, 3D gold ornament, countdown, calendar download, venue directions, sharing controls, and RSVP demo form.

## Requirements
- Node.js 20 or newer (Node.js 18.18+ may work with the installed Vite version)
- npm

## Run locally
```bash
npm install
npm run dev
```
Open the local URL shown by Vite.

## Production build
```bash
npm run build
npm run preview
```

## Deploy to Vercel
1. Put the project in a GitHub repository.
2. Import the repository in Vercel.
3. Framework preset: Vite.
4. Build command: `npm run build`
5. Output directory: `dist`
6. Deploy.

## Important content notes
- The supplied brief contains differing spellings for the bride's mother and groom's father. This project uses **Mrs. G. Pooselvi** and **Mr. P. Prasanth** from the family-details section. Please verify those names against the original invitation before publishing.
- Wedding date/time are set to 20 November 2026, 9:00–10:30 AM IST.
- The Maps button uses the supplied Google Maps short link.
- The RSVP form is front-end only and deliberately does not store or transmit guest data. Connect a secure backend/form service before using it for actual RSVPs.
- The music button is a UI toggle only; no music asset was supplied. To add music, provide a licensed audio file and wire it to a user-triggered audio element. Do not autoplay audio.
- The 3D heart ornament is decorative and is not a model of the actual venue or couple.
- Fonts load from Google Fonts; provide local font files if you need fully self-hosted operation.

## Project structure
```text
src/
  App.tsx
  main.tsx
  styles.css
public/
  favicon.svg
index.html
package.json
vite.config.ts
tsconfig.json
tsconfig.app.json
tsconfig.node.json
```
