# inotify

**[WIP]** Inotify bindings for [Crystal language](https://github.com/crystal-lang/crystal)

## Installation

Add this to your application's `shard.yml`:

```yaml
dependencies:
  inotify:
    github: petoem/inotify.cr
```

## Usage

```crystal
require "inotify"

Inotify::Watcher.new("./path/to/watch") do |event|
  pp event
end
```

*Note: You have to run something in the main fiber or else your program will exit.* 


## Development

TODO: Write development instructions here

## Contributing

1. Fork it ( https://github.com/petoem/inotify.cr/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [petoem](https://github.com/petoem) Michael Petö - creator, maintainer
