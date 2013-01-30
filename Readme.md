# Lanyrd

Wrapper around the Lanyrd iOS client api.

    @lanyrd   = Lanyrd::Client.new
    attendees = @lanyrd.attendees("fosdem")

## Development

Source hosted at [GitHub](http://github.com/andrew/lanyrd).
Report Issues/Feature requests on [GitHub Issues](http://github.com/andrew/lanyrd/issues).

Tests can be ran with `rake spec`

### Note on Patches/Pull Requests

 * Fork the project.
 * Make your feature addition or bug fix.
 * Add tests for it. This is important so I don't break it in a
   future version unintentionally.
 * Commit, do not mess with rakefile, version, or history.
   (if you want to have your own version, that is fine but bump version in a commit by itself I can ignore when I pull)
 * Send me a pull request. Bonus points for topic branches.

## Copyright

Copyright (c) 2013 Andrew Nesbitt. See [LICENSE](https://github.com/andrew/lanyrd/blob/master/LICENSE) for details.