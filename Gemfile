# frozen_string_literal: true

source 'https://rubygems.org'

gem 'bundler'
gem 'jekyll', '~> 3.8.6'
gem 'jekyll-paginate'
gem 'jekyll-sitemap'
gem 'jekyll-tagging'
gem 'minima', '~> 2.0'
gem 'rubocop'
gem 'scss_lint', require: false

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.6'
end

install_if -> { RUBY_PLATFORM =~ /mingw|mswin|java/ } do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
end

gem 'wdm', '~> 0.1.0', install_if: Gem.win_platform?
