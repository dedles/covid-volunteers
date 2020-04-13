source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 6.0.2', '>= 6.0.2.1'
gem 'puma', '~> 4.1'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'redis', '~> 4.0'

gem 'bootsnap', '>= 1.4.2', require: false
gem 'kaminari'
gem 'acts-as-taggable-on'
gem 'inline_svg'

# Linting
gem 'rubocop', require: false
gem 'rubocop-rails', require: false
gem 'rubocop-performance', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 4.0.0.rc1'
  gem 'factory_bot_rails'
  gem 'rails-controller-testing'
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
gem 'pg'
gem 'devise'

# Auto link.
gem 'rinku'

# Sending emails.
gem 'aws-sdk-ses'
gem 'aws-sdk-rails'

gem 'exception_notification', git: 'https://github.com/smartinez87/exception_notification'

gem 'pg_search'

# Email obfuscation
gem 'actionview-encoded_mail_to', git: 'https://github.com/mirko314/actionview-encoded_mail_to', branch: 'feature/fix-vanilla-mail-to'

gem 'gravatar_image_tag'

gem 'dotenv-rails', groups: [ :development, :test ]

gem 'config'

gem 'iso_country_codes', '~> 0.7.8'
