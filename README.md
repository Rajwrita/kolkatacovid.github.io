# Kolkata Covid Help Website

## Usage

You'll need to have [Jekyll](https://jekyllrb.com/), the `bundler` gem, and [`yarn`](https://yarnpkg.com/) (`npm` also works) installed on our computer. Summer provides a fully furnished Jekyll setup — just clone and install the dependencies:

```bash
# Ruby gems
bundle install
# Node modules
yarn
```

Then simply run `yarn start` to start the Jekyll server on port `4000`.

## Local Development

1. Install Install Ruby / Jekyll
2. Clone the repo `git clone https://github.com/kolkatacovid/kolkatacovid.github.io.git`
3. Empty out the url in `_config.yml`
4. The steps below will serve your site locally
  ```bash
$ cd kolkatacovid.github.io
$ bundle install
$ bundle exec jekyll serve
``` 
5. View the website at http://127.0.0.1:4000/



## Options

Summer includes some customizable options, applied via options in the `_config.yml` file. A standout feature is the dark theme.
Have a look at the [`_config.yml`](_config.yml) file for all available options.

## Contributing

We welcome bug fixes and feature request through [pull requests](https://github.com/kolkatacovid/kolkatacovid.github.io/compare). If you don't feel comfortable making code changes, feel free to [open an issue](https://github.com/kolkatacovid/kolkatacovid.github.io/issues/new), perhaps somebody else will help out.

## License

Open sourced under the [MIT license](LICENSE.md).

💛
