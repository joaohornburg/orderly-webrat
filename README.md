# Orderly Webrat

## Just forked!!!

This has just been forked. I will upload my code ASAP. For now, ignore instructions below...

-----------------------


Rspec matcher for asserting that this appears_before(that) in rspec request specs

## Installation

Add this line to your application's Gemfile:

    gem 'orderly'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install orderly

## Usage

In an rspec request spec, do

    this.should appear_before(that)

or, to assert that something does not appear before

    this.should_not appear_before(that)

Error handling in place for cases where this or that does not appear on the page.

## Todo
- Add TravisCI

## Contributing
Patches welcome! Submit a pull request.
