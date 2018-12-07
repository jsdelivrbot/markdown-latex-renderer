# Markdown LaTeX Renderer

Markdown LaTeX Renderer is a VSCode Extension to convert Markdown files' LaTeX expressions into SVG images on-the-fly.

![](.doc/README.gif)

## Settings

Create a `markdownLaTeXRenderer.json` file in your `.vscode` folder as follows:

```json
{
    "imagesFolderName": "images",
    "imagesUrlPreffix": "https://cdn.jsdelivr.net/gh/agurz/Markdown-LaTeX-Renderer/example/"
}
```

* **imagesFolderName**: Name of the folder where SVG images will be stored. This folder is relative to .md document
* **imagesUrlPreffix**: String to prepend to SVG image's path (The image path is relative to .md document)

## Example

Refer to [example](/example) folder
