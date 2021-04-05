# Change history for stripes-webpack

## [1.2.0](https://github.com/folio-org/stripes-webpack/tree/v1.2.0) (2021-04-05)

* If translations exist in a `/compiled` subdirectory, then they will be preferred as the translations to use in the final bundle. Refs STCLI-158.

## [1.1.0](https://github.com/folio-org/stripes-webpack/tree/v1.1.0) (2021-02-03)

* Remove support for `hardsource-webpack-plugin`. Refs STCOR-421, STCOR-510.
* Add `locateCssVariables` to `postcss-loader` loader. Refs STCOR-511.
