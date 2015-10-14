# A sample Gemfile
source "https://rubygems.org"

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'sass'
gem 'octopress'
gem 'jekyll-sitemap'

gem 'github-pages', versions['github-pages']

group :development do
  gem 'jekyll-docs'
end
