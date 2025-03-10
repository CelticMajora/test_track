source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.4'
# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'mini_racer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

gem 'puma', '~> 5.6'
gem 'nokogiri'

gem 'responders'

gem 'rack-timeout'

gem 'airbrake', '~> 7.3.5', require: false
gem 'sentry-raven', require: false

gem 'newrelic_rpm'
gem 'ddtrace'

gem 'rails_semantic_logger', require: false

gem 'devise'
gem 'omniauth-saml'
gem 'omniauth-rails_csrf_protection'

gem 'simple_form'

gem 'paperclip', '~> 5.2'
gem 'aws-sdk', '~> 2.3.0'

gem 'attribute_normalizer', '~> 1.2.0'
gem 'style_closet', path: 'vendor/gems/style-closet'

gem 'foreman'
gem 'delayed_job'
gem 'delayed_job_active_record'

gem 'with_transactional_lock'

gem 'bootsnap', '>= 1.3.0', require: false

group :development, :test do
  gem 'simplecov', require: false
  gem 'pry-rails'
  gem 'pry-remote'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails'
  gem 'rubocop-betterment'

  gem 'dotenv-rails'

  gem 'poltergeist'
  gem 'site_prism'
  gem 'selenium-webdriver'
  gem 'database_cleaner'

  gem 'factory_bot_rails'

  gem 'ruby_spec_helpers', path: 'vendor/gems/ruby_spec_helpers'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '>= 3.3.0'
  gem 'travis', '~> 1.8.0'
  gem 'listen', '~> 3.1.5'
end

group :test do
  gem 'shoulda-matchers'
  gem 'timecop'
  gem 'db-query-matchers'
end
