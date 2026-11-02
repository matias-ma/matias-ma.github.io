# Matias Andia

Personal academic website: https://matias-ma.github.io/

A static HTML/CSS website hosted with GitHub Pages. No build step or JavaScript runtime is required.

## Local preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Then visit http://127.0.0.1:8765. Stop with Control-C.

## Updates

Edit `index.html` for content and `style.css` for layout. Commit and push changes to `main`; GitHub Pages publishes the repository root automatically. PDFs retain stable paths. The portrait crop is controlled by `.portrait` in the stylesheet.

IBM Plex Mono is included under the SIL Open Font License; see `assets/OFL.txt`. Papers, notes, posters, and photographs retain their respective authorship and rights.

## Search visibility

The homepage includes a descriptive title, canonical URL, profile structured data, and sharing metadata. `robots.txt` permits crawling and points to `sitemap.xml`.

After publication, verify `https://matias-ma.github.io/` as a URL-prefix property in Google Search Console, submit `sitemap.xml`, and request homepage indexing. Add the site link to relevant academic profiles. Search rankings are determined by search engines and cannot be guaranteed.
