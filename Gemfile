# A sample Gemfile
source "https://rubygems.org"

# gem "rails"
gem "jekyll"

#group :jekyll_plugins do
gem "jekyll-multiple-languages-plugin"
#end

#gem "kramdown"

# Github pages

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
