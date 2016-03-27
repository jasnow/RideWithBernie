# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks

begin
  require 'rspec/core/rake_task'
  task default: :spec
rescue LoadError
  puts 'This error is happening most likely because you are on Heroku, if locally check your rspec path.'
end
