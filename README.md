# Middleman 3.0.x Project Template: HTML Email Boilerplate HAML

HTML Email Boilerplate HAML is the [HTML5 Boilerplate 0.5](http://htmlemailboilerplate.com/) adapted as a HAML Middleman 3.x project template, optimized for rapid development.

Using [Bundler](http://gembundler.com/) and [RVM](https://rvm.io/) is **highly** recommended.

Features:

* Uses the [HTML5 Boilerplate 0.5](http://htmlemailboilerplate.com/), converted to a Middleman/HAML workflow.
* [Middleman Livereload](https://github.com/middleman/middleman-livereload): enabled for the generic 'middleman' command by default
* RVM-ready
* Some good `.gitignore` defaults

## Usage

Download and install into ~/.middleman (you'll have to create this directory if it's not already there). You can then use it with the `--template` flag on `middleman init`. 

### Example

1. [Download](https://github.com/dannyprose/Middleman-HTML-Email-HAML/zipball/master)/clone to: `~/.middleman/htmlemailbp/`
2. Then create your new Middleman project: `middleman init my_new_project --template=htmlemailbp`

For more help follow [Middleman's project template instructions](http://middlemanapp.com/getting-started/welcome/).

## Recommendations

* In your source, keep style files organized seperately, but included in your layout file using partials and `<style>` tags.
* After you use `middleman build`, use [Premailer](http://premailer.dialect.ca/) to preflight your email and automatically inline all styles. Add this file to your repo in the `/build/` folder. I use filename `index-prelight.html`.
* Test with [Litmus](http://www.litmus.com/)