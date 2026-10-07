source "https://rubygems.org"

# github-pages gem forces safe mode, which triggers a Windows case-sensitivity
# bug in jekyll-sass-converter's path resolution (Dir.glob returns filesystem
# casing that differs from the pwd casing, sanitized_path rejects the mismatch,
# and SCSS load paths end up empty). Using individual gems instead.
# GitHub Pages uses its own fixed build environment regardless of this Gemfile.
gem "jekyll", "~> 3.10"

group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-seo-tag"
  gem "jekyll-redirect-from"
end

gem "kramdown-parser-gfm"

# Windows lacks a system timezone database; Jekyll needs this to build locally.
# Platform-gated, so it is a no-op on the Linux runners GitHub Pages builds on.
gem "tzinfo-data", platforms: [:windows, :jruby]
