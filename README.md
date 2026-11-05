# Space Riders legal documents

The Impressum (legal notice, DDG), Datenschutzerklärung (privacy policy,
DSGVO/GDPR) and Nutzungsbedingungen (terms of use) for Space Riders, a game
in development, in German and English. The German terms of use are the
binding version. This repo is the only copy: the game will link here, the
website's footer links here, and a store's privacy policy URL points here
too.

## Published at

GitHub Pages serves `main` from the repo root:

| Document | German | English |
|---|---|---|
| Impressum | [impressum.de.html](https://space-riders.github.io/space-riders-legal-docs/impressum.de.html) | [impressum.en.html](https://space-riders.github.io/space-riders-legal-docs/impressum.en.html) |
| Datenschutzerklärung | [datenschutzerklaerung.de.html](https://space-riders.github.io/space-riders-legal-docs/datenschutzerklaerung.de.html) | [datenschutzerklaerung.en.html](https://space-riders.github.io/space-riders-legal-docs/datenschutzerklaerung.en.html) |
| Nutzungsbedingungen | [nutzungsbedingungen.de.html](https://space-riders.github.io/space-riders-legal-docs/nutzungsbedingungen.de.html) | [nutzungsbedingungen.en.html](https://space-riders.github.io/space-riders-legal-docs/nutzungsbedingungen.en.html) |

If a file is renamed or the site moves, change the game's links in the same
release, and the footer links in
[space-riders-webpage](https://github.com/Space-Riders/space-riders-webpage).

## Editing

- **Keep both languages in sync.** Any sentence changed in one language
  changes in the other in the same commit, and the sections stay in the same
  order.
- Update the "Stand" / "Last updated" date in both files of a document when
  its content changes.
- **The terms of use carry a version number** ("Version 1" next to the date).
  Once the game asks users to agree to the terms, its own copy of this
  number mirrors it. A change that affects users' rights or duties bumps the
  version in both files and in the game in the same release, so the game
  asks again. Keep the version it replaces as an archive copy,
  `nutzungsbedingungen-v<N>.de.html` and `nutzungsbedingungen-v<N>.en.html`
  (`<N>` is that version's number), so what a user agreed to stays readable.
  Typos and pure clarifications keep the version.
- **Keep the documents true to the game.** The privacy policy names every
  place data leaves the device. Today the game is in development, and the
  policy says so in its "Space Riders (in Development)" section; before the
  first release that section is replaced by one for each thing the game
  does (what stays on the device, every service it talks to, accounts,
  sync, analytics, purchases), and the terms gain the price, platforms and
  stores. A release that adds a service, a request or a stored value
  updates the policy before it ships, together with the game's privacy
  manifest and the store's privacy label.
- Each file is a standalone page: a short shared header (charset, viewport,
  `style.css`, language switch) around the document text. Edit only the text
  between the language switch and `</main>`.
- The privacy policy is adapted from text made with Datenschutz-Generator.de
  (Dr. Thomas Schwenke) and the Impressum follows eRecht24. Keep the generator
  attribution at the end of the privacy policy; the free generator licence
  requires it. For that reason this repo has no open-source licence.
- `.nojekyll` makes Pages serve the files exactly as committed.
