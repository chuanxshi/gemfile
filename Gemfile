source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '3.0.1'

# To use Twiter Boostrap
# gem 'bootstrap-sass', '2.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

# To use faker generate fake data: names, addresses, phone numbers, etc.
# gem 'faker', '1.0.1'

gem 'jquery-rails'

# Pagination 
# gem 'will_paginate', '3.0.3'
# gem 'bootstrap-will_paginate', '0.0.5'

# File upload
# gem "paperclip", "~> 3.0"
# gem 'carrierwave'

group :development do
  gem 'sqlite3'
  gem 'annotate', '~> 2.4.1.beta'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :test, :development do
  gem 'rspec-rails', '2.9.0'
  gem 'guard-rsepc', '0.5.5'
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.0'

group :test do
  gem 'capybara', '1.1.2'
  gem 'factory_girl_rails', '1.4.0'
  gem 'cucumber-rails', '1.2.1', require: false
  gem 'database_cleaner', '0.7.0'
end

group :production do
  gem 'pg', '0.12.2'
end