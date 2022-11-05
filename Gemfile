# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby(File.read(File.join(File.dirname(__FILE__), '.ruby-version')).strip)

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use postgresql as the database for Active Record
gem "pg", "~> 1.1"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Bundle and transpile JavaScript [https://github.com/rails/jsbundling-rails]
gem "jsbundling-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Bundle and process CSS [https://github.com/rails/cssbundling-rails]
gem "cssbundling-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

gem 'dry-validation'
gem 'reform', '~> 2.2.0', '>= 2.2.4'
gem 'simple_endpoint', '~> 1.0.0'
gem 'trailblazer', '~> 2.1'
gem 'jsonapi-serializer', '~> 2.1'
gem 'oj', '~> 3.11'
gem 'redis-rails'
gem 'rspec-rails', '~> 5.1.0'
gem 'rswag'

group :development, :test do
  gem "web-console"
  gem "rack-mini-profiler"
  gem 'awesome_print', '~>1.9.2'
  gem 'factory_bot_rails', '~> 6.1'
  gem 'ffaker', '~> 2.18'
  gem 'pry-byebug', '~> 3.9'
  gem 'pry-rails', '~> 0.3.9'

  # Code quality
  gem 'brakeman', '~> 5.2.1', require: false
  gem 'bundle-audit', '~> 0.1.0', require: false
  gem 'fasterer', '~> 0.9.0', require: false
  gem 'i18n-tasks', '~> 0.9.34', require: false
  gem 'lefthook', '~> 0.7.2', require: false
  gem 'rails_best_practices', '~> 1.20', require: false
  gem 'rubocop', '~> 0.93.1', require: false
  gem 'rubocop-performance', '~> 1.10', require: false
  gem 'rubocop-rails', '~> 2.9', require: false
  gem 'rubocop-rspec', '~> 1.43', require: false
end

group :development do
  gem 'letter_opener', '~> 1.7'
  gem 'listen', '~> 3.4'
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
end

group :test do
  gem 'fuubar', '~> 2.5.1'
  gem 'json_matchers', '~> 0.11.1', require: 'json_matchers/rspec'
  gem 'mock_redis', '~> 0.27.3'
  gem 'pundit-matchers', '~> 1.7.0'
  gem 'rails-controller-testing', '~> 1.0'
  gem 'rspec_junit_formatter', '~> 0.5.1'
  gem 'shoulda-matchers', '~> 4.5'
  gem 'simplecov', '~> 0.21.2', require: false
  gem 'simplecov-lcov', '~> 0.8.0', require: false
  gem 'webdrivers', '~> 4.6', require: false
  gem "capybara"
end
