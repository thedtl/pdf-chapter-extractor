# PDF Chapter Extractor

A simple web tool to extract individual chapters from PDFs that have a built-in table of contents.

🔗 **Live Demo:** [https://YOUR-USERNAME.github.io/pdf-chapter-extractor](https://YOUR-USERNAME.github.io/pdf-chapter-extractor)

## Features

- 📄 Extract chapters from any PDF with bookmarks/table of contents
- 🔒 **100% Private** - all processing happens in your browser, nothing is uploaded
- 💻 Works on Mac, Windows, Chromebook - any device with a browser
- 📱 Mobile-friendly
- ⚡ Fast - no installation required

## How to Use

1. Go to the website
2. Drag & drop a PDF (or click to browse)
3. Click on the chapter you want
4. Click "Extract Selected Chapter"
5. The extracted PDF downloads automatically

## Setup Your Own (GitHub Pages)

### Quick Setup

1. **Fork this repo** or create a new one

2. **Upload `index.html`** to the repository

3. **Enable GitHub Pages:**
   - Go to repo Settings → Pages
   - Source: "Deploy from a branch"
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
   - Click Save

4. **Wait 1-2 minutes**, then visit:
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME
   ```

### Custom Domain (Optional)

If you want a cleaner URL like `chapters.yourlibrary.org`:

1. Go to Settings → Pages
2. Add your custom domain
3. Set up DNS (CNAME record pointing to `YOUR-USERNAME.github.io`)

## Technical Details

This tool uses:
- [PDF.js](https://mozilla.github.io/pdf.js/) - Mozilla's PDF reader (reads the table of contents)
- [pdf-lib](https://pdf-lib.js.org/) - Creates the new PDF with extracted pages

Everything runs client-side in JavaScript. No server, no backend, no data collection.

## Limitations

- Only works with PDFs that have a **built-in table of contents** (bookmarks/outline)
- Some PDFs have bookmarks but they don't map to page numbers correctly
- Very large PDFs (500+ pages) may be slow to process

## License

MIT - Free to use, modify, and distribute.
