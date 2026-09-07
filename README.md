# Ardéla — Tap Portal

Static, self-contained demo of the personal "tap portal" that every **Ardéla** NFC business card opens to.

`index.html` is the whole thing — no build step, no backend. State (profile, links, theme, background, card type, link visibility) is saved to the browser's `localStorage` purely for demo purposes; nothing is sent anywhere.

## What it demonstrates

- Editable profile (display name, bio) and a reorderable link list with a custom icon-grid platform picker.
- Brand-accurate icons/colors for Instagram, Facebook, and Viber.
- 15 selectable visual themes (all checked for accessible contrast), plus custom background upload.
- **Tap Behavior**: Full Portal vs. **Direct Link** (skips straight to one chosen platform, instantly — no loading transition).
- **Your Card**: Ardela One (white), Ardela Noir (black), Ardela Titanium (metal) card types.
- **Link Visibility**: Public (discoverable, `linkardela.com/your-name`) vs. Private (collapsed label like `link-ardela-noir`, no domain/code shown until tapped — tap again to copy the full link).
- Real vCard download via "Save My Contact."

## Status

This is a design/UX demo only, pending the real backend and the `linkardela.com` domain purchase. Once the domain is bought, the placeholder `linkardela.com` references throughout `index.html` will be confirmed/updated, and this repo can be wired up to GitHub Pages (or another host) with a custom domain.
