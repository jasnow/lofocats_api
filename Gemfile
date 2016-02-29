source 'https://rubygems.org'

gem 'rails', '4.2.5.2'
# Database
gem 'sqlite3'

# Required to use 'has_secure_password' in ActiveRecord
gem 'bcrypt'

# Serializers for the JSON responses
gem 'active_model_serializers'

# Used for API authorization
gem 'cancan'

group :test do
  # Rspec
  gem 'rspec-rails'
  # FactoryGirl factories
  gem "factory_girl_rails"
  # Use should matchers
  gem 'shoulda-matchers', '3.0.1', require: false # LOCKED DOWN - see #880 for fix.
  # To better handle time sensitive tests
  gem 'timecop'
end
