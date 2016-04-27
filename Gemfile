source 'https://rubygems.org'
#ruby=2.3.1
#ruby-gemset=ilolo
gem 'rails', '4.2.3'
gem 'pg'
gem 'sqlite3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'therubyracer', platforms: :ruby
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'slim'
gem 'less-rails'
gem 'twitter-bootstrap-rails', github: 'seyhunak/twitter-bootstrap-rails'

group :test, :developement do
  gem 'rspec-rails', '~> 3.4'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'launchy'
  gem 'guard-rspec'
  gem 'rubocop', '~> 0.34.2', require: false
  gem 'childprocess', '0.3.6'
#  gem 'libnotify' if /linux/ =~ RUBY_PLATFORM
  gem 'growl'    # if /darwin/ =~ RUBY_PLATFORM
  gem 'database_cleaner'
#  gem 'capybara-webkit', '1.3.0'

end

group :test do
  gem 'shoulda-matchers'
end

group :production do
  gem 'rails_12factor', '0.0.2'
end
