This repository contains the source files for www.ufgmg.org. When a new commit
is pushed to this repository's `master` branch, Github runs Jekyll automatically
to update the live site.

## Setting up Jekyll for local testing

You need to have Ruby installed and the `gem` tool on your path.

1.  Install Bundler.

    ```bash
    $ gem install bundler
    ```

2.  Install this repo's bundle.

    ```bash
    $ bundle install --path .bundle
    ```

3.  Run Jekyll.

    ```bash
    $ bundle exec jekyll serve
    ```

4.  Point your web browser to http://localhost:4000.
