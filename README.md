# hosted-my-subscriptions-themes-sass

Package of Sass themes, designed to be compiled and run externally to the hosted My Subscriptions widget.

## How to use

1. Choose the `'blank'` theme in the widget configuration for the hosted My Subscriptions widget.

2. Include and compile the `scss` code form the `/src` folder of this project, starting with the `/src/scss/theme-base.scss` file.

3. Load the compiled css code/file before the hosted My Subscriptions JavaScript file has been loaded on the page. For example towards the bottom of the `<head>` section of your page.
