# PDF Splitter

I built this project to make PDF page extraction super simple.

No signup.
No server upload.
No unnecessary steps.

Just upload your PDF, pick the pages you want, and download the new file.

---

## Live Demo
https://pdfsplitter-six.vercel.app/


---

## What This App Does

- Extracts only the pages you select from a PDF
- Supports drag and drop upload
- Shows page thumbnails for quick visual selection
- Allows single-page selection with click
- Supports range selection with Shift + Click
- Select all / deselect all in one action
- Lets you set a custom output file name
- Includes light and dark theme toggle
- Shows loading and extraction progress
- Works fully inside the browser

---

## Keyboard Shortcuts

- Space: extract selected pages
- Esc: clear the current file
- Cmd/Ctrl + A: select all or deselect all pages
- Shift + Click: select a page range

---

## Tech Stack

- React (Create React App)
- PDF.js (reading and rendering PDF pages)
- jsPDF (creating the output PDF)
- Tailwind CSS (UI styling)
- Lucide React (icons)
- Vercel (deployment)

---

## How It Works

1. Upload a PDF (or drag and drop it).
2. The app processes it locally in the browser.
3. Thumbnails are generated for all pages.
4. Select the pages you want to keep.
5. Set your output file name.
6. Click Extract (or press Space) to download the new PDF.

---

## Privacy

I designed this app to be privacy-friendly:

- Your PDF is processed locally on your device
- No file is uploaded to any server
- No account or login is required

---

## Limits and Quality

- Maximum file size: 100 MB
- Output generation uses high-quality rendering settings

---

## Run Locally

```bash
npm install
npm start
```

---

## Author
Built by [Prashanth Goud](https://www.linkedin.com/in/prashanth-goud-372485294/)
