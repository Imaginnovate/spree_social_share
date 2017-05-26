SpreeSocialShare
================

Enables sharing of product information through social sites. Currently supports Facebook only 

## Installation

1. Add this extension to your Gemfile with this line:
  ```ruby
  gem 'spree_social_share', github: 'Imaginnovate/spree_social_share', branch: '3-1-stable'
  ```

  The `branch` option is important: it must match the version of Spree you're using.
  For example, use `3-1-stable` if you're using Spree `3-1-stable` or any `3.1.x` version.

2. Install the gem using Bundler:
  ```ruby
  bundle install
  ```

3. Copy & run migrations
  ```ruby
  bundle exec rails g spree_social_share:install
  ```

4. Restart your server

  If your server was running, restart it so that it can find the assets properly.


## Contributing

If you'd like to contribute, feel free to raise a good pull request.

Copyright (c) 2017 Imaginnovate, released under the MIT License
