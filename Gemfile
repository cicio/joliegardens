source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
ruby '2.1.1'
gem 'rails', '4.2.0'
group :development, :test do
  gem 'sqlite3', '~> 1.3.6'
  gem 'debugger'
  gem 'cucumber-rails', :require => false
  gem 'cucumber-rails-training-wheels'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'launchy'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'ZenTest'
  gem 'spring'
end

group :production do
  gem 'pg', '>= 0.15.0'
end

group :assets do
  gem 'therubyracer', platforms: :ruby
  gem 'sass-rails', '~> 4.0.5'
  gem 'coffee-rails', '~> 4.1.0'
  gem 'uglifier', '>= 1.3.0'
end

gem 'jquery-rails', '~> 4.0'

gem 'haml'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
group :doc do
  gem 'sdoc', '~> 0.4.0'
  gem 'redcarpet', '~> 3.1.2', platform: :ruby
  gem 'w3c_validators'
  gem 'kindlerb'
end

# Use ActiveModel has_secure_password
  gem 'bcrypt', '~> 3.1.7', require: false

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

