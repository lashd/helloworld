# encoding: utf-8

require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "helloworld"
  gem.homepage = "http://github.com/lashd/helloworld"
  gem.license = "MIT"
  gem.summary = "summary"
  gem.description = "longer description"
  gem.email = "leon_a_d@yahoo.com"
  gem.authors = ["lashd"]
  # dependencies defined in Gemfile
end


task :default => :test
