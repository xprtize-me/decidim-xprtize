# frozen_string_literal: true

source "https://rubygems.org"

ruby RUBY_VERSION

gem "decidim", "0.26.1"
# gem "decidim-conferences", "0.26.1"
# gem "decidim-consultations", "0.26.1"
# gem "decidim-elections", "0.26.1"
# gem "decidim-initiatives", "0.26.1"
# gem "decidim-templates", "0.26.1"

gem "bootsnap", "~> 1.3"

gem "puma", ">= 5.0.0"

gem "faker", "~> 2.14"

gem "wicked_pdf", "~> 2.1"

group :development, :test do
  gem "byebug", "~> 11.0", platform: :mri

  gem "brakeman"
  gem "decidim-dev", "0.26.1"
end

group :development do
  gem "letter_opener_web", "~> 1.3"
  gem "listen", "~> 3.1"
  gem "spring", "~> 2.0"
  gem "spring-watcher-listen", "~> 2.0"
  gem "web-console", "~> 4.0"

  gem "capistrano", "~> 3.15"
  gem "capistrano-bundler"
  gem "capistrano-passenger"
  gem "capistrano-rails"
  gem "capistrano-rails-console"
  gem "capistrano-rbenv"
  gem "capistrano-sidekiq"
end

group :production do
  gem "figaro"
  gem "sidekiq"
  gem "sidekiq-cron"
end
