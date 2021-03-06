# Jekyll blog starter by [Prettystack](http://prettystack.com)

## Description

This is a starter kit to build a [Jekyll](http://jekyllrb.com) powered blog in a matter of minutes. It contains optional integration to external services such as Disqus, Google Analytics, Facebook, ... This starter kit comes with a superb theme by [HTML5 UP](http://html5up.net/) and some placeholder content from the [Gutenberg project](http://www.gutenberg.org/).

Make sure to check out all our [starter kits](https://github.com/prettystack/), we will soon have starter kits for corporate website and admin interface.

### Preview
[![Striped Preview](http://prettystack.com/img/60964924.donquiblog3.png)](http://prettystack.github.io/jekyll-blog-starter)

Browse the [live preview](http://prettystack.github.io/jekyll-blog-starter) hosted on Github Pages.

## Getting started

* Clone repository (`git clone https://github.com/prettystack/jekyll-blog-starter.git`)
* Install Ruby and Bundler
* Install project dependencies with `bundle install`
* Launch test server `jekyll serve --watch --config _config.yml,_themes/striped/_config.yml`
* Browse the site at [localhost:4000](http://localhost:4000)
* If necessary you can [migrate your existing blog](http://jekyllrb.com/docs/migrations/)
* Remove placeholder text and images from `_posts` and `images` folders
* Customize your `_config.yml` (see configuration below)
* Add new markdown files in the `_posts` directory to create posts


## Configuration

Read the commented `_config.yml` file for basic configuration.

### Theme selection

You must load the theme configuration in addition to the standard `_config.yml` file when you launch Jekyll. The extra configuration is located in the theme subdirectory (for instance: _themes/striped/_config.yml).

```bash
$ jekyll serve --watch --config _config.yml,themes/striped/_config.yml
```

### Disqus integration

Add your disqus shortname in *_config.yml* to enable disqus threads. For correct display, go to [settings/general](http://disqus.com/admin/settings/general/) and only keep numbers in "Comment Count Link".


### Google analytics

Create an account at [google analytics](http://www.google.com/analytics/), and add your tracking ID (should look like UA-12345678-1) in your `_config.yml`.

### Google webmaster

Add your [google webmaster](https://www.google.com/webmasters/) verification code in your `_config.yml`.


## Deployment

### Github Pages

Edit the variables in the `Rakefile` to set your Github repository, then you can issue a `rake deploy:github`


## Credits

### Jekyll

* [Jekyll](http://jekyllrb.com) static site generator. (MIT license)
* Some pages and ideas from [Jekyll-bootstrap](http://jekyllbootstrap.com/) (MIT license), [Jekyll-incorporated](https://github.com/kippt/jekyll-incorporated) (MIT license), [Hpstr-jekyll-theme](https://github.com/mmistakes/hpstr-jekyll-theme) (GPL)

### Theme

* *Striped!* theme from [HTML5 UP](http://html5up.net/) (Creative Commons Attribution 3.0).
* Syntax highlighting from [coderay github theme](https://github.com/danielpietzsch/CodeRay-GitHub-Theme)

### Placeholders

* Text: "The Ingenious Gentleman Don Quixote of La Mancha" by Miguel de Cervantes (public domain)
* Illustrations by Gustave Doré (public domain)
* Public domain novel made available by the [Gutenberg project](http://www.gutenberg.org/)


## License

See `LICENSE`.
