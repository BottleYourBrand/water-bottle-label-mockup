# water-bottle-label-mockup
A lightweight, client-side HTML/JavaScript tool for WordPress that allows customers to upload their own label designs and preview them as realistic mockups on a water bottle.

Features

Pure Client-Side: No server-side dependencies; runs entirely in the browser.

Multi-Format Upload: Supports JPEG, PNG, and PDF (first page) via PDF.js.

Aspect-Ratio Cropping: Centers and scales the uploaded design to fit the label area without distortion.

Curved Lighting: Subtle side-shadow gradient overlay to simulate a cylindrical wrap on the bottle.

Custom Upload Button: Styled to match the site’s design, with hover states.

Live Demo

View and test the mockup tool on our site:

Mockup Page: https://www.bottleyourbrand.com/blog/water-bottle-label-mockup/

Installation

Copy index.html (or paste the code into a WordPress HTML block/shortcode).

Update Image Path: Ensure the <img> src points to your blank bottle image:

<img class="bottle-image" src="https://www.yourlink.com" alt="Bottle" />

Embed in WordPress:

Use a Gutenberg HTML block, Elementor Custom HTML, or a plugin like WPCode.

Include PDF.js for PDF uploads:

<script src="https://cdnjs.cloudflare.com/ajax/libs/pdf.js/2.12.313/pdf.min.js"></script>

Usage

Navigate to the mockup page.

Click Upload Label and select an image or PDF.

The design will appear on the bottle, cropped and centered.

The side-shadow gradient adds realistic depth.

Customization

Dimensions & Position: Adjust CSS variables in the .label-overlay selector:

.label-overlay {
  left: 48.5%;  /* horizontal center */
  top: 42%;     /* vertical center */
  width: 34%;   /* label width */
  height: 25%;  /* label height */
}

Gradient Intensity: Tweak the .label-gradient background and opacity.

Button Style: Modify .btn-upload to match your theme color or font.

Related Links

Category: Water Bottle Labels
https://www.bottleyourbrand.com/water-bottle-labels

Make Your Own: Custom Water Bottle Label
https://www.bottleyourbrand.com/custom-water-bottle-label

License

MIT © Bottle Your Brand
