source 'https://rubygems.org'

gem 'rails', '6.1.0'

ruby '2.7.2'

gem 'rails_admin'
gem 'rails_admin-i18n'
gem 'remotipart'
gem 'puma'
gem 'rollbar'

# For SMS / calls
gem 'twilio-ruby'

# For link shortening
gem 'bitly'

# Store ENV variables in .env
gem 'dotenv-rails'

# Front end asset management for realz!
gem 'bower-rails'

# Allow us to serve angular templates
gem 'angular-rails-templates'

# Use postgresql as the database for Active Record
#HID: gem 'pg' # HID on 10/3/2020
# Use SCSS for stylesheets
gem 'sassc-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .coffee assets and views
#HID: gem 'coffee-rails'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
  gem 'rspec-rails'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'
  gem 'pry'
end

group :production, :staging do
  gem "rails_12factor"
  gem "rails_stdout_logging"
  gem "rails_serve_static_assets"
end
