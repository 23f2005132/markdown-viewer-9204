# Markdown Viewer 9204

A simple web application that fetches a Markdown file (`input.md`), renders it as HTML, and displays both the rendered HTML and the original Markdown source.

## Features

-   Fetches and renders Markdown from `input.md`.
-   Displays the rendered HTML in a `div` element.
-   Provides a button to toggle the visibility of the original Markdown source in a `pre` element.

## Usage

1.  Place your Markdown content in a file named `input.md` in the same directory as `index.html`.
2.  Open `index.html` in your web browser.
3.  Click the "Show Source" button to display the original Markdown source.
4.  Click the "Hide Source" button to hide the original Markdown source.

## Technologies Used

-   HTML
-   CSS
-   JavaScript
-   [marked.js](https://github.com/markedjs/marked) - A Markdown parser and compiler.

## Notes

The ID of the pre block containing the source is `markdown-source`.
