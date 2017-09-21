# EUTC Constitution PDF creation

This site is using the NPM package `markdown-pdf` to convert any pushes
to the master branch to a formatted PDF which is linked to from the
website. This ensures the website always has an up to date copy of the
constitution.

This is configured as a Yarn package and is processed by TravisCI on push.

The `index.html` file in this directory is used as the HTML boilerplate into
which the constitution is rendered. This rendered document is then
converted to PDF by PhantomJS.
