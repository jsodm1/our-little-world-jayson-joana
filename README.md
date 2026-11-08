# Our Little World — Jayson & Joana ♡

A separate, free, mobile-first **3D couple-world preview** for Jayson and Joana.

**Project website:** https://jsodm1.github.io/our-little-world-jayson-joana/

**Original personal site:** https://jsodm1.github.io/ (unchanged)

## What works now

This repository contains a dependency-free Three.js web preview in **index.html**. It uses Three.js from a public CDN and works directly in a browser when GitHub Pages is enabled.

- Four 3D scenes: Sunset Beach, Sakura Garden, Little Town, Starlight Hill.
- Stylized procedural avatars for Jayson and Joana.
- Joystick for phones, WASD/arrow keys on PC; drag to rotate camera.
- Walk/run controls, 3D camera follow and basic walking movement.
- A selection of preview interaction poses.
- Outfit color customization for both characters.
- Love letters saved to browser local storage.
- Image/portrait gallery with local browser storage (up to six compressed photos).
- Local music player (bring your own music).
- Editable subtitle in the "J & J" menu.
- Game screenshot button and responsive soft pastel design.
- Independent project URL; does not replace your original home page.

## Important status — preview, not two-person multiplayer

**This hosted version is a solo preview.** Jayson is locally controlled; Joana is a non-connected demo avatar. It does **not** yet connect two real phones, synchronize a kiss or hug, or authenticate a second person.

Letters and pictures saved in this hosted preview are only saved **on that device/browser**. They are not shared across devices, and clearing browser data can erase them.

The full version requires:
- Authenticated private two-player rooms and invited accounts.
- A private database with access-control rules.
- Character models and outfit assets built/rigged from the supplied references.
- True paired animations, synced hand-holding, seating, hug and kiss.
- Shared persistent letters, memories, messages, and music.
- Owner-only in-world editing permissions.

The larger React/TypeScript/Supabase starter is available as a separate downloadable ZIP in the ChatGPT conversation. This repository currently serves an independent standalone browser demo, **not that entire ZIP**.

## Deploy with GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. The included workflow at **.github/workflows/pages.yml** deploys the static site automatically when main changes.
5. Check the **Actions** tab to verify success.

The resulting website URL is:
https://jsodm1.github.io/our-little-world-jayson-joana/

No secrets or API keys are required for the preview.

## Future development plan

1. Upgrade to an organized React + Vite + React Three Fiber application.
2. Add Supabase Auth, secure room claims, a two-user limit, and RLS.
3. Add movement synchronization, partner proximity and interaction invitations.
4. Import two Blender-generated, rigged character models that match the references.
5. Add synchronized interaction animation state machines.
6. Add shared, private photo storage, letters, chat, and audio.
7. Add editable couple home, object placement, and extra destinations.
8. Add owner console, backups, and proper privacy settings.

Keep personal photos, private letters, passwords, and invitation codes **out of this public GitHub repository**.
