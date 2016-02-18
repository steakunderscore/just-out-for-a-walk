source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

ruby versions['ruby']

# This depends on everything needed
gem 'github-pages', versions['github-pages']

group :development do
  gem 'octopress'
  gem 'jekyll-docs'
end
