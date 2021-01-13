# Angular CLI 11.x - Source Maps issue on extract-i18n

1. Run `npm install`
1. Run `ng extract-i18n`

Error message:
```
Warning: ./node_modules/@progress/kendo-angular-common/__ivy_ngcc__/dist/fesm5/index.js
Module Warning (from ./node_modules/@angular-devkit/build-angular/src/extract-i18n/ivy-extract-loader.js):
(Emitted value instead of an instance of Error) Unable to fully load /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-common/__ivy_ngcc__/dist/fesm5/index.js for source-map flattening: Circular source file mapping dependency: /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-common/__ivy_ngcc__/dist/fesm5/index.js.map -> /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-common/__ivy_ngcc__/dist/fesm5/index.js.map

Warning: ./node_modules/@progress/kendo-angular-l10n/__ivy_ngcc__/dist/fesm5/index.js
Module Warning (from ./node_modules/@angular-devkit/build-angular/src/extract-i18n/ivy-extract-loader.js):
(Emitted value instead of an instance of Error) Unable to fully load /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-l10n/__ivy_ngcc__/dist/fesm5/index.js for source-map flattening: Circular source file mapping dependency: /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-l10n/__ivy_ngcc__/dist/fesm5/index.js.map -> /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-l10n/__ivy_ngcc__/dist/fesm5/index.js.map

Warning: ./node_modules/@progress/kendo-angular-upload/__ivy_ngcc__/dist/fesm5/index.js
Module Warning (from ./node_modules/@angular-devkit/build-angular/src/extract-i18n/ivy-extract-loader.js):
(Emitted value instead of an instance of Error) Unable to fully load /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-upload/__ivy_ngcc__/dist/fesm5/index.js for source-map flattening: Circular source file mapping dependency: /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-upload/__ivy_ngcc__/dist/fesm5/index.js.map -> /tmp/ng11-sourcemaps/node_modules/@progress/kendo-angular-upload/__ivy_ngcc__/dist/fesm5/index.js.map
```
