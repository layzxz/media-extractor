# Media Extractor

A lightweight, client-side web tool for extracting high-resolution (HD) photos and videos from **Instagram** (Stories/Posts) and **Snapchat** (Public Stories) using `view-source:`.

🔗 **Live Demo:** [https://layzxz.github.io/media-extractor/](https://layzxz.github.io/media-extractor/)

## Features

- **100% Client-Side:** Runs entirely in your browser with no backend or server required.
- **Instagram Support:** Parses `reels_media` JSON to extract clean Story slides (filtering out icons and junk assets) as well as Posts and Reels.
- **Snapchat Support:** Parses `__NEXT_DATA__` (`snapUrls.mediaUrl`) to extract public Stories in original HD quality.
- **`view-source:` Link Helper:** Quickly generates a `view-source:` URL for easier use on mobile browsers.
- **Paste & Filter:** One-click clipboard paste and media type filtering (All / Video / Image).

## How to Use

### On PC / Laptop

1. Open the Instagram Story/Post (make sure you're logged in for private accounts) or Snapchat public profile in your browser.
2. Press **Ctrl + U** (or prepend `view-source:` to the URL).
3. Press **Ctrl + A**, then **Ctrl + C** to copy the entire HTML source.
4. Open **Media Extractor**, click **Paste**, then click **Extract Media**.

### On Mobile (Android)

1. Expand the **Guide & Link Helper** section on the page.
2. Paste the Instagram / Snapchat link and tap **Copy view-source:**.
3. Paste it into your mobile browser's address bar (Chrome/Brave) and press Enter.
4. Long-press the text → **Select all** → **Copy**.
5. Return to **Media Extractor**, tap **Paste**, then **Extract Media**.

## Notes

- If video previews fail to load on desktop, temporarily disable your adblocker (e.g., Brave Shields) for this page.
- Due to browser CORS policies, some media files cannot be downloaded directly and will open in a new tab so you can save them manually (**Save As**).
