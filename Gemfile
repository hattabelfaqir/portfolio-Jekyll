# Gemfile pour le projet Jekyll HATTA BELFAQIR
# =====================================================
source "https://rubygems.org"

# Version de Jekyll
gem "jekyll", "~> 4.4"

# Theme Hydejack (remote ou local)
gem "jekyll-theme-hydejack", "~> 9.1"
gem "jekyll-remote-theme"

# Math support (optionnel)
gem "kramdown-math-katex"
gem "duktape"

# Nécessaire pour jekyll serve sur Ruby 3+
gem "webrick"

# Plugins Jekyll officiels et tiers
group :jekyll_plugins do
  gem "jekyll-default-layout"
  gem "jekyll-feed"
  gem "jekyll-optional-front-matter"
  gem "jekyll-paginate"
  gem "jekyll-readme-index"
  gem "jekyll-redirect-from"
  gem "jekyll-relative-links"
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-titles-from-headings"
  gem "jekyll-include-cache"

  # Plugins non-GitHub Pages (utiles pour local)
  gem "jekyll-last-modified-at"
  gem "jekyll-compose"
end

# Gems spécifiques Windows
gem 'wdm' if Gem.win_platform?
gem "tzinfo-data" if Gem.win_platform?
