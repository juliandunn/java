source 'https://rubygems.org'

gem 'berkshelf',  '~> 2.0'
gem 'chefspec',   '~> 2.0'
gem 'foodcritic', '~> 3.0'
gem 'rubocop',    '~> 0.12'

group :integration do
  gem 'test-kitchen',    '~> 1.0.0.beta'
  gem 'kitchen-vagrant', '~> 0.11'

group :test do
  gem "chefspec"
  gem "foodcritic"
  gem "guard"
  gem "guard-rspec"
  gem "guard-kitchen"
  gem "rake"
  gem "rb-inotify", :require => false
  gem "rb-fsevent", :require => false
  gem "rb-fchange", :require => false
end
