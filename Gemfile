source 'https://rubygems.org'

gem 'jekyll', "~> 4.3.2"

# Core plugins that directly affect site building
group :jekyll_plugins do
     gem "jekyll-feed", "~> 0.15"
  gem "jekyll-seo-tag"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-scholar"
  gem "jekyll-include-cache"
end

# Gems for development or external data fetching (outside :jekyll_plugins)
group :other_plugins do
    gem 'css_parser'
    gem 'feedjira'
    gem 'httparty'
    gem 'observer'       # used by jekyll-scholar
    gem 'ostruct'        # used by jekyll-twitter-plugin
    # gem 'terser'         # used by jekyll-terser
    # gem 'unicode_utils' -- should be already installed by jekyll
    # gem 'webrick' -- should be already installed by jekyll
end
