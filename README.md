# mruby-first_gem   [![Build Status](https://travis-ci.org/elderica/mruby-first_gem.svg?branch=main)](https://travis-ci.org/elderica/mruby-first_gem)
CalcPI class
## install by mrbgems
- add conf.gem line to `build_config.rb`

```ruby
MRuby::Build.new do |conf|

    # ... (snip) ...

    conf.gem :github => 'elderica/mruby-first_gem'
end
```
## example
```ruby
> p CalcPI.new.gauss_l
3.141592653589792
```

## License
under the MIT License:
- see LICENSE file
