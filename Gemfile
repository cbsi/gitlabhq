source "http://rubygems.org"

gem "rails", "5.0.0"

# Supported DBs
gem "sqlite3"
gem "mysql2"

# Auth
gem "devise", "~> 4.0.0"

# GITLAB patched libs
gem "grit",          :git => "https://github.com/gitlabhq/grit.git",            :ref => "7f35cb98ff17d534a07e3ce6ec3d580f67402837"
gem "gitolite",      :git => "https://github.com/gitlabhq/gitolite-client.git", :ref => "9b715ca8bab6529f6c92204a25f84d12f25a6eb0"
gem "pygments.rb",   :git => "https://github.com/gitlabhq/pygments.rb.git",     :ref => "2cada028da5054616634a1d9ca6941b65b3ce188"
gem "omniauth-ldap", :git => "https://github.com/gitlabhq/omniauth-ldap.git",   :ref => "f038dd852d7bd473a557e385d5d7c2fd5dc1dc2e"
gem 'yaml_db',       :git => "https://github.com/gitlabhq/yaml_db.git"
gem 'grack',         :git => "https://github.com/gitlabhq/grack.git"
gem "linguist", "~> 1.0.0", :git => "https://github.com/gitlabhq/linguist.git"

# API
gem "grape", "~> 0.2.1", ">= 0.2.1.1"

# Format dates and times
# based on human-friendly examples
gem "stamp"

# Pagination
gem "kaminari", ">= 0.14.0"

# HAML
gem "haml-rails", ">= 0.5.3"

# Files attachments
gem "carrierwave"

# Authorization
gem "six"

# Generate Fake data
gem "ffaker"

# Seed data
gem "seed-fu"

# Markdown to HTML
gem "redcarpet", "~> 2.1.1"

# Servers
gem "thin", ">= 1.4.0"
gem "unicorn", ">= 4.4.0"

# Issue tags
gem "acts-as-taggable-on", "3.1.0"

# Decorators
gem "draper", ">= 1.0.0"

# Background jobs
gem "resque", "~> 1.21.0"
gem 'resque_mailer', '>= 2.2.4'

# HTTP requests
gem "httparty"
gem "charlock_holmes", "0.6.8"
gem "foreman"
gem "colored"

# GITLAB settings
gem 'settingslogic'
gem 'net-ssh'

# Misc
gem "foreman"
gem "git"

group :assets do
  gem "sass-rails", "5.0.5"
  gem "coffee-rails", "4.1.1"
  gem "uglifier",     "1.0.3"
  gem "therubyracer"

  gem 'chosen-rails', '>= 0.9.11.1'
  gem "jquery-rails", "4.0.1"
  gem "jquery-ui-rails", "1.0.0"
  gem "modernizr",        "2.5.3"
  gem "raphael-rails",    "1.5.2"
  gem 'bootstrap-sass',   "2.0.4"
end

group :development do
  gem "letter_opener"
  gem "annotate", :git => "https://github.com/ctran/annotate_models.git"
  gem 'rack-mini-profiler', '>= 0.1.10'
end

group :development, :test do
  gem "rspec-rails", ">= 2.11.0"
  gem "capybara", ">= 1.1.3"
  gem "capybara-webkit", ">= 0.13.0"
  gem "headless"
  gem "autotest"
  gem "autotest-rails"
  gem "pry"
  gem "awesome_print"
  gem "database_cleaner"
  gem "launchy"
end

group :test do
  gem 'cucumber-rails', '>= 1.3.1', :require => false
  gem "simplecov", :require => false
  gem "shoulda-matchers"
  gem 'email_spec'
  gem 'resque_spec', '>= 0.12.0'
  gem "webmock"
end

group :production do
  gem "gitlab_meta", '2.8'
end
