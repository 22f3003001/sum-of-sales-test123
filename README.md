# Test Application

This is a single-page web application that allows users to input Markdown text and see the live rendered output with syntax highlighting. The application is built using modern web technologies, leveraging CDN-hosted libraries for styling, markdown parsing, and code highlighting.

## Features
- Displays a title "Test Application" in an `<h1>` tag with id `title`.
- Provides a textarea for user to input Markdown content.
- Renders the Markdown text in real time as HTML.
- Supports syntax highlighting for code blocks.
- Responsive design for mobile and desktop.
- Graceful error handling.

## How to Use
1. Open the `index.html` file in your web browser.
2. Enter or paste Markdown content into the textarea.
3. View the styled and syntax-highlighted HTML content appear in the preview area below.

## Code Structure Explanation
- **HTML**: Contains the layout, including the title, input textarea, and output container.
- **CSS**: Embedded within `<style>`, styles the layout, including responsiveness and aesthetics.
- **JavaScript**:
  - Listens to input events on the Markdown textarea.
  - Parses the Markdown input into HTML using the `marked` library.
  - Dynamically updates the preview section.
  - Finds code blocks within the rendered HTML and applies syntax highlighting with `highlight.js`.
  - Includes error handling to prevent crashes on malformed Markdown or highlighting issues.
- **External Libraries**:
  - Bootstrap via CDN for styling.
  - Marked.js for Markdown parsing.
  - Highlight.js for syntax highlighting.

## Technologies Used
- HTML5
- CSS3
- JavaScript ES6+
- Bootstrap 5.3 via CDN
- marked.js for Markdown parsing via CDN
- highlight.js for code syntax highlighting via CDN
- Responsive design principles

Feel free to customize and extend this application as needed!