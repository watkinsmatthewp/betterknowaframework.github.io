source "https://rubygems.org"

group :jekyll_core do
  gem "jekyll"
end

group :jekyll_plugins do  
  gem "jekyll-paginate"
  gem "jekyll-feed"
end

group :windows do
  # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
  # Performance-booster for watching directories on Windows
  gem "wdm", "~> 0.1.0" if Gem.win_platform?
end