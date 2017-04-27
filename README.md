# cz-conventional-changelog-customizable

This is a fork of [`cz-conventional-changelog`](https://github.com/commitizen/cz-conventional-changelog) that allows for customization of the max line widths of the header and body separately.

To configure, create a `conventional-changelog.json` file in the root directory of the project with the following content:
```javascript
{
  "maxLineWidthHeader": 100, // defaults to 72
  "defaultMaxLineWidthBody": 100 // defaults to 80
}
```
Both fields are optional. If not provided, default values are used.

Part of the [commitizen](https://github.com/commitizen/cz-cli) family. Prompts for [conventional changelog](https://github.com/stevemao/conventional-changelog-angular/blob/master/index.js) standard.
