source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.1"

gem 'http'

gem "sinatra"
gem "sinatra-contrib"

# Use Puma as the app server
gem "puma"

# use active record
gem "sinatra-activerecord"

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem "table_print"
  gem "appdev_support"
end

group :development, :test do
  gem "grade_runner"
  gem "pry"
  gem "sqlite3"
end

group :test do
  gem "capybara"
  gem "draft_matchers"
  gem "rspec"
  gem "rspec-html-matchers"
  gem "webmock"
  gem "webdrivers"
  gem "i18n"
end
