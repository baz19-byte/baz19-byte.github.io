# frozen_string_literal: true
source "https://rubygems.org"

# --- Core site dependencies (needed at build time) ---
gem "jekyll", "~> 4.3"
gem "jekyll-theme-chirpy", "~> 7.3", ">= 7.3.1"
gem "webrick", "~> 1.8"           # needed to serve locally on Ruby 3.x
gem "nokogiri"                    # required by many Jekyll plugins/themes

# Optional but common Jekyll plugins (uncomment if you use them)
# gem "jekyll-paginate"
# gem "jekyll-sitemap"
# gem "jekyll-seo-tag"
# gem "jekyll-include-cache"

# --- Development / test only ---
group :development, :test do
  gem "html-proofer", "~> 5.0"    # link checker (not needed for Cloudflare build)
end

# Windows platform specifics
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", platforms: [:windows]

# Pin Ruby version to avoid Ruby 3.4 issues on Cloudflare
ruby "3.4.5"
