# Flowable Website

We use [Jekyll](http://jekyllrb.com/) to build the site using ([mostly](http://zpao.com/posts/adding-line-highlights-to-markdown-code-fences/)) Markdown, and we host it by pushing HTML to [GitHub Pages](http://pages.github.com/).

## Installation

If you are working on the site, you will want to install and run a local copy of it.

### Dependencies

In order to use Jekyll, you will need to have Ruby installed.

 - [Ruby](http://www.ruby-lang.org/) (version >= 1.8.7)
 - [RubyGems](http://rubygems.org/) (version >= 1.3.7)
 - [Bundler](http://gembundler.com/)

Mac OS X comes pre-installed with Ruby, but it's preferable to use [rbenv](https://github.com/sstephenson/rbenv) to install Ruby.

```sh
$ brew update
$ brew install rbenv
$ rbenv install 2.3.1
$ rbenv global 2.3.1
$ ruby -v
```

Once you have RubyGems and installed Bundler (via `gem install bundler`), use it to install the dependencies:

```sh
$ bundle install # Might need sudo.
```

### Instructions
Use Jekyll to serve the website locally (by default, at `http://localhost:4000`):

```sh
$ bundle exec jekyll serve -w
$ open http://localhost:4000
```
