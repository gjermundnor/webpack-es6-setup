# Basic Webpack config with React ES6 setup
Just a really basic setup to get started. 
Made for personal use and preferences, but free for anyone to clone and use.

## Getting started
1. `npm install`
2. Bundle
  - Dev server `npm start`
  - Production build `npm run build`
3. Visible at `localhost:8080` or `localhost:8080/webpack-dev-server/`
4. Should output: `It works!`

## Add support for SASS
Install dependencies 
`npm install css-loader node-sass sass-loader style-loader --save-dev`

Update webpack.config
```
{
  test: /\.scss$/,
  loaders: ['style-loader', 'css-loader', 'sass-loader']
}
```
