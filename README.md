# A Square Tools

Free, browser-based utility tools built by [A Square Solutions](https://asquaresolution.com) — small, fast, no signup.

These tools are surfaced as pages on the A Square Solutions website; this repository holds their source (plain HTML + JavaScript).

## Live tools

| Tool | What it does | Live page |
|---|---|---|
| **Image to PDF Converter** | Combine JPG / PNG / WebP images into a single PDF — reorder pages and choose A4 / A3 / Letter. Runs entirely in your browser. | [asquaresolution.com/image-to-pdf-converter](https://asquaresolution.com/image-to-pdf-converter/) |
| **QR Code Generator** | Generate a QR code from any text or URL and download it — no email, no signup. | [asquaresolution.com/free-qr-code-generator](https://asquaresolution.com/free-qr-code-generator/) |

## How it works

Each tool is a single static HTML page (vanilla JavaScript, no framework) embedded into the A Square Solutions WordPress site. The Image-to-PDF converter builds the PDF locally in your browser with [jsPDF](https://github.com/parallax/jsPDF) — your images are never uploaded to a server.

## Tech

HTML5 · vanilla JavaScript · jsPDF (client-side PDF generation)

## Built by

[A Square Solutions](https://asquaresolution.com) — AI products, digital systems, and web experiences.
