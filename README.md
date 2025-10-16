# Hello World • Bootstrap 5 Single-Page App

A minimal, production-ready single-page web application that displays "Hello World" using an H1 element with id="greeting". Built with Bootstrap 5 via CDN, it is fully static and suitable for GitHub Pages deployment.

## Features
- Simple and clear UI using Bootstrap 5 (CDN)
- Self-contained: inline CSS and JavaScript, no build step required
- Embedded assets via data URIs (logo, favicon)
- Professional, responsive layout
- Graceful error handling and clean, maintainable code
- Works as a fully static site (GitHub Pages compatible)

## Setup / Deployment
- No build or server is required.
- To run locally: simply open `index.html` in your browser.
- For static hosting: upload the files to any static host (e.g., GitHub Pages). The repository created by this deployment already enables GitHub Pages.

## Usage
- Open the page and verify the greeting shows "Hello World!" in the H1 with `id="greeting"`.
- Click the "Check Status" button to see an example interactive message.

## Technical Overview
- Libraries: Bootstrap 5 (CSS and JS via CDN)
- Structure:
  - `index.html`: Single, self-contained page with inline CSS and JavaScript
  - No external build tools or dependencies
- Data URIs: Logo and favicon are embedded as data URIs in JavaScript and applied on page load.
- Accessibility: Basic features like skip link and ARIA live region for status updates.

## Code Quality Notes
- Inline JS uses `try/catch` for initialization, and small helper functions for safe DOM access.
- Minimal global surface: a small `window.app` object is provided for debugging/testing.

## License
This project is licensed under the MIT License. See the LICENSE section below.

### MIT License
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.