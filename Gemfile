source "https://rubygems.org"

# Use github-pages gem for GitHub Pages compatibility
gem "github-pages", "~> 231"

# Performance and compatibility
gem "webrick", "~> 1.8"

# Windows specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem 'wdm', '>= 0.1.0'
end

# Jekyll plugins
group :jekyll_plugins do
  gem 'jekyll-feed'
  gem 'jekyll-sitemap'
  gem 'jekyll-paginate'
  gem 'jekyll-seo-tag'
  gem 'jekyll-archives'
  gem 'jekyll-gist'
end