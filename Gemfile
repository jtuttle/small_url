source 'https://rubygems.org'

# http://stackoverflow.com/questions/41454333/meaning-of-new-block-git-sourcegithub-in-gemfile
git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.1'
gem 'pg', '~> 0.20.0'

# Use Puma as the app server
gem 'puma', '~> 3.7'

# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'bases', '~> 1.0.1'
gem 'rack-cors', '~> 0.4.1'
gem 'apipie-rails', '~> 0.5.1'
gem 'rest-client', '~> 2.0.2'

group :development, :test do
  gem 'pry-rails', '~> 0.3.6'
  gem 'pry-nav', '~> 0.2.4'
  
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'

  gem 'rspec-rails', '~> 3.6.0'
  gem 'factory_girl_rails', '~> 4.8.0'
end

group :development do

end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# For Heroku
ruby '2.4.1'
