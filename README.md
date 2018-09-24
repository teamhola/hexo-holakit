# Hexo-HolaKit

A Hexo blog theme built with [Team ¡Hola!'s HolaKit](https://github.com/teamhola/holakit), based on Hexo's default Landscape theme.

- [¡Hola!'s Website (Built with this)](http://ihola.one)

## Installation

### Install

``` bash
$ git clone https://github.com/teamhola/hexo-holakit themes/holakit
```

### Enable

Modify `theme` setting in `_config.yml` to `holakit`.

#### Theme Config

To override our default values, use key `theme_config` in your `_config.yml`.

### Update

``` bash
cd themes/holakit
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
rss: /atom.xml

# Content
excerpt_link: Read More

# Sidebar
widgets:
- tag
- recent_posts
- partners

# Miscellaneous
google_analytics:
favicon: /favicon.png
```

- **menu** - Navigation menu
- **rss** - RSS link
- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **sidebar** - Sidebar style. You can choose `left`, `right`, `bottom` or `false`.
- **widgets** - Widgets displaying in sidebar
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path

## Features

### Sidebar

Hexo-HolaKit provides 4 built-in widgets:

- tag
- recent_posts
- public (For ¡Hola! Website only for now)
- partners

You can edit them in `widget` setting.

## Development

### Requirements

- Hexo 2.4+
- HolaKit 0.17+

[Hexo]: http://zespia.tw/hexo/
[HolaKit]: https://teamhola.github.com/holakit