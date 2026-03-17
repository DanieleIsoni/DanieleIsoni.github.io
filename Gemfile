source "https://rubygems.org"

# Use a modern, patched Jekyll runtime instead of the legacy `github-pages`
# meta-gem, which pins many outdated transitive dependencies.
gem "jekyll", "~> 4.4"
gem "jekyll-theme-prologue", "~> 0.3.3"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?
