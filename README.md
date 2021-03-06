# SassC [![Build Status](https://travis-ci.org/sass/sassc-ruby.svg?branch=master)](https://travis-ci.org/sass/sassc-ruby) [![Gem Version](https://badge.fury.io/rb/sassc.svg)](http://badge.fury.io/rb/sassc)

Use `libsass` with Ruby!

This gem combines the speed of `libsass`, the [Sass C implementation](https://github.com/sass/libsass), with the easy of use of the original [Ruby Sass](https://github.com/sass/sass) library.

### libsass Version

[3.3.2](https://github.com/sass/libsass/releases/tag/3.3.2)

## Usage

This library utilizes `libsass` to allow you to compile SCSS or SASS syntax
to CSS.  To compile, use a `SassC::Engine`.

**Note**:  If you want to use this library with Rails/Sprockets, check out
[sassc-rails](https://github.com/bolandrm/sassc-rails).

Additionally, you can use `SassC::Sass2Scss` to convert Sass syntax to Scss syntax.

## Credits

This gem is maintained by [Ryan Boland](https://ryanboland.com)
and [awesome contributors](https://github.com/bolandrm/sassc-ruby/graphs/contributors).

## Changelog

- **1.8.2**
  - Update to Libsass 3.3.2
- **1.8.1**
  - Update to Libsass 3.3.1
- **1.8.0**
  - Update to Libsass 3.3.0
- **1.8.0.pre2**
  - Fix bug with looking up gem_path
- **1.8.0.pre1**
  - [Update to Libsass 3.3.0-beta3](https://github.com/sass/sassc-ruby/pull/20)
- **1.7.1**
  - Some updates to `Engine` API.
- **1.7.0**
  - [Support Precision](https://github.com/sass/sassc-ruby/pull/19)
- **1.6.0**
  - [Support Sass Color types](https://github.com/bolandrm/sassc-ruby/pull/14)
  - [Support quoted strings](https://github.com/bolandrm/sassc-ruby/pull/13)
  - [Improve custom function error handling](https://github.com/bolandrm/sassc-ruby/pull/15)
- **1.5.1**
  - 2nd attempt at fixing compilation bug (issue [#12](https://github.com/bolandrm/sassc-ruby/issues/12))
- **1.5.0**
  - Add support for inline source maps
  - Fix compilation bug (issue [#12](https://github.com/bolandrm/sassc-ruby/issues/12))
- **1.4.0**
  - Add support for line number comments
- **1.3.0**
  - Support Sass color custom function arguments
  - Adds error handling for exceptions in custom functions
  - Custom functions may have optional/default arguments

## Contributing

### Project Setup

1. Clone repo
1. Install dependencies - `bundle install`
1. Run the tests - `bundle exec rake test`

### Code Changes

1. Fork it ( https://github.com/[my-github-username]/sassc/fork )
1. Create your feature branch (`git checkout -b my-new-feature`)
1. Commit your changes (`git commit -am 'Add some feature'`) - try to include tests
1. Push to the branch (`git push origin my-new-feature`)
1. Create a new Pull Request
