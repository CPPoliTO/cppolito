# CPPoliTO

This is the repository for the website of the Competitive Programming PoliTO
Team (CPPoliTO).

[![Netlify Status](https://api.netlify.com/api/v1/badges/eab5a36d-d612-4909-bee9-e8fac540987e/deploy-status)](https://app.netlify.com/sites/cppolito/deploys)

## How is this website written?

This is a static website, and it has been written in plain HTML/CSS, no
framework or JavaScript has been used.

## Repository structure

The repository is structured in the following way:

```
cppolito
|
|- fonts
|- imgs
|- site
   |
   |- en
      |- ...
   |- it
      |- ...
|- index.html
|- style.css
|- ...
```

The site is divided into two macro-directories: en and it, since this website is
written both in English and Italian. The main language is Italian (the
`index.html` file is in Italian).

The directories `fonts` and `imgs` should be refactored in a single `assets`
directory, with local (e.g.: of a single page) assets positioned in the page
directory.
