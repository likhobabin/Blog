# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require 'rake/rdoctask'
require 'rdoc/task'
require File.expand_path('../config/application', __FILE__)
require 'rake'

include Rake::DSL
Blog::Application.load_tasks
