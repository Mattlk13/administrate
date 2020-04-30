source 'https://rubygems.org'

ruby "2.2.3"

gemspec

gem "delayed_job_active_record", ">= 4.1.0"
gem "high_voltage"
gem "markdown-rails", ">= 0.2.1"
gem "pg"
gem "redcarpet"
gem "unicorn"

group :development do
  gem "web-console", ">= 2.2.1"
end

group :development, :test do
  gem "appraisal"
  gem "awesome_print"
  gem "bundler-audit", require: false
  gem "byebug"
  gem "dotenv-rails", ">= 2.0.2"
  gem "factory_girl_rails", ">= 4.5.0"
  gem "faker"
  gem "i18n-tasks", ">= 0.8.7"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.1.0"
end

group :test do
  gem "ammeter", ">= 1.1.3"
  gem "database_cleaner"
  gem "formulaic", ">= 0.3.0"
  gem "fuubar"
  gem "launchy"
  gem "percy-capybara"
  gem "poltergeist"
  gem "shoulda-matchers", "~> 2.8.0", require: false
  gem "timecop"
  gem "webmock"
end

group :staging, :production do
  gem "rack-timeout"
  gem "rails_stdout_logging"
  gem "uglifier", ">= 2.7.2"
end
