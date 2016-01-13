source 'https://rubygems.org'

gem 'react_on_rails', '~> 2.0.0.rc.3'

gem 'rails', '3.2.22'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'

gem 'therubyracer', platforms: :ruby

# require: false is necessary for the linters as we only want them loaded
# when used by the linting rake tasks.
group :development do
  gem("rubocop", require: false)
  gem("ruby-lint", require: false)
  gem("scss_lint", require: false)
end

# For Heroku deployment
gem 'rails_12factor', group: :production
gem 'puma', group: :production

gem 'bootstrap-sass', '~> 3.1.1'
