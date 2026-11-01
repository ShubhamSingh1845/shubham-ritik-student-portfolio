# Shubham & Ritik — Student Portfolio

A responsive joint portfolio for BCA students Shubham Kumar and Ritik Singh, built with plain HTML, CSS, and JavaScript. No frameworks or build tools are required.

## Files

- `index.html` — standalone portfolio page.
- `style.css` — page styling and responsive layouts.
- `script.js` — mobile navigation, accessible project tabs, active navigation, and scroll reveals.
- `portfolio-single-file.html` — self-contained version with CSS and JavaScript embedded for Blogger.

## Run locally

Double-click `index.html` to open the portfolio in a browser. Alternatively, from this folder run:

```powershell
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Publish on GitHub

Create an empty GitHub repository, then connect it as the remote for this folder:

```powershell
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git commit -m "Add joint student portfolio"
git push -u origin main
```

The project files are intentionally plain static files, so they can also be published with GitHub Pages from the repository's `main` branch.

## Before publishing

Review the GitHub links in `index.html` and `portfolio-single-file.html`. Shubham's button currently points to the weather project repository. Replace `RITIK-USERNAME` with Ritik's profile or repository URL when available.

## License

Released under the MIT License. See [LICENSE](./LICENSE).
