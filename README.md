# Chin Yuan Yue — Portfolio

A minimalist, responsive personal website built with plain HTML, CSS, and JavaScript for GitHub Pages. All profile content is based on the supplied resume. No personal photographs or logos are used.

## Files

```
index.html
style.css
main.js
README.md
```

## Preview locally

Open `index.html` in a browser, or run a local static server from this folder:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish as a personal GitHub Pages site

1. Sign in to GitHub and find your exact GitHub username.
2. Create a **public** repository named **`YOUR-USERNAME.github.io`**, replacing `YOUR-USERNAME` with that exact username.
3. Upload **the contents of this folder** to the repository root. Keep `index.html`, `style.css`, and `main.js` together at the root. You can drag in the files through **Add file → Upload files**, then commit them.
4. Open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**. Select the **main** branch and **/(root)** folder, then save.
5. After GitHub finishes publishing, visit `https://YOUR-USERNAME.github.io/`.

If you make edits later, commit the updated files to `main` and GitHub Pages will publish the new version.

## Personalization

- Update the email link in `index.html` if your preferred public contact changes.
- Add a GitHub or project link only when you have verified the URL and want it public.
- The page uses abstract shapes and has no logo or favicon.
- This package does not include the resume PDF because it contains personal phone numbers. Add a public-safe CV later if desired.

The web font is loaded from Google Fonts. If unavailable, the browser uses a system sans-serif fallback.
