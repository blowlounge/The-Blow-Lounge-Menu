THE BLOW MENU - SPEED & PHONE EDITING UPDATE

WHAT CHANGED
- Public menu images are now high-quality WebP files for faster loading.
- The first Food Menu image is preloaded; the Cocktail Menu remains lazy-loaded until selected.
- Preview editor supports one-finger pan and two-finger pinch-to-zoom on phones/tablets.
- Tap Select Price Area to draw a rectangle around the old price. The editor then returns to navigation mode.
- Price entry is larger and easier to tap on mobile screens.
- Deploy uploads edited WebP images and refreshes the image URLs in index.html.

GITHUB UPLOAD
1. Extract this ZIP.
2. Replace index.html and preview.html in the repository root.
3. Keep signin.html in the repository root.
4. Upload the complete assets folder beside index.html. It must contain food-menu.webp and cocktail-menu.webp.
5. Commit to the main branch and wait for Vercel deployment.

IMPORTANT
- Do not upload only index.html; both WebP files in assets are required.
- The old PNG/JPG assets may remain in GitHub, but the new index.html uses the WebP files.
- The existing editor still requires a GitHub Personal Access Token when Deploy is clicked.
