source 'http://rubygems.org'

gem 'rails', '3.1.4'

gem 'spree'
gem 'spree_usa_epay'
gem 'spree_skrill'
gem 'spree_static_content', :git => 'git://github.com/spree/spree_static_content.git', :branch => '1-0-stable'
#gem 'twitter-bootstrap-rails'
#gem 'high_voltage'
gem 'thin'
gem 'spree_heroku', :git => 'git://github.com/joneslee85/spree-heroku.git', :branch => '1-0-stable'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.1.5'
  gem 'coffee-rails', '~> 3.1.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'execjs'
  #gem 'therubyracer'

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

group :development, :test do
  gem 'sqlite3'
end

group :production do
  gem 'pg'
end

group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
end

