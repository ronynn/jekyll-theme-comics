---
title: About
---

## Usage

To use the comics theme on github pages:

1. Add the following to your site's `_config.yml`:

    ```yml
    remote_theme: r01nx/jekyll-theme-comics
    plugins:
    - jekyll-remote-theme # add this line to the plugins list if you already have one
    ```

2. Optionally, if you'd like to preview your site on your computer, add the following to your site's `Gemfile`:

    ```ruby
    gem "github-pages", group: :jekyll_plugins
 
