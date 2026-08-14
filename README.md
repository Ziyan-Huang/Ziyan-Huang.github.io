# Ziyan Huang Homepage

This repository contains the source code for Ziyan Huang's personal academic homepage:

[https://ziyan-huang.github.io/](https://ziyan-huang.github.io/)

The website is a simple static site built with HTML and CSS and hosted with GitHub Pages.

Public links use GitHub Pages' extensionless aliases (for example,
`/publications` rather than `/publications.html`). Keep internal links,
canonical URLs, the Atom feed, and the sitemap aligned with those clean URLs.

## Main Files

- `index.html`: homepage content
- `publications.html`: selected publication list
- `talks.html`: invited talks
- `blog.html`: note index
- `main.css`: page styles
- `assets/`: optimized images and social preview graphics

## Publishing a Note

When adding a local note, update the article page, `blog.html`, the latest-writing
card in `index.html`, `feed.xml`, and `sitemap.xml`. External writing belongs in
`blog.html` and `feed.xml`, but not in the site-only sitemap. Keep the site
dependency-free and run the HTML, link, responsive-layout, and image-size checks
before deployment.
