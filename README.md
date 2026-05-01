```commandline
rm -f Gemfile.lock
rm -rf .bundle vendor/bundle
bundle clean --force
rm -rf ~/gems/cache/*
bundle install
bundle exec jekyll serve --baseurl="" --incremental
```
