source 'https://rubygems.org'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

# Database
gem 'sqlite3'

# Feeds
gem 'feedjira'
gem 'feedvalidator'

# Background Processing
gem 'sinatra', require: nil
gem 'sidekiq'
gem 'sidetiq'

# DB Migrations
gem 'hobo_fields'

# Forms
gem 'simple_form'

# HAML
gem 'haml-rails'

# Decorators
gem 'draper'

# Authentication
gem 'devise'

# File Upload
gem 'carrierwave'

# Internationalization
gem 'i18n-tasks'

# Pagination
gem 'kaminari'

group :development do
	gem "erb2haml"
  # Errors
  gem 'better_errors'
  gem 'binding_of_caller'
  # Debugger
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-byebug' unless Gem.win_platform?
end

# Testing
group :test, :development do
	gem 'rspec-rails'
	gem 'cucumber-rails', require: false
	gem 'factory_girl_rails'
end

# Backend
# gem 'activeadmin'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'sass'
  gem 'bootstrap-sass'

  gem 'uglifier', '>= 1.0.3'
  gem 'coffee-rails'
  # Front-End framework
  gem 'therubyracer', :platforms => :ruby
  gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'
  gem 'autoprefixer-rails'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
