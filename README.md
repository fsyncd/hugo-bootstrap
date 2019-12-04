# Hugo Bootstrap

Batteries included site template that enables building static sites using Hugo and Bootstrap 4.x.

## Includes

* Dependency management using npm.
* Asset bundling using webpack.
* SCSS stylesheet support using PostCSS.
* Hot reloading support.
* Bootstrap theme support.

## Usage

### Prerequisites

You will need [hugo](https://gohugo.io/) and the latest LTS releases of [node](https://nodejs.org/en/) and [npm](https://www.npmjs.com/) installed.

To use Hugo Bootstrap, first clone the repository, and then run:

```
npm install
```

This will take some time and will fetch [Bootstrap](https://getbootstrap.com/), it's dependencies, and all the required tools.

### Development

While working on developing your Hugo site, run:

```
npm run preview
```

This will launch a Hugo development server with hot reloading support. The preview command should 
result in a new browser window being opened to your site, but if this fails, visit 
[http://localhost:3000](http://localhost:3000). The development server will automatically reload when
it detects stylesheet or content changes.

### Release

To build a release version of your Hugo site, run:

```
npm run build
```

This command will populate the `/dist` folder with the static content of your Hugo site.

## Folders

```
|--site                // Everything in here will be built with hugo
|  |--content          // Pages and collections - ask if you need extra pages
|  |--data             // YAML data files with any data for use in examples
|  |--layouts          // This is where all templates go
|  |  |--partials      // This is where includes live
|  |  |--index.html    // The index page
|  |--static           // Files in here ends up in the public folder
|--src                 // Files that will pass through the asset pipeline
|  |--js               // Javascript sources for webpack bundling
|  |--scss             // SCSS sources for webpack bundling
|  |--index.js         // index.js is the webpack entry for your css & js assets
```

## Todo

* Hugo shortcodes for Bootstrap UI components.
* Common Bootstrap layouts.

## Acknowledgements

This site template was inspired by [victor-hugo](https://github.com/netlify-templates/victor-hugo) from Netlify.
