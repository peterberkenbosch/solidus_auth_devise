source "https://rubygems.org"

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem "solidus", github: "solidusio/solidus", branch: branch

gem 'pg'
gem 'mysql2'

group :development, :test do
  gem "pry-rails"
  gem "rails-controller-testing"
end

gemspec
