# Mechanical Engineering Portfolio

A responsive personal portfolio website for Rudy Amezcua, designed to be hosted on GitHub Pages.

## Files
- `index.html` — main portfolio site and Arduino monitoring-system case study
- `styles.css` — responsive styling
- `script.js` — copyright year
- `assets/system-diagram.svg` — original illustrative system architecture (not a physical wiring schematic)
- `assets/` — add actual project photos here

## Publish to GitHub Pages
1. Create a **public** repository named `engineering-portfolio` in your GitHub account.
2. Upload all files and folders from this package to the repository root.
3. Go to repository **Settings → Pages → Build and deployment**.
4. Choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Your site should appear at `https://rudyamezcua06-maker.github.io/engineering-portfolio/` after GitHub publishes it.

You can alternatively name the repository `rudyamezcua06-maker.github.io` to use a root profile-site URL.

## Add real project images
Replace the illustration and placeholders in `index.html` with photographs you own. Suggested names: `assets/prototype.jpg`, `assets/lcd.jpg`, `assets/enclosure.jpg`.

For example, change:
`<img src="assets/system-diagram.svg" ...>`
to:
`<img src="assets/prototype.jpg" ...>`

The current page includes clearly labeled image slots, not photographs claiming to depict an actual build.

## Customize before publishing
- Confirm the displayed name and biography are how you want to introduce yourself.
- Add links to a real résumé, LinkedIn profile, and professional email only when you're comfortable making them public.
- Add verified testing measurements, full Arduino source code, and SolidWorks images as available.
- The Arduino project shown here **does not include an IR sensor**; it uses DHT11 temperature sensing and PIR motion detection.
- The system diagram is **conceptual**, not a wire-for-wire build schematic.
