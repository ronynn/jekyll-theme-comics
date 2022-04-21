---
title: Jekyll Theme Comics
---
<h2>Recent Blog Posts</h2>

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ site.url }}{{ post.url }}" class="link">
      <time class="">{{ post.date | date_to_string }} </time>
      : {{ post.title }}
    </a>
  </li>
  {% endfor %}
</ul>


A minimalist yet exciting theme based on action comics. Licensed under the [MIT License](./LICENSE).

## Roadmap

See the [open issues](https://github.com/r01nx/jekyll-theme-comics/issues) for a list of proposed features (and known issues).

## Project philosophy

The Comics theme originated from the idea of presenting a page with a colorscheme that excites the vision. It is intended to make it quick and easy for users to create a website. The theme is perfect for exciting projects, erring on the side of simplicity rather than flexibility, and provide users the opportunity to opt-in to additional complexity if they have specific needs or wish to further customize their experience (such as adding custom CSS or modifying the default layout). It should also look great, but that goes without saying.

## Contributing

Interested in contributing to Comics? I'd love your help. Comics is an open source project.

## Author

[rohan](https://github.com/r01nx)

