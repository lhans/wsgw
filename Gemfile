source 'https://rubygems.org'
ruby '1.9.3'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails',                '4.0.0'

gem 'bootstrap-sass',       '2.3.2.0'
#gem 'protected_attributes', '~> 1.0.0'

gem 'devise',               '~> 3.0.0.rc'

gem 'bcrypt-ruby',          '3.0.1'
gem 'will_paginate',        '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

group :development, :test do
  gem 'pg',                 '0.15.1'
  gem 'rails_12factor',     '0.0.2'
  gem 'rspec-rails',        '2.11.0'
  gem 'annotate',           '2.5.0'
end
 
# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',         '~> 4.0.0'

  # Use CoffeeScript for .js.coffee assets and views
  gem 'coffee-rails',       '~> 4.0.0'

  # Use Uglifier as compressor for JavaScript assets
  gem 'uglifier',           '>= 1.3.0'
end


# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder',             '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby',        '~> 3.0.0'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :test do
	gem 'capybara',       '1.1.2'
	#gem 'cucumber-rails','1.2.1', :require => false
  	#gem 'database_cleaner',  '0.7.0'	
      gem 'factory_girl_rails', '4.2.1'
end

group :production do
  gem 'pg',                 '0.15.1'
  gem 'rails_12factor',     '0.0.2'
end