source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

# Add version constraints for compatibility
gem 'activesupport', '~> 7.0.8'
gem 'railties', '~> 7.0.8'

ruby "3.1.0"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.3"

# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"

# Use sqlite3 as the database for Active Record
gem "sqlite3", "~> 1.4"

# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "tailwindcss-rails", "~> 3.3"
gem "tailwindcss-ruby", "~> 3.4" # only necessary with tailwindcss-rails <= 3.3.0
gem "turbo-rails"
gem "importmap-rails"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end


gem "dockerfile-rails", ">= 1.7", :group => :development
