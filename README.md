# CYBER Mission Award Website

This website was built using the Jekyll Serif theme:
https://github.com/zerostaticthemes/jekyll-serif-theme

## Local development

Requires Ruby 3.0+ (the macOS system Ruby is too old). On macOS:

```sh
brew install ruby
export PATH=/opt/homebrew/opt/ruby/bin:$PATH
gem install bundler
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve
```

The site is then served at http://localhost:4000 and rebuilds on changes. The compiled `_site/`, `vendor/`, `.bundle/` and `Gemfile.lock` are git-ignored.
