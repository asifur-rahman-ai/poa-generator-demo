# Power of Attorney Generator (Demo)

A browser-based form that generates a ready-to-use Power of Attorney document for admiralty proceedings. Fill in the details, then print to PDF or download as a Word file.

**Live demo:** https://YOUR_USERNAME.github.io/poa-generator-demo/

> This is a demo version. All names, ID numbers, addresses and photos are sample data. Nothing here is legal advice.

## Features

- Two templates: **Defend** (contest an admiralty suit) and **Arrest** (vessel arrest and recovery)
- Two power-giver types: **Company** (board resolution, two attorneys) and **Firm / Proprietorship** (single attorney)
- Optional former vessel name (Ex. name), IMO number and flag
- Power giver photo upload, shown with the attorneys' photos at the top of the document
- **Preview and Print to PDF** from the browser
- **Download as Word (.docx)** with matching layout and font
- Fully responsive form

## How to use

1. Choose the POA type and the power-giver type.
2. Upload the power giver's photo (optional) and fill in the fields marked with *.
3. Click **Preview & Print to PDF** or **Download as Word (.docx)**.

## Tech

- Single self-contained `index.html` (HTML, CSS and vanilla JavaScript)
- [docx](https://github.com/dolanmiu/docx) library, loaded from a CDN, for Word export
- No backend, no database, no build step

## Privacy

Everything runs in the browser. Entered data and uploaded photos are not sent to any server.

## Run locally

Download `index.html` and open it in a browser. An internet connection is needed for the Word export, because the `docx` library loads from a CDN.

## Disclaimer

The document text is a sample template for demonstration. Have any real Power of Attorney reviewed by a qualified lawyer before use.
