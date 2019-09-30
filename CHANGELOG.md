# Changelog

### 30th September 2019

**Note: due to deprecation and addtion of certain Hugo features and variables the required minumum version of Hugo is now `0.57.2`**

`.Site.RegularPages` in combination with `.Site.Params.mainSections` is used to define the kind of content shown on the homepage ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/92891fe6186515ade4c18bde12bee53b6aef7c0d)). This is a more flexible approach than hard-coding the `post` content type. Add the following lines to your config file to restore the old behavior (TOML version):

```toml
[params]
mainSections = ["post"]
```

Furthermore, all instances of the `.Hugo` template variable have been replaced with the `hugo` template function ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/561374e3bb98d234f0ced7dd34e28d68e016f3b7)). RSS feeds are now included using Hugo's `OutputFormats` feature ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/ee4a1be11e060e69f40f340eff11b95d9be0a0ce)).

### 21st December 2016

Custom assets can now be linked with the `custom_js` and `custom_css` variables ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/d084de82d969d36b38765f5499a3a558f475182e))

The `exampleSite` folder is now a standalone Hugo website that can be used to preview the theme. Make sure you change the `themesDir` variable in the config file as described in the "Installation" section of the README ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/d084de82d969d36b38765f5499a3a558f475182e))

Now, this theme makes use of Hugo's own Google Analytics template ([show diff](https://github.com/digitalcraftsman/hugo-minimalist-theme/commit/4e2916a4bc11ce3191dd325e17237a25d01f5b58)). You have to move your tracking code in the config file as follows:

```toml
# Remove
[params]
    google_analytics = ""

# and add outside the params block
googleAnalytics = ""
```