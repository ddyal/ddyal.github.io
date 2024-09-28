source "https://rubygems.org"

# gem "jekyll", "~> 4.2.0"

gem "github-pages", group: :jekyll_plugins
gem "jekyll-include-cache", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jemoji"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", :platforms => [:jruby]

gem "minimal-mistakes-jekyll"
