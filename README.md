# QR Code Generator

Turn a website or direct file download link into a scannable QR code and save it as a PNG. The generator runs entirely in your browser and keeps no history.

**[Open the QR Code Generator on GitHub Pages](https://aractor.github.io/qr-generator/)**

## Generate a QR code

1. Paste a complete URL starting with `https://` or `http://`.
2. Select **Generate QR code** to preview it.
3. Select **Download PNG** to save the image.

The QR code points to the URL you entered. For file links, the destination determines whether the file opens in the browser or downloads.

## Light and dark mode

The app follows your system theme by default. Use the sun or moon button in the top-right corner to switch modes. The app remembers your choice in the browser.

## Run offline

Download `index.html` and open it directly in a modern browser. The file includes everything needed to generate and save QR codes offline. Opening a scanned link still requires access to its destination.

## Third-party code

`index.html` bundles [Project Nayuki's QR Code generator](https://github.com/nayuki/QR-Code-generator/tree/v1.8.0), version 1.8.0, under the MIT license. The copyright and license notice are included in the HTML file.
