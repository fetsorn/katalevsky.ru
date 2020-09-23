# katalevsky.ru
Built with Hugo, Fomantic-UI, GitLab, Netlify

## Fomantic-UI
Resides in `static/semantic`
 - Current customizations
``` js
/* static/semantic/src/theme.config */
@feed : 'timeline';

/* static/semantic/src/site/globals/site.variables */
@fontName : 'Open Sans';
```
 - To update fomantic
``` sh
# Update fomantic
$ npm update fomantic-ui

# Go into the build directory
$ cd static/semantic/

# Rebuild
$ npx gulp build
```
## Forms to Google Sheets
forms tied to google sheets with this
[Awesome solution by Jamie Wilson](https://github.com/jamiewilson/form-to-google-sheets)
