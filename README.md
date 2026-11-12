<div align="center">
<h1>📄 QR Lens Extractor 🔍</h1>

<p>
A modern, lightning-fast, client-side web app to instantly extract links and content from QR codes. Featuring drag-and-drop, visual code highlighting, live URL previews, and full multilingual support.
</p>

<div align="center">
  <a href="http://paypal.me/R0mb0">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Light.svg">
      <img alt="Saved you time? Support the dev" src="https://github.com/R0mb0/Support_the_dev_badge/blob/main/Badge/SVG/Support_the_dev_badge_Default.svg">
    </picture>
  </a>
</div>

---

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/93028b1ac1e944afb23ab0170b6e5ae2)](https://app.codacy.com/gh/R0mb0/Qr_lens_extractor/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)
[![pages-build-deployment](https://github.com/R0mb0/Qr_lens_extractor/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/R0mb0/Qr_lens_extractor/actions/workflows/pages/pages-build-deployment)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/R0mb0/Qr_lens_extractor)
[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/R0mb0/Qr_lens_extractor)
[![MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/license/mit)
[![Donate](https://img.shields.io/badge/PayPal-Donate%20to%20Author-blue.svg)](http://paypal.me/R0mb0)

<h2><a href="https://r0mb0.github.io/Qr_lens_extractor/">👉 Click here to test the app! 👈</a></h2>

</div>

[![01.png](https://github.com/R0mb0/Qr_lens_extractor/blob/main/Readme_imgs/01.png?raw=true)](https://r0mb0.github.io/Qr_lens_extractor/)
[![02.png](https://github.com/R0mb0/Qr_lens_extractor/blob/main/Readme_imgs/02.png?raw=true)](https://r0mb0.github.io/Qr_lens_extractor/)

<hr>

<h2>🚀 Features</h2>
<ul>
<li><strong>Local Processing</strong>: The core QR decoding happens entirely in your browser using <code>jsQR</code>. Your images are never uploaded to a server!</li>
<li><strong>Live Web Previews</strong>: If the QR code contains a URL, the app automatically fetches and displays a thumbnail screenshot of the destination page using the Microlink API.</li>
<li><strong>Visual Feedback</strong>: Once decoded, the app highlights the exact position of the QR code directly on the image with a green bounding box.</li>
<li><strong>Multilingual Support</strong>: Automatically detects your browser language or lets you manually switch between 6 European languages (EN, IT, ES, FR, DE, PT). Preferences are saved locally!</li>
<li><strong>Modern UI</strong>: Fast, responsive, and adaptive Dark/Light mode interface based on your system preferences, with manual override controls.</li>
<li><strong>Advanced Clipboard Integration</strong>: Copy the extracted link or download/copy the generated website preview image straight to your clipboard with one click.</li>
</ul>

<h2>🛠️ How it works</h2>
<ol>
<li><strong>Drag and drop</strong> your image file into the dropzone (or click to browse).</li>
<li>The app draws the image on a hidden HTML5 canvas and scans the pixels for QR patterns.</li>
<li>If found, the image is displayed with the QR code highlighted.</li>
<li>If the result is a web link, an API call is made to generate a website screenshot.</li>
<li>Use the action buttons to copy the content, open the link, or save the preview image!</li>
</ol>

<h2>🏆 What makes it special?</h2>
<ul>
<li><strong>Single-File Architecture</strong>: HTML, CSS, and vanilla JavaScript are bundled into a single file. No build steps, no Node modules, no complex setup.</li>
<li><strong>Zero Dependencies</strong>: Aside from the lightweight <code>jsQR</code> script fetched via CDN, everything is built from scratch using native Web APIs.</li>
</ul>

<h2>💡 Why use this tool?</h2>
<ul>
<li><strong>Desktop Convenience</strong>: Easily read QR codes from screenshots, flyers, or documents directly on your PC without needing to pull out your smartphone.</li>
<li><strong>Link Verification</strong>: Safely check where a QR code points to and view a preview of the webpage before actually visiting it on your main browser.</li>
</ul>

<h2>⚡ Getting Started</h2>

<h3>Online</h3>
<p>Simply visit the <a href="https://r0mb0.github.io/Qr_lens_extractor/">Live Demo hosted on GitHub Pages</a>.</p>

<h3>Local Installation</h3>
<p>Running this tool locally is ridiculously easy:</p>
<ol>
<li><strong>Clone this repository</strong> or simply download the <code>index.html</code> file.</li>
<li>Double-click <code>index.html</code> to open it in your favorite browser.</li>
<li>Done. <em>(Note: An internet connection is only required to load the jsQR CDN and fetch the live URL previews)</em>.</li>
</ol>

<a href="https://github.com/R0mb0/Crafted_with_AI">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/CraftedWithAIDark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAILight.svg">
<img alt="Crafted with AI" src="https://github.com/R0mb0/Crafted_with_AI/blob/main/Badge/SVG/NotMadeByAIDefault.svg">
</picture>
</a>
