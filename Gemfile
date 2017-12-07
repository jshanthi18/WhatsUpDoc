source 'https://rubygems.org'

# renders HTML from markdown
gem 'redcarpet'

# markdown linting tool
gem 'mdl'

gem 'colored'
gem 'safe_yaml'
gem 'httparty'

# CI needs this specific version of Rake
#gem 'rake',  '10.1.0'

group :test do
  gem 'database_cleaner'
  gem 'cucumber-rails', '~> 1.4.0', require: false
  gem 'pickle',            git: 'https://github.com/enova/pickle.git'
  gem 'yajl-ruby'
  gem 'rb-fsevent',       '~> 0.9.0'
  gem 'launchy'

  gem 'coveralls', require: false
  gem 'webmock'
  gem 'vcr'

  gem 'poltergeist', '~> 1.15.0'
  gem 'capybara-screenshot'
  gem 'rspec-sidekiq'
  gem 'rake',  '10.1.0'
end
