source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "bcrypt", "3.1.12"
gem "bootstrap-kaminari-views"
gem "bootstrap-sass", "3.3.7"
gem 'bootstrap3-datetimepicker-rails', '~> 4.17.47'
gem "coffee-rails", "~> 4.2"
gem "config"
gem "faker", "~> 1.9", ">= 1.9.1"
gem "i18n"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "kaminari"
gem "momentjs-rails", ">= 2.9.0"
gem "pg"
gem "pg_search"
gem "puma", "~> 3.7"
gem "rails", "~> 5.1.6"
gem "rubocop", "~> 0.54.0", require: false
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "dotenv-rails"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
