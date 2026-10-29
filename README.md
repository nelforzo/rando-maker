# rando-maker

A tiny browser app for generating random names and IDs. No dependencies, no build step — just open `index.html`.

## Features

- **New Rando** — generates a random name from a pool of European first and last names.
- **New ID** — generates a random 16-character ID using an unambiguous alphabet (no `0`/`O`, `1`/`I`/`L`) for easy reading and transcription.
- **New Birthdate** — generates a random ISO birthdate for someone between 20 and 50 years old.
- **Copy buttons** — every output is shown in a monospaced code block with its own copy button; copying never alters the displayed value.

## Usage

Open `index.html` directly in a browser, or serve the directory:

```sh
python3 -m http.server
```

Then visit <http://localhost:8000>.

## Live version

Also published as an app on <https://nelforzo.github.io/rando-maker/>.

## License

See the parent GitHub Pages project for licensing details.
