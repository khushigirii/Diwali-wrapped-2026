# Diwali Wrapped 2026 — Rotaract

A zero-budget, single-page interactive Diwali personality quiz. It runs entirely in the visitor's browser: no database, login, paid API, or form collection.

## Preview locally
1. Unzip the folder.
2. Open `index.html` in Chrome, Edge, Safari, or Firefox.
3. Answer the seven questions and reveal your result.
4. Use **Download my card** or **Share my wrapped**.

## Publish free with GitHub Pages
1. Sign in to GitHub and create a new **Public** repository, e.g. `diwali-wrapped-2026`.
2. Upload `index.html` to the repository's root (the top level).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish. Your public link will look like:
   `https://YOUR-USERNAME.github.io/diwali-wrapped-2026/`

## Alternative: Netlify Drop
1. Visit https://app.netlify.com/drop
2. Drag the unzipped folder (containing `index.html`) onto the page.
3. Netlify creates a free public URL. You can rename the site in its dashboard.

## Before publishing — customise these
Open `index.html` in any text editor and:
- Replace `Rotaract presents` / `Rotaract` with your exact club name if desired.
- Replace `@YOURROTARACTCLUB` in the share caption with your Instagram handle.
- Update the year if reusing the experience in a future year.

## How it works
- Seven tap-to-answer multiple-choice questions.
- Each answer adds a point to one of six festive archetypes.
- The highest score determines the personality result. Ties are resolved consistently by the order in the scoring list.
- A reveal animation introduces the result.
- The result card is drawn as a PNG in the browser, so users can download it or use the device's native share sheet where supported.

## Instagram sharing note
Websites cannot directly publish to an Instagram Story on someone's behalf. On supported phones, **Share my wrapped** opens the native share sheet with the PNG. Otherwise it downloads the image; the participant can then add it to their Instagram Story manually and tag the club.

## Privacy
Answers are processed locally in the visitor's browser and are not sent to a server or stored. The site does not ask for names, email addresses, phone numbers, or other personal details.

## Zero-budget hosting
GitHub Pages and Netlify offer free static-site hosting options. Their free-tier terms and availability can change; check the provider's current limits before a large campaign.
