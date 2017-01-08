source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', github: "rails/rails"
gem 'arel', github: "rails/arel"

gem 'jekyll'
gem "minima", "~> 2.0"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
end

gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'

gem 'sass-rails', github: "rails/sass-rails"
gem 'uglifier', '>= 1.3.0'
gem 'webpacker', github: "rails/webpacker"
gem 'coffee-rails', '~> 4.2'
gem 'turbolinks', '~> 5'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'pry-byebug'
end

group :development do
  gem 'web-console', github: 'rails/web-console'
  gem 'listen', '>= 3.0.5', '< 3.2'
end