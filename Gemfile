source "https://rubygems.org"

gem "jekyll", "~> 3.8.6"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

# For LiveReload: https://robbinespu.gitlab.io/posts/jekyll-unable-load-eventmachine/
gem 'eventmachine', '1.2.7', github: 'eventmachine/eventmachine', tag: 'v1.2.7'

