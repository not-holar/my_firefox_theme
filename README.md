# My Firefox Theme
 
Welcome to the repo for my Firefox theme, a theme that aims to look nice and clean while not compromising functionality.

![Screenshot](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/screenshots/screenshot.png)

[See More Screenshots](SCREENSHOTS.md)

# Installation

## Firefox

> **Recommended**: install the Tree Style Tabs extension first before you do this as the theme will hide the tab bar.

1. Copy the files from [firefox/chrome](firefox/chrome) into the ```chrome``` folder (doesn't exist by default) in your Firefox profile directory. To find your profile directory, go to about:support.
2. Go to about:config, agree that you are responsible for everything horrible you are going to do next.
3. Set ```toolkit.legacyUserProfileCustomizations.stylesheets``` to ```true```.
4. Set ```svg.context-properties.content.enabled``` to ```true```.
5. Restart Firefox.

### Optional
Download and install [Google Sans](https://www.google.com/search?q=Google+Sans).

The toolbar layout i use:
![](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/firefox/toolbar_layout.png)

> The .css files have **a lot** of ~~dead~~ commented out styles, you can lurk around and potentially find something you like, or just remove all of them and minify the files, if that's what you like.

## Tree Style Tabs

1. [Download Tree Style Tabs from Mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
2. Set the main settings (important ones are underlined) like so: [Settings Screenshot](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/settings.png).
3. Scroll down and copy-paste everything from [tree_style_tabs/extra_style_rules.css](tree_style_tabs/extra_style_rules.css) to [here](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/put_css_here.png).

## Reddit Theme

Any custom css extension will work, below are the instructions for **Stylus**:

1. Switch to the old (classic) version of Reddit
2. Go to Stylus > Manage > Write new style > Mozilla Format > Import.
3. Paste everything from [reddit/mozilla_format.css](reddit/mozilla_format.css).
4. Press either Overwrite or Append.
5. Name it whatever you'd like.
6. Press Save.

# If you have anything to say

If you have any issues or suggestions, feel free to create an issue here on Github!

Pull Requests are also welcome.
