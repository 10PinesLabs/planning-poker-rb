source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'rails', '~> 6.1.4'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'bulma-rails', '~> 0.9.1'
gem 'hotwire-rails', '~> 0.1.3'
gem 'jbuilder', '~> 2.7'
gem 'pg', '~> 1.2.3'
gem 'puma', '~> 5.0'
gem 'rexml', '~> 3.2.5'
gem 'sass-rails', '>= 6'
gem 'sqlite3', '~> 1.4'
gem 'webpacker', '~> 5.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'spring'
  gem 'web-console', '>= 4.1.0'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]