# Tandoori Hugo - A minimalistic theme

![Tandoori Hugo Theme Screenshot](https://github.com/gnappuraz/tandoori-hugo/blob/master/images/screenshot.png)

## Installation
```
$ mkdir themes
$ cd themes
$ git submodule add https://github.com/gnappuraz/tandoori-hugo.git tandoori-hugo
```

See [the Hugo documentation](https://gohugo.io/themes/installing/) for more information.

## Extra Features

### Responsive
This theme is designed to look great on both large-screen and small-screen (mobile) devices.

### Syntax highlighting
This theme uses the default server-side Chroma highlighting, the style can be found in `css/style.css`.

### Google Analytics
To add Google Analytics, simply sign up to [Google Analytics](https://www.google.com/analytics/) to obtain your Google Tracking ID, and add this tracking ID to the `googleAnalytics` parameter in `config.toml`.

### Extra shortcodes
There are some extra shortcodes provided (along with the customized figure shortcode):

#### Details
This simply adds the html5 detail attribute, supported on all *modern* browsers. Use it like this:
```
{{% details "This is the details title (click to expand)" %}}
This is the content (hidden until clicked).
{{% /details %}}
```

#### Split
This adds a two column side-by-side environment (will turn into 1 col for narrow devices):
```
{{< columns >}}
This is column 1.
{{< column >}}
This is column 2.
{{< endcolumn >}}
```

#### Avatar
It creates a round cut-out of the image passed in `src`:
```
{{< avatar src="/images/avatar.png" >}}
```

#### Centered
Centers the content wrapping it in a `div` with `text-align: center`:
```
{{< centered >}}
    <span>Some text that need to be centered</span>
{{< centered />}}
```

## About
This is a modification of the [Beautiful Hugo](https://github.com/halogenica/beautifulhugo) theme by [Michael Romero](http://halogenica.net/about/). 
It supports most of the features of the original theme.

## License

MIT Licensed, see [LICENSE](https://github.com/gnappuraz/tandoori-hugo/blob/master/LICENSE).
