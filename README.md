# Jack's Workbench

A warm, Norse-inspired personal workbench for logistics study, research, revision, and daily notes. It is a static website: no server or build step is required.

## Run it locally

Open `index.html` in a browser. Notes and the daily quota are saved in that browser's local storage. They stay on that device and browser; they are not sent to GitHub or synchronized between visitors.

## Make your own copy

1. Fork this repository on GitHub.
2. In your fork, edit `index.html` to change the greeting, card copy, colors, and links. Search for the visible text you want to replace.
3. Enable GitHub Pages in **Settings → Pages**, selecting **GitHub Actions** as the deployment source. The included workflow publishes the site whenever you push to the `main` branch.
4. Share your Pages URL with friends. Each friend can fork the repository and publish a separate version.

## Public sharing and privacy

A GitHub Pages site is public. Anything you put in the HTML or commit to this repository can be read by anyone. The notes you enter in the website are stored only in that browser's local storage and are not visible to other visitors. To share updates with friends, edit the public page content and push those edits to GitHub. Do not put private journal entries, passwords, API keys, or personal data in the published source.

## Customize

- **Navigation:** find `<nav class="nav">` in `index.html`; edit the link labels and section anchors.
- **Four main cards:** find the `four-pane` section and edit the four card headings, sentences, and action labels.
- **Quick entries and quick actions:** find `quick-entries` and the `data-quick` buttons.
- **Look and feel:** edit the final CSS style block near `</head>` for background, glass effect, spacing, and Norse rune accents.
- **Persistent browser data:** the site uses `localStorage` for saved notes and quota. Clearing browser storage removes those local entries.

## License

No license is included yet. Add a license file if you want to grant others explicit reuse rights.

