---
title: About this Site
permalink: /about.html
nav_order: 5
---

# EUTC Constitution & Production Guidelines

This repository is used for collaborative editing of the Edinburgh University Theatre Company's important documents, constitution and production guidelines, with robust version tracking.

This is to be the authoritative copy of the constitution.

The 'main' branch is the official and currently in use branch and has been protected from pushes. Changes to this branch need to be agreed through standard constitution change processes, including being approved by committee/company as appropriate. Please use branches and forks for development.

On creation of a release, a Github action runs that automatically generates a combined PDF for both the constitution and production guidelines. This is to serve as a record if needed.

## Naming conventions

Releases: are to be tagged in reverse date order (`yyyy.MM.dd`) for the **latest** of any document contained within, with the title stating which documents were changed, e.g. `Constitution adopted dd.MM.yyyy` or `Constition and Production Guidelines adopted dd.MM.yyyy`

Do not change the names of the `*.md` files.

Line 3 of the `*.md` files should contain the line: `This version adopted dd.MM.yyyy`
