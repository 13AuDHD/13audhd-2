# Thirteen Nebula personal site

Static, mobile-first website built for GitHub Pages.

## Upload
1. Upload every file and folder to the root of a GitHub repository.
2. In GitHub, open Settings > Pages.
3. Select Deploy from a branch, choose `main` and `/ (root)`, then save.

## Replace first
- `img/profile-placeholder.svg` with your square profile image. Keep the same filename or update every reference.
- `img/signature-placeholder.svg` with your transparent signature image.
- `img/hero-placeholder.svg` with the homepage hero image.
- Replace all SVG placeholders in `img/photos`, `img/design`, and `img/blog`.
- Update the five values in the `This year in numbers` section of `index.html`.

## Add a blog post
1. Copy one dated HTML article.
2. Rename it `YYYY-MM-DD-Post-title.html`.
3. Replace its content and hero image.
4. Add a matching card to `blog.html` with its date, category, length, title, and searchable snippet.
5. Keep only the three newest cards in the Notebook section of `index.html`.

The blog filters run entirely in the browser. No database, framework, or server is required.
