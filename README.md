# Ronesh Maharjan — Portfolio

A responsive personal portfolio built with HTML, CSS and vanilla JavaScript for GitHub Pages.

## Preview locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Personal settings
Edit `config.js` to update the email
 address, social profile links and education details. Only add social URLs you actually use. The contact form remains disabled until a real Formspree endpoint is configured.

## Contact form
1. Create a form at https://formspree.io/ and set its destination to your email.
2. Verify the destination if requested.
3. Copy the public endpoint, shaped like `https://formspree.io/f/abcdefgh`.
4. Add it as `formspreeEndpoint` in `config.js`.
5. Deploy and test the form. Until configured, use the direct email link.

Do not put passwords or private API keys in this public repository.

## Privacy
The birth date is not included in public files. The optional age endpoint described in the previous version is not part of this redesign's page flow; the About section avoids publishing an age. The semester progress bar was removed because a guessed progress percentage can be misleading.

## Publish
Keep the contents of this folder at the root of your GitHub Pages repository and commit to the publishing branch. The `CNAME` file is preserved for `roneshmaharjan.com.np`; keep the custom domain configured in GitHub Pages settings.

## Project visuals
The project panels are CSS-made illustrative placeholders, not screenshots of finished applications. Replace them with genuine screenshots when available.

## Files
- `index.html` — page structure and portfolio content
- `styles.css` — layout, responsive styles and light/dark themes
- `script.js` — navigation, theme, social links and contact form behavior
- `config.js` — public personal settings
- `CNAME` — GitHub Pages custom domain
- `assets/favicon.svg` — site icon
- `.nojekyll` — GitHub Pages configuration
