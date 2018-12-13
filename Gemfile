source 'https://rubygems.org'
git_source(:github) {|repo| "https://github.com/#{repo}.git"}

ruby '2.4.4'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'pry-rails'
gem 'puma', '~> 3.11'
gem 'rails', '~> 5.2.0'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'tty-spinner'
gem 'rails-i18n', '~> 5.1'

gem 'webpacker'
# # .js assets
# source 'https://rails-assets.org' do
#   gem 'rails-assets-jquery'
#   gem 'rails-assets-notifyjs'
# end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # gem 'sqlite3'
  gem 'pg', '>= 0.18', '< 2.0'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'capybara', '>= 2.15', '< 4.0'
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'
end

group :production do
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
