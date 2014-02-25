# Cats
[![Gem Version](https://badge.fury.io/rb/cats.png)](http://badge.fury.io/rb/cats)
[![Build Status](https://secure.travis-ci.org/nicolasmccurdy/cats.png?branch=master)](http://travis-ci.org/nicolasmccurdy/cats)
[![Dependency Status](https://gemnasium.com/nicolasmccurdy/cats.png)](https://gemnasium.com/nicolasmccurdy/cats)
[![Code Climate](https://codeclimate.com/github/thenickperson/cats.png)](https://codeclimate.com/github/thenickperson/cats)

A library/tool that does a small number of cat-related tasks. Cats currently
acts as a command line client and library for receiving cat facts.

## [Documentation](http://rubydoc.info/github/nicolasmccurdy/cats/frames)

## Installation
Add this line to your application's Gemfile:

    gem 'cats'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install cats

## Usage

### As a command line tool
```shell
$ cats fact
A cat can travel at a top speed of approximately 31 mph (49 km) over a short
distance.
```

### As a library
```ruby
require 'cats'

puts Cats.fact
```

## Credits
- List of cat facts: [CatFactsApi](https://github.com/pieces029/CatFactsApi)
  (MIT License)

## Contributing
1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
