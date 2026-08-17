# Content Credentials Prototype

This prototype keeps the full social feed as a single image. The only interactive element is the Content Credentials banner near the top.

Click the banner to open the detailed Content Credentials summary/history screen. Close it with the X, by clicking outside, or by pressing Escape.

## Hosting

Upload `index.html`, `feed.png`, and `credentials-detail.png` to a static host such as GitHub Pages, Netlify, Cloudflare Pages, or another static web host.

For Qualtrics, this package keeps the visual assets local to the page. If Qualtrics strips local image references, the next version can inline both images as data URIs for a single-file embed.
