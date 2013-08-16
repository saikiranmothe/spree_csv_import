SpreeCsvImport
==============

Introduction goes here.

Installation
------------

Add spree_csv_import to your Gemfile:

```ruby
gem 'spree_csv_import'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g spree_csv_import:install
```

Testing
-------

Be sure to bundle your dependencies and then create a dummy test app for the specs to run against.

```shell
bundle
bundle exec rake test_app
bundle exec rspec spec
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'spree_csv_import/factories'
```

Copyright (c) 2013 [sai kiran mothe], released under the New BSD License
