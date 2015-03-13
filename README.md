## marionette-nunjucks

This is a simple adaptation of `Marionette.Renderer` to work with [Nunjucks](http://mozilla.github.io/nunjucks/) templating engine (instead of the default [Underscore](http://underscorejs.org/#template) templates).

It is assumed that the [slim version](https://github.com/mozilla/nunjucks/tree/master/browser) of Nunjucks is being used (which work only with precompiled templates). Make sure the precompiled templates are loaded before they are used, otherwise you'll have a `NunjucksError: template not found`.

More details:

 - Read the "Getting started" section in the Nunjucks webpage: http://mozilla.github.io/nunjucks/getting-started.html

 - Read the "Browser usage" in the Nunjucks API documentation (detailed information on how to use Nunjucks in the browser): http://mozilla.github.io/nunjucks/api.html#browser-usage

 - Checkout the grunt-nunjucks task to automatically precompile templates on changes: https://github.com/jlongster/grunt-nunjucks

