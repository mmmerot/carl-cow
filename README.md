# Portfolio webby

Open `index.html` in a browser to preview the site. The site is responsive and uses no build tools.

## Add your own paintings

Open `index.html` in a text editor and search for `const paintings=`. Replace each sample painting's title, details, finished image, process image, and note. For dependable hosting, create an `images` folder next to `index.html` and use paths such as `images/garden.jpg`.

## Publish on GitHub Pages

1. Sign in to GitHub and create a new public repository, for example `painting-portfolio`.
2. Unzip this package.
3. In the repository, choose **Add file > Upload files**.
4. Upload `index.html` and your optional `images` folder. Keep `index.html` at the repository root.
5. Commit the files.
6. Open **Settings > Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Choose **main** and **/(root)**, then save.
9. Return to the Pages settings to see the published URL.
10. For later changes, use GitHub's pencil icon or upload updated files and commit again.

## Important static-site note

The included guestbook, reactions, and settings use browser `localStorage`. They work immediately, but each visitor sees only their own entries and reactions. To share entries across visitors, connect Firebase, Supabase, or another serverless database and add security rules, rate limiting, spam filtering, and moderation. Never place administrator secrets in `index.html`.

The current artwork images are online placeholders. Replace them with your own files before launch.

