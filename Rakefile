# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks

desc 'a custom task can go here'
namespace :aa do
  task :aaa do
    puts "a custom rake task can go here"
  end
end
