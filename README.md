# My Firefox Theme
 
Welcome to the repo for my Firefox theme, a theme that aims to look nice and clean while not compromising functionality

<p align="center">
	<img src="https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/screenshot.png" alt="Screenshot">
</p>

## Installation

### Firefox

**Recommended**: install the Tree Style Tabs extension first before you do this as the theme will hide the tab bar.

1. Copy the files from [firefox/userchrome](firefox/userchrome) into the ```chrome``` folder (doesn't exist by default) in your Firefox profile directory. To find your profile directory, go to about:support.
2. Go to about:config, agree that you are responsible for everything horrible you are going to do next.
2. Set ```toolkit.legacyUserProfileCustomizations.stylesheets``` to ```true```.
3. Set ```svg.context-properties.content.enabled``` to ```true```.
4. Restart Firefox.

*(Optional) The toolbar layout i use:*
<p align="center">
	<img src="https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/firefox/toolbar_layout.png" alt="Toolbar Layout Screenshot">
</p>

### Tree Style Tabs

[Download Tree Style Tabs from Mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/)

*Main settings (Important ones are underlined):*
<img src="https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/settings.png">

*Then scroll down and copy-paste everything from [tree_style_tabs/extra_style_rules.css](tree_style_tabs/extra_style_rules.css) here:*
<img src="https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/put_css_here.png">

### Reddit Theme

Any custom css extension will work, below are the instructions for **Stylus**:
1. Go to Stylus > Manage > Write new style > Mozilla Format > Import
2. Paste everything from [reddit/mozilla_format.css](reddit/mozilla_format.css)
3. Press either Overwrite or Append
4. Name it whatever you'd like
5. Press Save

## If you have anything to say

If you have any issues or suggestions feel free to create an issue here on Github
