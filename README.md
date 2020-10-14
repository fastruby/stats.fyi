# Stats.FYI

This project is a place to share `rails_stats` data for all your projects.

## Getting Started

You can locally setup this Rails application by calling this command:

```
./bin/setup
```

## Submitting Data

In order to submit data to your local instance, you can do it like this:

```
SHARE_URL=http://localhost:3000 bundle exec rake stats
```

If you want to use the default SHARE_URL (https://stats.fastruby.io) then you
can call `rake stats` like this: 

```
SHARE=true bundle exec rake stats
```

## Contributing

Bug reports and pull requests are welcome on GitHub at 
https://github.com/fastruby/stats.fyi/issues.

## Sponsorship

![FastRuby.io | Rails Upgrade Services](https://github.com/fastruby/stats.fyi/raw/master/fastruby-logo.png)

`stats.fyi` is maintained and sponsored by [FastRuby.io](https://fastruby.io). 
The names and logos for FastRuby.io are trademarks of The Lean Software Boutique 
LLC.
