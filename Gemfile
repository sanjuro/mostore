source 'http://rubygems.org'

gem 'rails', '3.1.4'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'mysql2'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
group :development do 
	gem 'rspec-rails'
end

group :test do 
	# gem 'rspec-rails'
	# gem 'webrat'
	# gem 'factory_girl_rails'
	# gem 'spork'
	gem 'turn', '0.8.2', :require => false
end

gem 'spree', :path => '../spree'
gem 'spree_usa_epay'
gem 'spree_skrill'

gem 'spree_gateway', :path => '../spree_gateway'

gem 'spree_multi_domain', :git => 'git@github.com:sanjuro/spree_multi_domain.git'
gem 'spree_personera_theme', :git => 'git@github.com:sanjuro/spree_personera_theme.git'
gem 'spree_social', :git => 'git@github.com:sanjuro/spree_social.git'