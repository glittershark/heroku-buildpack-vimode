heroku-buildpack-vimode
=======================
Buildpack intended for use with [heroku-buildpack-multi][bm] to set vi-mode in
the Readline config on heroku, for use with Rails Console, etc.

[bm]: https://github.com/ddollar/heroku-buildpack-multi

## Usage

Just add it as a line to your `.buildpacks` file, ie:

```
> cat .buildpacks

https://github.com/glittershark/heroku-buildpack-vimode
https://github.com/heroku/heroku-buildpack-ruby
```

## License

Licensed under the MIT License
