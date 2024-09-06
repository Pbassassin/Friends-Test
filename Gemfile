source "https://rubygems.org"
gem "rails", "~> 7.2.0"
gem "sprockets-rails"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'devise', '~> 4.9', '>= 4.9.4'
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "sqlite3", ">= 1.4"
  gem "web-console"
end

group :production do
  gem 'pg', '~> 1.5'
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
