# portfolio webby

Open `index.html` to preview. The **Customize** drawer now has an individual colour control for every major component:

- Page background
- Cards, navigation and panels
- Main text
- Secondary text
- Accent colour
- Buttons
- Button text
- Borders
- Mini-game wall
- Mini-game floor
- Inputs and reaction backgrounds

The default palette is a subdued cow-in-nature scheme using cream, soil brown, moss green, hay, and charcoal. Select **Cow in Nature preset** to restore it.

Settings are saved in the current browser. To make chosen colours permanent for every visitor, copy the selected hex values into the `:root` block at the top of `index.html`, replacing the existing values.

## GitHub update steps

1. Unzip this package.
2. Open your GitHub website repository.
3. Select the existing `index.html` and use the pencil icon, or choose **Add file > Upload files**.
4. Replace the old `index.html` with this one.
5. Commit the change to `main`.
6. GitHub Pages will redeploy the updated site.

Replace the sample paintings by searching for `const paintings=` in `index.html`.

Guestbook entries, reactions, and custom settings use browser local storage, so they are not shared between visitors on the static version.
