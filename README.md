# Asif Newaz: personal academic website

Source for [newaz-aa.github.io](https://newaz-aa.github.io). It is plain HTML and CSS. There is no build step and no framework, so what is in this repository is exactly what gets served.

## Structure

| File | Page |
| --- | --- |
| `index.html` | Home: bio, education, honors and awards, research interests, selected publications |
| `research.html` | Research |
| `publications.html` | Full publication list |
| `teaching.html` | Courses and student supervision |
| `honors.html` | Honors and awards |
| `contact.html` | Contact details |
| `assets/style.css` | The one stylesheet shared by every page |
| `assets/photo.jpg` | Portrait on the Home page |

## Editing

Edit any file directly on GitHub: open the file, click the pencil icon, change the text, and commit. GitHub Pages republishes the site within a minute or two.

- **Text:** change the words between the tags. Leave the tags themselves (`<p>`, `<a>`, `<li>` and so on) in place.
- **Add a publication:** open `publications.html`, copy one existing `<li>...</li>` block, paste it in the right section (newest first), and edit the year, title, authors, venue and DOI link.
- **Change the photo:** replace `assets/photo.jpg` with a new image under the same name (a square image works best).
- **Footer date:** the "Last updated" text is at the bottom of every page, so change it in each file.
- **Colors and fonts:** all in `assets/style.css`. The accent color is the `--accent` value at the top.

## Previewing locally

Open `index.html` in a browser. The links between pages work from a local copy.

## Hosting

The site is served by GitHub Pages from the `main` branch. The repository name must stay `newaz-aa.github.io`.
