require 'rubygems'
require 'appraisal'
require 'bundler/setup'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new(:spec)

task :default do
  exec 'rake appraisal spec'
end
