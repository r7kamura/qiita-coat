# qiita-coat
The UI components for Qiita.

## Install
```
$ bower install qiita-coat --save
```

## Usage
```scss
// Import all files
@import "qiita-coat/scss/all";

// Or import individual files
@import "qiita-coat/scss/variables";
@import "qiita-coat/scss/mixins";
```

## Development
There are some npm tasks for developers.

### npm run setup
Set up your environment to develop this project.

```
$ npm run setup
```

### npm run build
Build JavaScripts and Stylesheets.

```
$ npm run build
```

### npm run server
Launch a development server on http://127.0.0.1:9292.

```
$ npm run server
```

### npm run build-pages
Build static files into ./build directory.

```
$ npm run build-pages
```

### npm run deploy-pages
Push static files in ./build directory for GitHub Pages.

```
$ npm run deploy-pages
```
