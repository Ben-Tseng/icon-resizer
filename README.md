# Chrome-Extension-Asset-Resizer
A lightweight, browser-based image resizer designed to help developers quickly meet the Chrome Web Store's strict asset dimension requirements.

Why this project?
When submitting a Chrome Extension, the developer dashboard requires images in specific dimensions (like 1280x800 for large tiles or 640x400 for small tiles). Most general-purpose editors are overkill or add compression artifacts.

This tool provides:

Exact Dimensions: No more "invalid image size" errors during upload.

Privacy First: Processing happens entirely in your browser. Your images are never uploaded to a server.

Speed: One-click presets for common Chrome Store sizes.

# Features
One-Click Presets: Instantly set dimensions to 1280x800 or 640x400.

Custom Dimensions: Manually input any Width and Height.

Instant Preview: See how your image looks before downloading.

No Installation: Just a single HTML file that runs in any modern browser.

# How to Use
Clone this repository or download the index.html file.

Open index.html in your web browser (Chrome, Edge, Firefox, etc.).

Click "Choose File" to upload your design or screenshot.

Select a Preset (e.g., 1280x800) or enter your own dimensions.

Click "Apply Changes".

Click "Download Resized Image" to save your asset.

# Tech Stack
HTML5 Canvas: For high-performance client-side image rendering.

JavaScript (ES6): For file handling and UI logic.

CSS3: Responsive and clean user interface.

# Note on Image Stretching
Currently, this tool uses a "fill" method which may stretch images if the aspect ratio of the original file differs significantly from the target size. For best results, use a source image with a similar 16:10 aspect ratio.
