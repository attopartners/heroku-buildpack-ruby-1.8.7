Heroku buildpack: Ruby
======================

This was a fork of the standard
[Heroku buildpack](http://devcenter.heroku.com/articles/buildpack) for
Ruby, Rack, and Rails apps.  It's reason for being was to provide the
ability to run apps requiring Ruby version 1.8.7 on the Cedar stack.

However, with advancement's in Heroku's own Ruby buildpack, the need for
this one has faded.  Heroku now supports multiple
[Ruby versions](https://devcenter.heroku.com/articles/ruby-versions) by
specifying the version in your project's Gemfile.

One of those versions is Ruby 1.8.7, and therefore we no longer need to
use this custom buildpack.

The full list of Rubies supported by Heroku's buildpack is available
[here](https://s3.amazonaws.com/heroku-buildpack-ruby/ruby_versions.yml).
