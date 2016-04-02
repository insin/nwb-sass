# cherta-nwb-sass

Plugin enabling a [Sass](http://sass-lang.com/) loading pipeline for `.scss` and `.sass` files in [nwb](https://github.com/insin/nwb) using [sass-loader](https://github.com/jtangelder/sass-loader).

I'm releasing this package because the PR I made to the original repo was not accepted and I need it for a project. It is not my intention to maintain this package and will erase it as soon as the original project accepts the PR or solved the `.saas` loading issue.

## Usage

Install in a project you're using nwb to develop and nwb will detect and load the plugin:

```
npm install --save-dev cherta-nwb-sass
```

**Note:** if node-sass has trouble installing binaries on your platform, [pre-built binaries can be found here](https://github.com/sass/node-sass-binaries) and should be placed in `node-sass/vendor/` (inside your `node_modules/`) as `binding.node`.
