### Setup

This repo is designed to provide additional vim plugins for use via
[Janus](https://github.com/carlhuda/janus). Once Janus is installed and
running, do the following:

```
$ git clone https://github.com/bval/vim-plugins ~/.janus
$ git submodule init && git submodule update
$ cd ~/.janus
$ sudo gem install bundler
$ sudo bundle install
```

### Contributing

To add new submodules:

```
$ cd ~/.janus
$ git submodule add https://github.com/org/vim-plugin-repo
$ git commit
```

Be sure to add any requisite gems for your vim plugins to the Gemfile
and re-run `bundle install` if necessary.
