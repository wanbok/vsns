source 'https://rubygems.org'

# for Heroku deployment
ruby "2.0.0"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use LESS for stylesheets
gem 'less-rails'
gem 'twitter-bootstrap-rails'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
gem 'jquery-ui-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Attention! added by hschoi
# To resolve Turbolink problems,
# please reference http://blog.joshsoftware.com/2013/06/28/troubleshooting-turbolinks-with-rails-4/.
gem 'jquery-turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# commented out by hschoi due to incompatibility to summernote-rails
# gem 'flatui-rails'
gem 'summernote-rails'

gem 'slimbox2-rails'

# gem 'masonry-rails'

gem 'simple_form', github: 'plataformatec/simple_form', tag: 'v3.0.0.rc'

# gem 'carrierwave'
gem 'carrierwave-aws'  # added by hschoi
gem 'rmagick'

# for Authentication and Authorization
gem 'devise'
#gem 'devise', github: 'plataformatec/devise', branch: 'rails4'
gem 'authority'
gem 'rolify'

# for pagination
gem 'will_paginate'
gem 'pageless-rails', github: 'rorlab/pageless-rails'

# for Tagging
gem 'acts-as-taggable-on'

# Replace gem 'tagsinput-rails' with the following one for Bootstrap
gem 'bootstrap-tagsinput-rails'

# Chatting
gem 'mad_chatter', github: 'wanbok/mad_chatter'

group :development do

  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
  
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :production do
  # for heroku deployment
  gem 'pg'
  gem 'rails_12factor'
end

# Use ActiveModel has_secure_password
gem 'bcrypt-ruby'
#gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
