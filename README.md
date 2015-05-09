# jekyll-gulp-optimizations | Getting you to a Google PageSpeed Insights score of 100

This is an adaption and extension of a already very good gulp script from Steve Edson's post [Automating optimisations with Gulp](https://steveedson.co.uk/gulp/advanced-tasks/).

## For further explenation take a look at [my blog post about it.](https://www.dimitrikoenig.net/scoring-100-on-googles-pagespeed-insights.html)

## Installation

1. Clone this repo and move the files into your jekyll root folder
2. Edit the gulpconfig.json file and place your server and cloudflare credentials in there
3. run `npm install gulp -g` to install gulp globally and be able to run `gulp` commands
4. run `npm install` to install all needed dependencies
5. run `gulp deploy` to do the whole build and deploy to your server

## Available commands

### gulp deploy

Builds and deploys all files to your server

### gulp dry-run

Builds without deploying all files to your server, for testing reasons. You can run `jekyll serve` and do a parallel `gulp dry-run` command to see how your local output will look like.

### gulp raw-deploy

Does to normal `jekyll build` and deploys directly to your server, without any optimizations.