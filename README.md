# hugo-basic

A Hugo theme based on [Blank](https://github.com/Vimux/blank) by [Vimux](https://github.com/Vimux)

## Configuration
### Example `config.toml`
```toml
baseURL = 'http://www.example.com/' # the site URL
languageCode = 'en-us' # the language code
title = 'My Very Cool Site' # the site name
copyright = '2022 This Cool Person' # year and copyright holder

[menu]
  [[menu.main]]
        identifier = "posts"
        name = "Posts"
        url = "/posts/"
        weight = 1

[params]
  # used in the site metadata:
  description = "Description goes here" 
  author = "A Very Cool Developer"

  # used to customize the color scheme in light or dark mode
  # can be any color notation recognized by CSS
  # below values are the defaults
  backgroundColor = "#f8f9fa"
  textColor = "#34393f"
  accentColor = "#34393f"
  navColor = "blue"
  linkColor = "blue"
  visitedLinkColor = "purple"

  backgroundColorDarkMode = "#34393f"
  textColorDarkMode = "#f8f9fa"
  accentColorDarkMode = "#f8f9fa"
  navColorDarkMode = "skyblue"
  linkColorDarkMode = "skyblue"
  visitedLinkColorDarkMode = "lightblue"

  # used to set the main font of the document
  # should be a series of system fonts and fallbacks, or a custom font you've included the files for and a fallback
  # example: "Helvetica, Arial, sans-serif"
  # default is monospace
  font = "monospace"

  # the title for the content on the home page
  homeHeader = "Recent Posts"
```