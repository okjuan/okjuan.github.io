source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.9.5"

# This is the default theme for new Jekyll sites. You may change this to anything you like.

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.17"

  # I want minima version 3+, which is not available on
  # reference:
  # - https://github.com/jekyll/minima/issues/454
  # - https://stackoverflow.com/questions/68518590/does-minima-dark-skin-work-on-github-ages
  gem "jekyll-remote-theme"
  gem "jekyll-seo-tag"

  # TODO: address build incompatibility with posix-spawn
  # An error occurred while installing posix-spawn (0.3.15), and Bundler cannot continue.
  gem "jekyll-last-modified-at"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?


gem "webrick", "~> 1.8"

gem "rexml", "~> 3.2"

gem "kramdown-parser-gfm"
