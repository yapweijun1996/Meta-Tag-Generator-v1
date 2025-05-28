# Meta Tag Generator

[Live Demo](https://yapweijun1996.github.io/Meta-Tag-Generator-v1/)

A simple, interactive tool to select and generate HTML meta tags for SEO, social sharing, PWA support, and more.

## Features

* **Core SEO Tags**: charset, viewport, description, canonical
* **Open Graph**: OG title, description, image for Facebook, LinkedIn
* **Twitter Cards**: summary and summary\_large\_image support
* **PWA & iOS**: theme-color, apple-mobile-web-app-capable, status bar styles
* **Legacy & Niche**: legacy HTTP-equiv and verification tags
* Live preview of selected tags and easy copy-to-clipboard

## Usage

1. Open the https://yapweijun1996.github.io/Meta-Tag-Generator-v1/
2. Check the boxes for the meta tags you need.
3. Fill in any custom values in the input fields.
4. Copy the generated `<meta>` tags from the code panel into your HTML `<head>`.

## Customize

* To **add or modify** tags, edit the `metaTagsData` array in `index.html`.
* Styles are defined in the `<style>` block at the top of `index.html`.
* Behavior is managed by the JavaScript functions `renderMetaTags()` and `updateGeneratedCode()`.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
