# Changelog

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