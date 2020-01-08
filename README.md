# CactusX

CactusX is an improved and modernized version of the [Cactus theme](https://github.com/digitalcraftsman/hugo-cactus-theme). Features include:

* use of .scss instead of .css by leveraging Hugo's asset pipeline feature
* asset minification, also via Hugo asset pipeline
* removal of redundant highlight.js code; Hugo has built-in server-side code highlighting via [Chroma](https://gohugo.io/content-management/syntax-highlighting/)
* using the more modern `gtag.js` analytics (and loading it asynchronously for better performance) from Google instead of the old `analytics.js`
* vectorized, svg avatar (never blurry, scales perfectly with DPI)
* fast loads with [instant.page](https://instant.page/) and minimal icon font set from [fontello](http://fontello.com/)

Install by cloning `https://github.com/sammymax/hugo-cactus-x.git` into your themes `folder`.

![Screenshot](https://raw.githubusercontent.com/sammymax/hugo-cactus-x/master/images/screenshot.png)

The original readme is below.

# Cactus Theme

Cactus is a minimalistic theme for bloggers based on the default theme of the same-named [Cactus static site generator](//github.com/koenbok/Cactus) written in Python and [Nick Balestra](//github.com/nickbalestra/kactus)'s Jekyll port. Noteworthy features of this Hugo theme are the integration of a comment-system powered by Disqus, a customizable about page, support for RSS feeds, syntax highlighting for source code, and sharing options for blog posts.


![Screenshot](https://raw.githubusercontent.com/digitalcraftsman/hugo-cactus-theme/dev/images/screenshot.png)


## Installation

Inside the folder of your Hugo site, run:

    $ cd themes
    $ git clone https://github.com/digitalcraftsman/hugo-cactus-theme.git

For more information, please read Hugo's official [setup guide](//gohugo.io/overview/installing/).

### The config file

Take a look inside the [`exampleSite`](//github.com/digitalcraftsman/hugo-cactus-theme/tree/dev/exampleSite) folder of this theme. You'll find a file called [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml).

To use it, copy the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) file to the root folder of your Hugo site. Feel free to change the strings as you like to customize your website.

Make sure to update the `themesDir` property in the config file to point to your site's theme folder, otherwise an error will be thrown indicating the themes folder is unable to be found.

## About page

Use the about page to introduce yourself to your visitors. You can customize the content as you like in the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml). Furthermore, you should replace the [avatar placeholder](//github.com/digitalcraftsman/hugo-cactus-theme/blob/master/static/images/avatar.png) with a great image of yourself.

## Disqus

This theme features a comment system powered by Disqus too. Just add your Disqus-shortname to the [`config.toml`](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/exampleSite/config.toml) and let readers respond to your blog posts.

## Nearly finished

To see your site in action, run Hugo's built-in local server.

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Found a bug or got an idea for a new feature? Feel free to use the [issue tracker](//github.com/digitalcraftsman/hugo-cactus-theme/issues) to let me know. Or directly make a [pull request](//github.com/digitalcraftsman/hugo-cactus-theme/pulls).

Please create a separate branch for your pull request.


## License

This theme is released under the MIT license. For more information read the [license](//github.com/digitalcraftsman/hugo-cactus-theme/blob/dev/LICENSE.md).


## Acknowledgements

Thanks to

- [Nick Balestra](//github.com/nickbalestra/kactus) for creating the original theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project.
