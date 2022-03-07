# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.3'
gem 'rails', '6.1.4.6'

# Use postgresql as the database for Active Record
gem 'pg', '~> 1.3'

# Use Puma as the app server
gem 'puma', '~> 5.6'

# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.4'

# Turbo makes navigating your web application faster. Read more: https://github.com/hotwired/turbo-rails
gem 'turbo-rails', '~> 1.0'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '~> 1.10', require: false

# Template Engine
gem 'slim-rails', '~> 3.3'

# App monitoring
gem 'newrelic_rpm', '~> 8.5'

group :development, :test do
  gem 'byebug', '~> 11.1', platforms: %i[mri mingw x64_mingw]
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 2.20'
  gem 'pry', '~> 0.13.1'
  gem 'pry-byebug', '~> 3.9'
  gem 'pry-rails', '~> 0.3.9'
  gem 'rspec-rails', '~> 5.1'
  gem 'rubocop', '~> 1.25', require: false
  gem 'rubocop-performance', '~> 1.13', require: false
  gem 'rubocop-rails', '~> 2.13', require: false
  gem 'rubocop-rspec', '~> 2.9', require: false
  gem 'slim_lint', '~> 0.22.1', require: false
end

group :development do
  gem 'listen', '~> 3.7'
  gem 'spring', '~> 2.1'
  gem 'spring-commands-rspec', '~> 1.0'
  gem 'spring-watcher-listen', '~> 2.0'
  gem 'web-console', '~> 4.2'
end

group :test do
  gem 'capybara', '~> 3.36'
  gem 'email_spec', '~> 2.2'
  gem 'selenium-webdriver', '~> 4.1'
  gem 'simplecov', '~> 0.21.2', require: false
  gem 'simplecov-lcov', '~> 0.8.0', require: false
  gem 'webmock', '~> 3.14', require: false
end

group :staging, :production do
  gem 'rack-timeout', '~> 0.6.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', '~> 1.2019', platforms: %i[mingw mswin x64_mingw jruby]
