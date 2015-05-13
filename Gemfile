# -*- coding: utf-8 -*-
source 'https://rubygems.org'

gem 'rails', '4.1.5'
gem 'therubyracer'

gem 'mysql2'


group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier', '>= 1.0.3'
  gem 'turbo-sprockets-rails3'
end

gem 'jquery-rails'
gem 'haml-rails'
gem 'thin'
gem 'kaminari'
gem 'oauth'
gem 'default_value_for'
gem "simple_oauth"
gem "faraday"
gem "faraday_middleware"
gem "meta_search"
gem "settingslogic"
gem "bugsnag"
gem "newrelic_rpm"
gem "squeel"
gem 'whenever', :require => false
gem 'mail-iso-2022-jp'
gem 'delayed_job_active_record'
gem 'carrierwave'
gem 'fog'

group :development, :test do
  gem 'pry-byebug'
  gem "rspec-rails"
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'factory_girl_rails'
  gem 'json_spec', '~> 1.1.1'
  gem 'json_expressions'
  gem 'spring', github: "jonleighton/spring"
  gem 'guard'
  gem 'guard-spring'
end

group :test do
  gem 'webmock'
  gem 'simplecov', require: false
  gem 'capybara'
end

group :staging, :production do
  gem "daemons"
end
