source 'https://rubygems.org'

gem 'rails', '4.0.1'
gem 'thin'
gem 'feedzirra'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'debugger'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'

# removed following and will use CDN instead of asset pipeline - see
# http://coderberry.me/blog/2013/04/22/angularjs-on-rails-4-part-1/
# gem 'jquery-rails', '3.0.4'
# gem 'turbolinks', '1.1.1'
# gem 'jbuilder', '1.0.2'

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
