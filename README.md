# PDF Loader App

A simple static web app for GitHub Pages.

## How it works
- Opens a loading screen video first
- Then automatically shows a PDF in the browser
- Uses only HTML, CSS, and JavaScript, so it is easy to host on GitHub Pages

## Files
- `index.html` — the app
- `assets/loading.mp4` — your loading screen video
- `assets/document.pdf` — your PDF file

## How to use
1. Put your video in `assets/loading.mp4`
2. Put your PDF in `assets/document.pdf`
3. Push the repository to GitHub
4. In GitHub repository settings, enable GitHub Pages from the root branch

## Optional URL parameters
You can also use custom file names:

`https://your-site.github.io/?video=assets/myvideo.mp4&pdf=assets/myfile.pdf&title=My%20Document`

## Notes
- Keep the video muted so autoplay works in most browsers
- If the PDF does not render inside the page in a particular browser, the Open PDF button will still open it directly
