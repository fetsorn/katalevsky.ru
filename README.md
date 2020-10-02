# katalevsky.ru

Built with Hugo, Fomantic-UI, GitLab, Netlify
Written with Emacs org-mode

## Fomantic-UI

CSS styles and jQuery come from [Fomantic-UI](https://fomantic-ui.com/)
All source files are in `static/semantic`

- Current customizations to fomantic

```js
/* static/semantic/src/theme.config */
@feed : 'timeline';

/* static/semantic/src/site/globals/site.variables */
@fontName : 'Open Sans';
```

- To update fomantic

```sh
# Update fomantic
$ npm update fomantic-ui

# Go into the build directory
$ cd static/semantic/

# Rebuild
$ npx gulp build
```

## Forms to Google Sheets

Forms are connected to google sheets using this [awesome solution by Jamie Wilson](https://github.com/jamiewilson/form-to-google-sheets)
Data is being sent to a [spreadsheet](https://docs.google.com/spreadsheets/d/1hE_e0UPqLOP-UWG4vtwaXDxDm52pokYuooXxCrombpA/edit?usp=sharing)
This spreadsheet is stored at divisol.company@gmail.com Google Drive "My Drive/personal/katalevsky.ru/katalevsky.ru"

## Netlify

This website is hosted at divisol.company@gmail.com Netlify account

## Forestry.io

Templated for editing Hugo content are at divisol.company@gmail.com Forestry.io account
Here's instruction

## org-mode

All source files have been generated from `org/hugo.org` using org-tangle
You can ignore this and edit files in `content/` and `layouts/` directly
