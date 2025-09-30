
## Introduction
This template is intended for the purpose of creating a *new* website, and as such, will be occassionally updated to work with the latest version of Hugo. The version used currently is Hugo v0.148.1.

This doesn't mean that it uses all of Hugo's features. In fact, the goal of this starter is to use as *few as possible* so that the amount of Hugo-specific detail you need to understand is kept to a minimum. Your experience should feel as close to "edit some HTML, write some Markdown" as possible.

## Styling
Follows my own best practices for building webpage...
1.`layout.css` – Tailwind-like utility classes for layout
2. `typography.css` – Styling for text content elements
3. `styles.css` –
4. `main.css` – For managing CSS variables, font imports,

## RSS
- Separate RSS feeds for each type of content, with full post content provided for each post in the RSS feed.
- RSS link in footer (with a link to aboutfeeds.com)

## Hugo features
- Hugo's render hooks are used to provide useful enhancements to Markdown syntax:
  - Add add captions in Markdown image syntax (e.g. ), which automatically inserts them into <figcaption> elements.
  - Add an `external` class to links that link to absolute URLs.

  -
- Shortcodes are avoided because they tie your Markdown to Hugo-specific syntax, it is recommended to just write HTML as much as possible and only reach for shortcodes if the simple approach starts to feel painful. Hugo has [built-in "embedded" shortcodes](https://gohugo.io/content-management/shortcodes/#embedded) for the most common needs. Privacy preservation for those is turned on in `hugo.toml`.
- Hugo's [image processing](https://gohugo.io/content-management/image-processing/) features are not used because I prefer to manually resize/edit images.
- The site doesn't use Hugo's [Modules feature](https://gohugo.io/hugo-modules/use-modules/) as I think they're needless complexity for most people.
