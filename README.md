# MuchStyleGuide

A ruby-style guide and supporting [Rubocop](https://rubocop.org/) configs.

## Usage

Bundle the gem.

```ruby
gem "much-style-guide", "~> x.x.x", require: false
```

It is recommended you lock into only getting patch release updates and explicitly upgrade non-patch releases as configuration _additions_ won't be made in patch releases.

Then run Rubocop like you normally would, e.g.:

```
$ rubocop
```

## Dependencies

* [Rubocop](https://rubocop.org/) version

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am "Added some feature"`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
