# frozen_string_literal: true

require 'bundler/gem_tasks'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:rspec)

require 'rubocop/rake_task'

RuboCop::RakeTask.new

task default: %i[rspec rubocop]
