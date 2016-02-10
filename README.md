# Minimalist

Minimalist is a responsive theme with a focus on blogging based on the [Minimalistic](Minimalistic) Ghost theme made by [Raphael Riegger](https://github.com/rriegger). Noteworthy features of this Hugo theme are the integration of a comment-system powered by Disqus, easy localization (l10n), support for RSS feeds, syntax highlighting for source code and sharing options in the blog posts.

<span align="center">![](https://raw.githubusercontent.com/digitalcraftsman/hugo-minimalist-theme/master/images/screenshot.png)</span>


## Installation

Inside the folder of your Hugo site run:

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/digitalcraftsman/hugo-minimalist-theme.git

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### The config file

Take a look inside the [`exampleSite`](https://github.com/digitalcraftsman/hugo-minimalist-theme/tree/master/exampleSite) folder of this theme. You'll find a file called [`config.toml`](https://github.com/digitalcraftsman/hugo-minimalist-theme/blob/master/exampleSite/config.toml).

To use it, copy the [`config.toml`](https://github.com/digitalcraftsman/hugo-minimalist-theme/blob/master/exampleSite/config.toml) in the root folder of your Hugo site. Play around with the settings to tweak your site as you like.


## Localization (l10n)

Localization allows you to easily translate all strings in our website. Within [`exampleSite/data`](https://github.com/digitalcraftsman/hugo-minimalist-theme/tree/master/exampleSite/data) you'll find a file called [`l10n.toml`](https://github.com/digitalcraftsman/hugo-minimalist-theme/blob/master/exampleSite/data/l10n.toml). If you're not blogging in English replace all strings with their equivalents of your preferred language.


## Nearly finished

In order to see your site in action, run Hugo's built-in local server.

    $ hugo server

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Contributing

Did you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/digitalcraftsman/hugo-minimalist-theme/issues) to let me know. Or make directly a [pull request](https://github.com/digitalcraftsman/hugo-minimalist-theme/pulls).


## License

This theme is released under the Apache License 2.0. For more information read the [License](//github.com/digitalcraftsman/hugo-minimalist-theme/blob/dev/LICENSE.md).


## Annotations

Thanks to 
        
- [Raphael Riegger](https://github.com/rriegger) for creating the original theme
- [Steve Francia](//github.com/spf13) for creating Hugo and the awesome community around the project
