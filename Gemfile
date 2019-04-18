# frozen_string_literal: true

source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/dry-rb/#{repo_name}" }

gemspec

gem 'dry-logic', github: 'dry-logic', branch: 'master'
gem 'dry-types', github: 'dry-types', branch: 'master'

group :test do
  gem 'dry-monads', require: false
  gem 'i18n', require: false
  gem 'simplecov', require: false, platform: :mri
  gem 'transproc'
end

group :tools do
  gem 'pry'
  gem 'pry-byebug', platform: :mri
  gem 'redcarpet', platform: :mri
end

group :benchmarks do
  gem 'actionpack', '~> 5.0'
  gem 'activemodel', '~> 5.0'
  gem 'benchmark-ips'
  gem 'hotch', platform: :mri
  gem 'virtus'
end
