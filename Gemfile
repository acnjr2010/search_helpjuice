source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.0.1'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'font-awesome-sass', '~> 4.7'
gem 'haml', '~> 4.0', '>= 4.0.7'
gem 'simple_form', '~> 3.3', '>= 3.3.1'
gem 'rails-i18n', '~> 5.0.0.beta1'
gem 'will_paginate', '~> 3.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails', '~> 4.8'
  gem 'faker', '~> 1.7', '>= 1.7.2'
  gem 'pry-rails', '~> 0.3.4'
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  gem 'simplecov', '~> 0.13.0', require: false
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'shoulda-matchers', '~> 3.1', '>= 3.1.1', require: false
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Capistrano to upload application
  gem 'capistrano', '~> 3.7', '>= 3.7.1'
  gem 'capistrano3-puma', '~> 1.2', '>= 1.2.1'
  gem 'capistrano-rails', '~> 1.2', '>= 1.2.2', require: false
  gem 'capistrano-bundler', '~> 1.2', require: false
  gem 'capistrano-rvm', '~> 0.1.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
