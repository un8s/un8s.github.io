# un8s.github.io

Source of [un8s.com](https://un8s.com): a static landing page that lists the
un8s projects, plus a small blog. It has no build step: GitHub Pages serves
`main` as it is.

## Blog

Posts are hand-written HTML under `blog/<slug>/index.html`, sharing
`blog/style.css`. To publish a post:

1. Copy an existing post's directory and replace the article.
2. Add it at the top of the list in `blog/index.html`.
3. Add an `<entry>` at the top of `blog/feed.xml` and bump its `<updated>`.
4. Update the "Writing" list on `index.html`.
