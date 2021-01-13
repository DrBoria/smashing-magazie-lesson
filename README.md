Basic template with EJS templates

Additional features:
. Babel
. Sass
. HMR
. Autoprefixer
etc.

## Setup

```
    $ git clone https://github.com/DrBoria/landing_template
    $ cd ./website_boilerplate
    $ npm install 
    $ npm start
      or
    $ yarn install
    $ yarn start
```

Added ejs-plain-loader for fixing issue with package update
```
Info about syntax (https://www.npmjs.com/package/ejs-plain-loader)
````

## Development

If you want to add new page write link to it inside webpack.config.js in customHtmlWebpackPlugin()

Example:
```
    customHtmlWebpackPlugin({
      filename: "page2.html",
      template: "./src/views/pages/page2.ejs",
    }),
```
