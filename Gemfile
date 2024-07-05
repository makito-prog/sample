source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.3.3"

gem "rails", "~> 7.0.0"
gem "sprockets-rails", "~> 3.5"
gem "puma", "~> 5.0"
gem "importmap-rails", "~> 2.0"
gem "turbo-rails", "~> 2.0"
gem "stimulus-rails", "~> 1.3"
gem "jbuilder", "~> 2.12"

group :development, :test do
  gem 'sqlite3', '~> 1.4'
  gem "debug", platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem "web-console", "~> 4.0"
end

group :test do
  gem "capybara", "~> 3.36"
  gem "selenium-webdriver", "~> 4.0"
  gem "webdrivers", "~> 5.0"
end

group :production do
  gem "pg", "~> 1.4"
end

gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem "bootsnap", require: false
