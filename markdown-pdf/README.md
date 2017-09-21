# EUTC Constitution PDF creation

This site is using the NPM package `markdown-pdf` to convert any pushes
to the master branch to a formatted PDF which is linked to from the
website. This ensures the website always has an up to date copy of the
constitution.

Pushes to `master` will trigger a build of the PDF by Travis CI, with the
resultant PDFs being published as a "Release" on this repository.
