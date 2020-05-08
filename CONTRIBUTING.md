# CONTRIBUTING

Clone the project:

```
git clone git@github.com:Effilab/wice_grid.git
cd wice_grid/
```

Install the OS-specific dependencies:

- on macOS Catalina, using Homebrew:

  ```
  brew install v8@3.15
  bundle config build.libv8 --with-system-v8
  bundle config build.therubyracer --with-v8-dir=/usr/local/opt/v8@3.15

  brew cask install phantomjs
  ```

Then run bundler:

```
bundle
```

Run the tests:

```
rspec
```

## TODO

- Fix `rspec ./spec/features/csv_export_request_spec.rb:9 # CSV export WiceGrid should export csv`
