source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0.1'
# Use sqlite3 as the database for Active Record
gem 'pg'

# SEO pack
gem 'sitemap_generator'
gem 'meta-tags', require: 'meta_tags'

gem 'haml-rails'
gem 'rest-client'
gem 'font-awesome-rails'
gem 'html5-rails'
gem 'fancybox2-rails'

gem 'sass-rails'
gem 'compass-rails'

gem 'jsoneditor-rails'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem "jquery-fileupload-rails"
gem 'jquery-datetimepicker-rails'

gem 'devise'
gem 'devise_invitable'
gem 'cancancan'
gem 'rolify'
gem 'redcarpet'

gem "select2-rails"

gem 'newrelic_rpm'

# file upload
gem 'paperclip'
gem 'fog'

gem 'exception_notification'

gem 'foundation-rails', '5.5.2.1'

#pagination
gem 'kaminari'
gem 'simple_form'
gem 'country_select'
gem 'au_state_select', '~>1.7'

gem 'nokogiri'
# Turbolinks is dangerous makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

gem 'json-diff', '0.4.1'

gem 'haml'

gem 'ckeditor'

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring

# Use ActiveModel has_secure_password
gem 'bcrypt'

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Use unicorn as the app server
gem 'unicorn'

gem 'sidekiq', '~> 4.2'

gem 'nested_form', git: 'git://github.com/BenZhang/nested_form.git'

gem 'elasticsearch-model'
gem 'elasticsearch-rails'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :test do
  gem 'rspec'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'simplecov-rcov'
  gem "factory_girl_rails"
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'rails-controller-testing'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'puma', '~> 3.0'
  gem 'pry'
  gem 'pry-nav'
  # gem 'spring'
  gem 'capistrano', github: 'capistrano/capistrano', branch: 'legacy-v2'
  gem 'capistrano-ext'
  gem 'rvm-capistrano', require: false
  gem "capistrano-db-tasks", require: false, github: 'gkopylov/capistrano-db-tasks', ref: 'f3949cd'
  #gem 'capistrano', '~> 3.7', '>= 3.7.1'
  #gem 'capistrano-rails', '~> 1.2'
  #gem 'capistrano-passenger', '~> 0.2.0'
  #gem 'capistrano-rvm'
  gem "better_errors"
  gem "binding_of_caller"
  gem 'pixelforce_cms', '~> 1.0'
  gem 'pixelforce_recipes', '~> 0.2'
  gem 'railroady'
end
gem 'thor', '0.19.1'
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
