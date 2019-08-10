`npm install webpack --save-dev`

install webpack CLI
`npm install webpack-cli --save-dev`

using CLI to create a bundle on current project (mode production or development)
`npx webpack --entry ./index.js --output ./bundle.js --mode development`

the above command can be located on a configuration file named 'webpack.config.js'

#CSS LOADER

Adding css loader to webpack config.
First, intall css integration
`npm i --save-dev css-loader`
`npm i --save-dev style-loader`

Second, add this module to webpack config and add a css rule.