# annotator-rails

annotator-rails wraps the [Annotator](http://annotatorjs.org/) library in a
rails engine for simple use with the asset pipeline provided by Rails 3.1 and
higher. The gem includes the development (non-minified) source for ease of
exploration. The asset pipeline will minify in production.

Annotator is "an open-source JavaScript library to easily add annotation
functionality to any webpage.". Please see its
[documentation](https://annotator.readthedocs.org/en/latest/index.html) for
details.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'annotator-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install annotator-rails

Add the following directive to your Javascript manifest file (application.js):

    //= require annotator


## Versioning

annotator-rails 2.0.0-alpha.3 -> Annotator 2.0.0-alpha.3

Every attempt is made to mirror the currently shipping Annotator version
number wherever possible. The major, minor, and patch version numbers will
always represent the Annotator version. Should a gem bug be discovered, a 4th
version identifier will be added and incremented.


## Thanks

Thanks to [Derek Prior](https://github.com/derekprior) for his
[blog post regarding Gem packaging](http://www.prioritized.net/blog/gemify-assets-for-rails/)
and for packaging [momentjs-rails](https://github.com/derekprior/momentjs-rails).
I shamelessly copyied the whole structure.
