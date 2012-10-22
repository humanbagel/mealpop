source 'https://rubygems.org'

gem 'rails', ">= 3.2.8"

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem "mysql2", "~> 0.3.11"

# templating
gem "haml", "~> 3.1.4"

#authenthication and authorization
gem "devise", "~> 1.5.3"
gem "cancan", "~> 1.6.7"
gem "role_model", "~> 0.7.0" #sets up mask field for roles, used with cancan
gem "omniauth", "~> 1.0.2"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', "~> 0.9.9"

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'thin'        # used for thin server (instead of mongrel)

gem "rmagick", "~> 2.13.1"
gem 'viewfu'
gem "s3", "~> 0.3.11"

gem "twitter"
gem 'gravtastic'

gem "rails_config", "~> 0.2.5"

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

group :development, :test do
  gem "ruby-debug", :platforms => :mri_18
  gem "ruby-debug19", :platforms => :mri_19, :require => 'ruby-debug'
  gem "therubyracer", "~> 0.9.9", :require => "v8"
  gem "heroku-rails", "~> 0.4.3"
end
