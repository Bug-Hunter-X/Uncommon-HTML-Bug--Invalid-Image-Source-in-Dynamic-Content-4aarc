# Uncommon HTML Bug: Invalid Image Source in Dynamic Content

This repository demonstrates a subtle bug related to dynamically adding an image with an invalid source to an HTML document using JavaScript.

The bug occurs because the dynamically added `img` tag uses an invalid image source ('invalid-image-source.jpg'). While this might not immediately cause an error, it can result in a broken image icon being displayed where the image should appear and can affect the page layout.

The solution involves ensuring all image sources are valid and potentially using error handling or fallback mechanisms.