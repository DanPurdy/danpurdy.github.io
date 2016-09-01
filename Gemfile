source "https://rubygems.org"
ruby RUBY_VERSION


require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'octopress-autoprefixer'
gem 'github-pages', versions['github-pages']
