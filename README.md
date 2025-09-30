
## Introduction
This template is intended for the purpose of creating a *new* website, and as such, will be occassionally updated to work with the latest version of Hugo. The version used currently is Hugo v0.148.1.

This doesn't mean that it uses all of Hugo's features. In fact, the goal of this starter is to use as *few as possible* so that the amount of Hugo-specific detail you need to understand is kept to a minimum. Your experience should feel as close to "edit some HTML, write some Markdown" as possible.

To get started, [install Hugo](https://gohugo.io/installation/) and clone this repository. Then `cd` into the repository and run `hugo serve --renderToMemory` to view the site.

## Features
- Dynamic social media/preview cards
- My recommended CSS file organization:
  1.`layout.css` – Define styles for the entire site structure (columns, nav bar, CSS reset, etc).
  2. `typography.css` – Consolidated styles for text content elements
  3. `custom.css` – For declaring CSS variables, and writing page-specific classes
- RSS feed with full post content
- Shortcodes are avoided because they tie your Markdown to Hugo-specific syntax, it is recommended to just write HTML as much as possible. But Hugo has [built-in "embedded" shortcodes](https://gohugo.io/content-management/shortcodes/#embedded) for the most common needs. Privacy preservation for those is turned on in `hugo.toml`.
- Pre-filled `netlify.toml` file to ease deployment to Netlify (great host, generous free tier).

## Learn more
This starter tries *really* hard to be as minimal as possible. But Hugo has a ton of features, some of which you will eventually want to reach for. The following are probably the most important:
- [Render hooks](https://gohugo.io/content-management/markdown-attributes/): These allow you to control how markdown is converted to HTML, which enables things like [adding "external" classes](https://gohugo.io/render-hooks/links/) to links that point away from your site, or [rendering images within <figcaption> elements](https://gohugo.io/render-hooks/images/).
- [Taxonomies](https://gohugo.io/content-management/taxonomies/): For organizing your content by tags and categories.
- [Full-text search](https://gist.github.com/cmod/5410eae147e4318164258742dd053993)
- [Sections](https://gohugo.io/content-management/sections/): Create multiple content sections and give them separate designs and RSS feeds. For example, the [riffs](https://joodaloop.com/riffs) section on my site.
- [Markdown attributes](https://gohugo.io/content-management/markdown-attributes/): Easily add classes and other attributes to markdown elements.
- [Image processing](https://gohugo.io/content-management/image-processing/) pipelines
- [Page bundles](https://gohugo.io/content-management/page-bundles/): A way to colocate images with the pages where they're used. I personally don't use this because I like my writing to be a flat list of Markdown files.
- [Data sources](https://gohugo.io/content-management/data-sources/): To load content from local or remote sources (like headless CMSes).
