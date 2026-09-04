# CircleCraft Product Website

Ready for a separate GitHub Pages repository named `circlecraft-site`.

## Before publishing
Copy the real CircleCraft Play Store assets into `assets/`:
- `feature-graphic.png`
- promotional screenshots `1.png` through `8.png`

## GitHub Pages
1. Create a public repository named `circlecraft-site`.
2. Upload the contents of this ZIP to the repository root.
3. Settings → Pages → Deploy from a branch.
4. Choose `main` and `/ (root)` and Save.

The existing CircleCraft privacy-policy site remains separate and is linked from the footer.

## Google Play button
The site currently says `Google Play link coming soon` because the closed-test opt-in URL was not supplied. Once you have it, replace that span in `index.html` with a normal link using the test URL. For production, use the public Play Store URL.
