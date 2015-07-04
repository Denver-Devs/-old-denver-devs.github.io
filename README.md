# denver-devs.github.io
> Denver developers lil website

This site is built using Jekyll and hosted on GitHub Pages.

## Contribute

### Setup
You will need Jekyll and the `github-pages` gems.

Jekyll is the static site generator that builds the content files and templates into HTML files.

    gem install jekyll

The `github-pages` gem maintains a local Jekyll environment that is compatible with GitHub Pages. You may use `bundler` or `gem install` directly.

    bundle install

or

    gem install github-pages

### Running the site

Use `jekyll` to preview the site:

    jekyll serve

The site will build into the `_site` path and be hosted at `localhost:4000`.
