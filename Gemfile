source 'https://rubygems.org'
ruby "2.2.0"
gem "rake"
gem "serious", :path => './serious'
gem "json"
gem 'puma'

group :development do
  gem 'rerun'
end

group :test do
  gem 'rack-test'
  gem 'test-unit'
  gem 'webmock'
  gem 'feedvalidator', :require => 'feed_validator', :git => 'https://github.com/bandzoogle/feedvalidator.git'
  gem 'typhoeus'
end
