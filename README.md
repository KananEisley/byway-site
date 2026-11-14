# byway-site

KananEisley's website, served by GitHub Pages (`CNAME`; the old
kananeisley.github.io/byway-site addresses forward there). Plain HTML and CSS,
no scripts:

- `index.html`: KananEisley's home page, a card for each app.
- `style.css` for the app pages, `doc.css` for privacy and help pages, `images/`
  for the app icons (256 px).
- `lens/`, `scanner/`, `rory-bears/`: each app's page, with its privacy policy
  (`privacy/`) and help (`support/`), linked from the App Store.
- `byway/`: the Byway browser's page (the browser keeps its name until its own
  rename).
- `registry.json`: the signed registry of site names. Published automatically by the
  registry server; don't edit by hand (browsers verify its signatures and refuse
  changes).
- `updates/`: signed browser updates (later).
