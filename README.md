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

Then vist [http://localhost:4000/](http://localhost:4000/) in a browser.  The site should automatically reload as you change the content.
