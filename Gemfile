source "https://rubygems.org"

gem "rails", "~> 8.0.1"

gem "graphql", "~> 2.4"

gem "sequel", "~> 5.89"
gem "pg", "~> 1.5"
gem "sequel_pg", "~> 1.17", require: "sequel"
gem "sequel-rails", "~> 1.2"
gem "memo_wise", "~> 1.10"

gem "puma", ">= 5.0"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Add HTTP asset caching/compression and X-Sendfile acceleration to Puma [https://github.com/basecamp/thruster/]
gem "thruster", require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin Ajax possible
# gem "rack-cors"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  # Static analysis for security vulnerabilities [https://brakemanscanner.org/]
  gem "brakeman", require: false

  # Omakase Ruby styling [https://github.com/rails/rubocop-rails-omakase/]
  gem "rubocop-rails-omakase", require: false

  gem "rack-mini-profiler", "~> 3.3"
  gem "stackprof", "~> 0.2.27"

  # Needed by RubyMine
  gem "mutex_m", require: false
end
