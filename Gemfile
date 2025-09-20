source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.4.5"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 8.0.2"

gem "propshaft"

# Use sqlite3 as the database for Active Record
#gem "sqlite3", "~> 2.7"
gem "pg" # Use PostgreSQL as the database for Active Record
# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 6.6"

gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

gem "requestjs-rails"

# Use Tailwind CSS [https://github.com/rails/tailwindcss-rails]
gem "tailwindcss-rails", "~> 3.3.1"

# Use solid_cable adapter to run Action Cable in production
gem "solid_cable"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
gem "bcrypt", "~> 3.1.7"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "rspec-rails"
  gem "dotenv-rails"
end

group :development do
  gem "letter_opener_web"

  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"

  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"

  gem "hotwire-spark"

  # Use Redis for Action Cable
  gem "redis", "~> 5.4"
end

group :test do
  gem "shoulda-matchers", require: false
  gem "capybara"
  gem "cuprite"
  gem "factory_bot_rails"
  # gem "vcr", require: false
  # gem "webmock"
end

gem "meta-tags"
gem "class_variants"
gem "http"
gem "inline_svg"

gem "view_component", "~> 4.0"
gem "administrate", "= 1.0.0.beta3"
gem "redcarpet", "~> 3.6" # Markdown renderer

gem "solid_queue"
gem "solid_cache"
gem "mission_control-jobs"

gem "dry-initializer", "~> 3.1"
gem "dry-operation"

# Exception tracking
gem "exception_notification"
gem "slack-notifier"

gem "validates_timeliness", "~> 8.0"
gem "kaminari", "~> 1.2"
gem "prawn", "~> 2.5"
gem "prawn-table", "~> 0.2.2"
gem "caxlsx", "~> 4.4"
gem "caxlsx_rails", "~> 0.6.4"
gem "chartkick", "~> 5.2"
gem "groupdate", "~> 6.7"
