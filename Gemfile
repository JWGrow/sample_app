source 'https://rubygems.org'

gem 'rails', '3.2.1'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'
gem 'gravatar_image_tag'
gem 'will_paginate'

group :development do
  gem 'rspec-rails'#, '2.6.1'
  gem 'annotate'#, '2.4.0'
  gem 'faker'#, '0.3.1'
end

group :test do
  gem 'rspec-rails'#, '2.6.1'
  gem 'webrat'#, '0.7.1'
  gem 'spork'#, '0.9.0.rc8'
  gem 'factory_girl_rails'#, '1.0'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

# activerecord-postgresql-adapter error cure:
#1) add the line: gem 'pg' to your Gemfile.
#2) Run the command bundle install to install the gem into your bundle.
#3) Stage the Gemfile and Gemfile.lock changes: git add Gemfile Gemfile.lock
#4) Commit the changes: git commit -m "Install the pg gem"
#5) Redeploy to heroku: git push heroku master
gem 'pg'
