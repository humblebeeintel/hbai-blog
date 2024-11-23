source "https://rubygems.org"

# Use github-pages gem for GitHub Pages compatibility
gem "github-pages", "~> 231"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Windows Directory Monitor
gem 'wdm', '>= 0.1.0' if Gem.win_platform?

# Performance-booster for watching directories on Windows
gem "webrick", "~> 1.8"

# Add sass explicitly
gem 'sass', '~> 3.7.4'
gem 'sass-listen', '~> 4.0.0'

# Jekyll plugins
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-paginate'
  gem 'jekyll-seo-tag'
  gem 'jekyll-archives'
  gem 'jekyll-gist'
end

# Lock specific versions for stability
gem "nokogiri", "~> 1.15.5"
gem "commonmarker", "~> 0.23.10"

# For faster file watching
group :development do
  gem 'rb-fsevent', '~> 0.11.2'
  gem 'rb-inotify', '~> 0.10.1'
end