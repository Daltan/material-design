# Material-Design

Material-Design is a material design theme for [Hugo](http://gohugo.io/).

## Features

- Material Design
- Google Analytics (optional)
- Pagination
- Disqus (optional)
- Twitter, Facebook, GitHub links (optional)
- Tags
- Categories
- Highlighting source code

## Installation

```shell
$ mkdir themes
$ cd themes
$ git clone https://github.com/pdevty/material-design
```

## Usage

```shell
$ hugo server -t material-design -w -D
```

## Configuration

config.toml

```toml
theme="material-design"
baseurl = "Your Site URL"
languageCode = "en-us"
title = "Your Site Title"
MetaDataFormat = "toml"
paginate = 9
disqusShortname = "Your Disqus Name" # optional
copyright = "© 2015 Copyright Text"

[params]
  description = "Your Site Description"
  twitter = "Your Twitter Name" # optional
  github = "Your Github Name" # optional
  facebook = "Your facebook Name" # optional
  headerCover = "images/headerCover.png" # optional
  footerCover = "images/footerCover.png" # optional
  googleAnalyticsUserID = "Your Analytics User Id" # optional
```

content file

```toml
+++
Categories = ["material","desgin"]
Tags = ["golang","development"]
date = "2015-05-16"
title = "About Hugo"

+++

content here
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request