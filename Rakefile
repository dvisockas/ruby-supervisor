require 'rubygems'
require 'bundler/setup'
require "bundler/gem_tasks"
require "rspec/core/rake_task"

task :default => :spec
task :rspec => :spec

desc "Run all specs"
RSpec::Core::RakeTask.new(:spec) do |t|
  t.rspec_opts = %w[--color]
  t.verbose = false
end

