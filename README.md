# The r9y.dev website

This repository contains the code for the website hosted at [r9y.dev](https://r9y.dev).

If you want to make changes to the map, you need to look at [this repository instead](https://github.com/r9y-dev/r9y-map).

## Local Development

If you want to make changes to the website, fork this repository, make your changes, and then [submit a pull request](https://github.com/r9y-dev/site/pulls).

### Testing locally

To test this site locally, run the following commands:

```bash
bundle install
bundle exec jekyll s -w --verbose --livereload
```

If you're running on a remote instance you can run to bind to all interfaces:

```bash
bundle install
bundle exec jekyll s -w --verbose --livereload --host=0.0.0.0
```

Then vist [http://localhost:4000/](http://localhost:4000/), or [http://yourhostname:4000](http://yourhostname:4000) in a browser.  The site should automatically reload as you change the content.

Note, this requires the ruby and ruby-dev packages installed, eg. on Ubuntu:

```bash
apt install ruby ruby-dev ruby-bundler
```

