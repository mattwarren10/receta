source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.4'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.7'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'bower-rails', '~> 0.11.0'
gem 'foreman', '~> 0.84.0'

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'minitest', '~> 5.10', '>= 5.10.3'
  gem 'factory_bot_rails', '~> 4.8', '>= 4.8.2'
  gem 'capybara', '~> 2.15', '>= 2.15.4'
  gem 'database_cleaner', '~> 1.6', '>= 1.6.2'
  gem 'selenium-webdriver', '~> 3.7'
end

group :development do

  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'

  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production, :staging do
  gem 'rails_12factor', '~> 0.0.3'
  gem 'rails_stdout_logging', '~> 0.0.5'
  gem 'rails_serve_static_assets', '~> 0.0.5'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
