source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

gem "github-pages", group: :jekyll_plugins

# If you want to use Jekyll native, uncomment the line below.
# To upgrade, run `bundle update`.

# gem "jekyll"

gem "wdm", "~> 0.1.0" if Gem.win_platform?
gem 'eventmachine', '1.2.7', platform: :ruby
gem 'nokogiri', '< 1.16'

# gem "github-pages", ">= 228", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  # gem "jekyll-archives"
  gem "jekyll-feed"
  gem 'jekyll-sitemap'
  # gem 'hawkins'
  # gem 'jekyll-liveserve'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]