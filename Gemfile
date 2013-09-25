source 'https://rubygems.org'

gem 'rails', '3.2.13'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'devise'
gem 'haml-rails'
gem 'bson_ext'
gem 'mongoid'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'less-rails'
  gem 'sass-rails',   '~> 3.2.3'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
	gem 'twitter-bootstrap-rails', '2.1.3'
  gem 'uglifier', '>= 1.0.3'
end

gem 'ember-rails'
gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
gem 'unicorn'

# Deploy with Capistrano
gem 'capistrano'
gem 'capistrano_colors'

gem 'rspec-rails', :group => [:development, :test]
gem 'dotenv-rails', :groups => [:development, :test]

group :development do
	gem 'pry'
	gem 'pry-nav'
	gem 'rspec-rails'
end

group :test do
  gem 'turn', :require => false
  gem 'database_cleaner', '1.0.1'
  gem 'mongoid-rspec'
  gem 'factory_girl_rails', '~> 3.5.0'
end