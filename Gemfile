source 'https://rubygems.org'

gem 'rails', '~> 3.2.8'

gem 'json', '~> 1.7.5'
gem 'simple_form', '~> 2.0.4'

gem 'sqlite3', '~> 1.3.6',  :groups => [:test, :development]
gem 'pg', '~> 0.14.1',      :groups => :production
gem 'heroku'
gem 'copycopter_client', :git => 'git://github.com/copycopter/copycopter-ruby-client.git' 
gem 'responders'
gem 'will_paginate'
gem 'libv8'

# Using Capybara with RSpec:
#   http://rubydoc.info/github/jnicklas/capybara#Using_Capybara_with_RSpec
gem 'capybara', '~> 1.1.2', :groups => :test

group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'twitter-bootstrap-rails', '~> 2.1.4'
  gem 'jquery-ui-rails', '~> 2.0.2'
  gem 'jquery-datatables-rails', '~> 1.11.1'
end
gem 'jquery-rails', '~> 2.1.3'

gem 'omniauth-github'
group :development, :test do
  gem 'hirb', '~> 0.7.0'
  gem 'quiet_assets', '~> 1.0.1'  # wylacza logowanie *assets pipeline*
  gem 'rspec-rails', '~> 2.11.0'
# Bezproblemowe zape³nianie bazy danymi testowymi:
#   https://github.com/thoughtbot/factory_girl/blob/master/GETTING_STARTED.md
gem 'factory_girl_rails'
gem 'faker'
gem 'populator'
end

gem 'less-rails', '~> 2.2.6'
gem 'therubyracer', '~> 0.10.2'

# alternatywa dla serwera Webrick
gem 'thin'
