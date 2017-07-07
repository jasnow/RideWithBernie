source 'https://rubygems.org'

ruby '2.4.1'

gem 'rails', '5.1.2'

gem 'rails_admin'
gem 'rails_admin-i18n'
gem 'remotipart'
gem 'puma'
gem 'rollbar'

# For SMS / calls
gem 'twilio-ruby', '5.0.0.rc25'

# For link shortening
gem 'bitly'

# Store ENV variables in .env
gem 'dotenv-rails', :groups => [:development, :test]

# Front end asset management for realz!
gem 'bower-rails'

# Allow us to serve angular templates
gem 'angular-rails-templates'

# Use postgresql as the database for Active Record
gem 'pg'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '1.0.0.rc2' , group: :doc # LOCKED DOWN

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
