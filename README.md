# Ejs Plain Template

Basic EJS template for making statis pages.

## Built With
* HMR
* Babel
* Sass
* Sass resources (variables and mixins auto included)
* Autoprefixer
* Cross env


## Setup

```
    $ git clone https://github.com/DrBoria/ejs-plain-template.git
    $ cd ./ejs-plain-template
    $ npm install 
    $ npm start
```

## Development

If you want to add new page write link on it inside webpack.config.js in customHtmlWebpackPlugin()

Example:
```
    customHtmlWebpackPlugin({
      filename: "page2.html",
      template: "./src/views/pages/page2.ejs",
    }),
```


## Build

```
  npm run build
```

Build in 'build' folder.
By default all is minified. Css and js separately.