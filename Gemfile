source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby File.read('.ruby-version').strip

gem "rails", "~> 7.0.6"

gem "cssbundling-rails"
gem 'draper', '~> 4.0', '>= 4.0.2'
gem "jbuilder"
gem "jsbundling-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "redis", "~> 4.0"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem 'annotate', '~> 3.2'
  gem 'dotenv-rails', '~> 2.8', '>= 2.8.1'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 3.2'
  gem 'pry-byebug', '~> 3.10', '>= 3.10.1'
  gem 'pry-rails', '~> 0.3.9'
  gem 'shoulda-matchers', '~> 5.3'
  gem 'rspec-rails', '~> 6.0', '>= 6.0.3'
end

group :development do
  gem "awesome_print", require:"ap"
  gem 'better_errors', '~> 2.10', '>= 2.10.1'
  gem 'binding_of_caller', '~> 1.0'
  gem 'brakeman', '~> 6.0'
  gem 'i18n-tasks', '~> 1.0', '>= 1.0.12'
  gem 'listen', '~> 3.8'
  gem 'rails_best_practices', '~> 1.23', '>= 1.23.2'
  gem 'readapt'
  gem 'reek', '~> 6.1', '>= 6.1.4'
  gem 'rubocop-rails', '~> 2.20', '>= 2.20.2'
  gem 'rubocop-rootstrap', '~> 1.2'
  gem 'spring', '~> 4.1', '>= 4.1.1'
end

group :test do
  gem "capybara"
  gem 'database_cleaner', '~> 2.0', '>= 2.0.2'
  gem 'pg_query', '~> 4.2', '>= 4.2.1'
  gem 'prosopite', '~> 1.3', '>= 1.3.2'
  gem "selenium-webdriver"
  gem 'simplecov', '~> 0.22.0'
  gem "webdrivers"
  gem 'webmock', '~> 3.18', '>= 3.18.1'
end
