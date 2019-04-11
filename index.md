# Marp
The skinny framework for creating a slide deck from Markdown

---

## Markdown to Marp
* Start with a markdown file 
* Add YAML frontmatter
* Ensure page breaks/separators `\r\n --- \r\n`
* Convert w/ CLI tool (`npm i -D @marp-team/marp-cli`)

<!--
npx marp demo.md --preview
npx marp demo.md
npx marp demo.md --pdf
-->

---

## Make it automatic
* Netlify <!-- (could also use Now, Heroku, etc) -->
* Ensure npm can build it <!-- something, something puppeteer.js -->
* Add a config file to make it easy
* Push to github
---

## Use VSCode
* Marp plugin
* Preview mode!

---

# Thanks