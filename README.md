Chargify Direct Example
=======================

This is a small [Sinatra](http://www.sinatrarb.com/) app that demonstrates how to use [Chargify Direct](http://docs.chargify.com/chargify-direct-introduction) for
Signups.  It leverages the new [Chargify2 gem](https://github.com/chargify/chargify2) to create the Direct secure form inputs and signature, verify the redirect response, and fetch the call response.

Requirements
---------------

Your current Ruby version should meet or exceed the version specified in [.ruby-version](.ruby-version).


Getting Started
---------------

1. Clone this repo to your local machine
2. Run `bundle install`
3. Copy `config/config.example.yml` to `config/config.yml`
4. Edit `config/config.yml` to add your own API User credentials
5. Create products on your API User's Site with handles 'basic' and 'pro' (or edit the example to match product handles you have)
6. Invoke the app with `bundle exec rackup` and play at <http://localhost:9292>
