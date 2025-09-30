
## Introduction
This template is intended for the purpose of creating a *new* website, and as such, will be occassionally updated to work with the latest version of Hugo. The version used currently is Hugo v0.148.1.

This doesn't mean that it uses all of Hugo's features. In fact, the goal of this starter is to use as *few as possible* so that the amount of Hugo-specific detail you need to understand is kept to a minimum. Your experience should feel as close to "edit some HTML, write some Markdown" as possible.

## Features
- Dynamic social media/preview cards
- My recommended CSS file organization:
  1.`layout.css` – Define styles for the entire site structure (columns, nav bar, CSS reset, etc).
  2. `typography.css` – Consolidated styles for text content elements
  3. `custom.css` – For declaring CSS variables, and writing page-specific classes
- RSS feed with full post content
- Shortcodes are avoided because they tie your Markdown to Hugo-specific syntax, it is recommended to just write HTML as much as possible. But Hugo has [built-in "embedded" shortcodes](https://gohugo.io/content-management/shortcodes/#embedded) for the most common needs. Privacy preservation for those is turned on in `hugo.toml`.

## Recommendations
To get more out of Hugo, I recommend checking out the following features:
- Render hooks: and an explainer.
- [Image processing](https://gohugo.io/content-management/image-processing/) pipelines
