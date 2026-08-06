# Mito.H Apps GitHub Pages SEO update

## Files
- `index.html`: Japanese search landing page
- `en/index.html`: English search landing page
- `tester.html`: Japanese closed tester page
- `en/tester.html`: English closed tester page
- `style.css`: responsive shared design
- `sitemap.xml`: URLs submitted to search engines
- `robots.txt`: crawler guidance
- `support.html`, `privacy.html`: retained and improved

## REQUIRED before publishing the tester buttons
Search the following files for these placeholders:
- `TESTER_APPLICATION_URL`
- `GOOGLE_PLAY_OPT_IN_URL`

Replace them in:
- `tester.html`
- `en/tester.html`

Suggested usage:
- TESTER_APPLICATION_URL = Google Form collecting tester name/contact and Google Play account email
- GOOGLE_PLAY_OPT_IN_URL = the opt-in link issued by Google Play Console

## Upload
Replace the current repository files with this folder structure and commit to `main`.

## After publishing
1. Open the live Japanese and English URLs and test every link.
2. Add the GitHub Pages URL to Google Search Console.
3. Submit `sitemap.xml`.
4. Request indexing for `/`, `/en/`, `/tester.html`, and `/en/tester.html`.
5. Link to the Japanese or English landing page from relevant community posts.
