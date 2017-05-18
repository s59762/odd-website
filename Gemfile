source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13.0'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development, :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'spring-commands-rspec'
  gem 'timecop'
  gem 'vcr'
  gem 'webmock'
  gem 'capybara-screenshot'
  gem 'guard-livereload'
  gem 'guard-rspec', require: false
  gem 'guard-pow'
  gem 'terminal-notifier-guard'
  gem 'annotate'
  gem 'better_errors'
  gem 'meta_request'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
  gem 'faker'
  gem 'rubocop'
  gem 'bullet'
  gem 'capistrano'
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rails', '~> 1.1.1'
  gem 'capistrano-rbenv', github: 'capistrano/rbenv'
  gem 'capistrano-sidekiq'
  gem 'slackistrano'
  gem 'capistrano-db-tasks', require: false
  gem 'rack-mini-profiler', require: false
  gem 'binding_of_caller'
end

gem 'pg'
gem 'devise', github: 'plataformatec/devise'
gem 'espresso_martini', github: 'oracle-design/espresso_martini'
gem 'sprockets-rails'
gem 'sass-rails'
gem 'font-awesome-sass'
gem 'sassc-rails'
gem 'bourbon'
gem 'neat', '~>1.8.0'
gem 'bootstrap-sass'
gem 'material_icons'
gem 'autoprefixer-rails'
gem 'slim-rails'
gem 'bower-rails'
gem 'modernizr-rails'
gem 'jquery-rails'
gem 'awesome_rails_console'
gem 'growlyflash'
gem 'rails-assets-sweetalert', source: 'https://rails-assets.org'
gem 'sweet-alert-confirm'
gem 'rails-settings-cached'
gem 'figaro'
gem 'cells'
gem 'cells-slim'
gem 'cells-rails'
gem 'carrierwave'
gem 'mini_magick'
gem 'meta-tags'
gem 'favicon_maker'
gem 'sidekiq'
gem 'pundit'
