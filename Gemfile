source 'http://rubygems.org'

gem 'rails', '3.1.3'

gem 'neoid'
gem 'json'
gem 'gravatar_image_tag'
gem 'will_paginate'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem 'webrat'

  #gem 'neo4j'
#  gem 'neo4j', '1.3.1'
#  gem 'neo4j-admin'

  # To use debugger
  gem 'ruby-debug19'
end

gem 'jquery-rails'

group :assets do
  gem 'sass-rails', "~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

group :production do
	gem 'pg'
end

group :development, :test do
	gem 'rspec-rails'
end

group :development do
	gem 'faker'
	gem 'sqlite3'
end

group :test do
	gem 'webrat'
	gem 'spork'
	gem 'factory_girl_rails'
end

