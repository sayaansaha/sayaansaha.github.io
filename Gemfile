source "https://rubygems.org"
ruby RUBY_VERSION

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "3.3.1"
#debug tool pry
gem 'pry'
# Use jquery as the JavaScript library
gem 'jquery-rails'
#jquery UI to add interesting effects to jquery items
gem 'jquery-ui-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'



# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.0"

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'sqlite3','~> 1.3.11'
  gem 'byebug', platform: :mri
  gem 'factory_girl_rails', '~> 4.4.1'
  gem 'capybara', '2.4.1'
  gem 'database_cleaner', '1.3.0'
  gem 'rspec-rails', '~> 3.5'
  gem 'selenium-webdriver', '2.42.0'

end




# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
   gem "jekyll-feed", "~> 0.6"
end
