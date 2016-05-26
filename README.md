# Cutestrap
[Cutestrap](http://cutestrap.com) is a 8KB CSS framework with vertical rhythm, grid and form controls. It is an alternative to bootstrap.

Cutestrap is made by Tyler Childs. This gem is an unofficial integration of latest cutestrap to Rails 3.x & rails 4.x

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'cutestrap'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install cutestrap

## Usage
At application.css
```
*= require_tree .
*= require cutestrap
*= require_self
```
## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/cutestrap. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
