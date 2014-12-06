# sasaplus1.github.io

my website

## How to setup

requirements:

- rbenv
- ruby-build
- rbenv-gem-rehash

install Ruby 2.1.1 by rbenv:

```sh
$ rbenv install 2.1.1
```

install bundler and install required gems by bundler:

```sh
$ echo 'gem: --no-document' >> $HOME/.gemrc
$ gem install bundler
$ rake install
```

## Rakefile tasks

- install
  - install required gems
- preview (default task)
  - preview in local
