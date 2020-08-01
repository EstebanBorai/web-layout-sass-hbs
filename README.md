<div align="center">
  <img 
    src="https://avatars3.githubusercontent.com/u/19378685?s=120&v=4"
    height="120"
    width="120"
  />
  <h1>web-layout-sass-hbs</h1>
  <span>Webpack template with Handlebars and Sass ready for layout development</span>
</div>

## Getting Started

```bash
# clone the repository replacing "project name" with your projects name
git clone https://github.com/estebanborai/web-layout-sass-hbs.git <project name>

# step into the directory
cd ./web-layout-sass-hbs

# install dependencies
yarn

# run the development server and write the code!
yarn start

# build your bundle
yarn build
```

## Scripts

### Bundle with yarn

```
yarn build
```

### Bundle with npm

```
npm run build
```

## Whats inside?
Webpack configuration using css-loader, sass-loader and style-loader to handle your style files. Also brings handlebars-loader so you are able to take advantage of the power of handlebars to build your layout!

## PostCSS
PostCSS is ready to use, in order to add plugins you must create a file called postcss.config.js, read more in the PostCSS official website! Visit PostCSS website.

## Bundle
When running either yarn build or npm run build, 3 files will be generated in your dist/ directory. These files contains all your markdown in one place, feel free to open index.html either will your favorite browser or with an HTTP server!

```
. dist/
├── index.html
├── main.js
├── main.css
```

## Contributions
Contributions to this repository are welcome, feel free to open either an Issue or Pull Request.

## License
Licensed under the MIT License
