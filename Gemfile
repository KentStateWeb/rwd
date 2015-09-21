source 'https://rubygems.org'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'hpricot'
gem 'guard'
gem 'guard-jekyll-plus'
gem 'guard-livereload'