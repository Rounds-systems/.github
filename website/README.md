# rounds.systems landing page

A single static file, `index.html`. No build step and no dependencies beyond Google Fonts.

- **Preview:** open `index.html` in a browser.
- **Deploy:** serve the `website/` folder from any static host (GitHub Pages, Netlify, Cloudflare Pages, an S3 bucket).
- **Theme:** follows the visitor's light or dark setting. All colours are tokens at the top of the `<style>` block.
- **Membership form:** a front-end template. It validates and shows a confirmation, but sends nothing. Wire the `submit` handler at the bottom of the file to your backend before launch.
- **Stats:** the figures (343,000 registered doctors, 1,200 members, 7 in 10 graduates are women, up to 50% inactive after marriage) come from the brand brief. Update them in the hero, the re-entry band and Fig. 1 (`N` and `LIT` in the script, one dot per 100 doctors).
