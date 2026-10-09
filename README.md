# Animevolt

A responsive, static starter website for an anime-editing clip library. It includes search, category filters, preview dialogs, and favourites stored in the visitor's browser.

## Files
- `index.html` — page structure
- `style.css` — responsive dark/neon styling
- `script.js` — sample clip data and interactions

## Important about sample content
The six cards are **original placeholder designs**. No anime episodes or downloadable video files are included. Only publish videos that you created or have permission to redistribute. A clip being short or available online does not automatically make it free to redistribute.

## Add a video you are allowed to share
1. Create a folder named `clips` in the repository.
2. Upload your authorized `.mp4` file there.
3. Open `script.js` and find the clip object you want to update in the `CLIPS` array.
4. Set `video: "clips/your-file.mp4"`.
5. Set `canDownload: true` only if you have permission to let visitors download and reuse that file.
6. Optionally set `thumbnail: "images/your-thumbnail.jpg"` after adding a thumbnail you are allowed to use.
7. Commit the changes and test the page. Large videos may exceed GitHub's file limits or use too much bandwidth; consider a suitable video host if needed.

## Publish with GitHub Pages
1. Upload `index.html`, `style.css`, `script.js`, and this README to the root of your repository.
2. Open the repository's **Settings → Pages**.
3. Under build/deployment, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then save.
5. Wait for deployment. The site address is usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

GitHub Pages supports static sites; it does not provide a server/database for uploads, user accounts, or backend functionality.

## Before going public
- Replace the demo email address `hello@animevolt.example` in `index.html`.
- Add your own contact and privacy/copyright pages as needed.
- Check every video and image licence.
- Test search, filters, preview, and download on mobile.
