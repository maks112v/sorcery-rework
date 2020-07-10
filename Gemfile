# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# TODO: Does having the Gemfile setup this way make sense?

gem 'rails'

group :rubocop do
  gem 'rubocop', '~> 0.87.0'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'
end

group :test do
  gem 'rspec'
  gem 'rspec-rails'
end
