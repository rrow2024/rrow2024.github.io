source "https://rubygems.org"

# After changing this file, run `bundle install`.
# To run the website, run `bundle exec jekyll serve`.

# This replaces gem "jekyll" for GitHub Pages.
gem "github-pages", "~> 231", group: :jekyll_plugins

# Themes
gem "minima", "~> 2.5"


# Other Jekyll plugins
group :jekyll_plugins do
  # gem "<name>", "~> <version>"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
# If this fails to install, try `gem install wdm -- --with-cflags=-Wno-implicit-function-declaration`.
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# This was throwing an error message until installed here.
gem "webrick", "~> 1.8"
