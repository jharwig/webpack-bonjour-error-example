# webpack-bonjour-error-example
https://github.com/webpack/webpack-dev-server/issues/1481

# Steps to Reproduce

1. `npm install`
1. `cd project-1 && ../node_modules/.bin/webpack-dev-server --hot --inline --bonjour`
1. In new terminal while first is running:

    `cd project-2 && ../node_modules/.bin/webpack-dev-server --hot --inline --bonjour`
    
