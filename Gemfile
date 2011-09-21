source "http://rubygems.org"

gem "rails", "3.1.0"
#gem "sprockets"
gem "pg", :require => "pg"

gem 'json'
gem 'coffee-script'
gem 'uglifier'

gem "devise"
gem "oa-oauth", :require => "omniauth/oauth"
gem "kaminari"
gem "carrierwave"
gem "jquery-rails"
gem "meta_search"

group :test, :development do
  gem "rspec-rails"
  gem "email_spec"
  gem "shoulda"
  gem "cucumber-rails"
  gem "capybara"
  gem "factory_girl_rails"
  gem "database_cleaner"
  gem "ruby-debug19"
  gem "mongrel", ">= 1.2.0.pre2"
  gem "chronic"
  gem "awesome_print"
  gem "therubyracer"
  gem "spork", "~> 0.9.0.rc"
end

group :production do
  gem "therubyracer-heroku"
end
