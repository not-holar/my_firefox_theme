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
5. In the **Customize...** menu, set density to Normal.
6. Download and install [Google Sans](https://www.google.com/search?q=Google+Sans), [Open Sans](https://www.google.com/search?q=Open+Sans) or [Noto Sans](https://www.google.com/search?q=Noto+Sans). Alternatively, remove these two rules: [in userChrome](https://github.com/not-holar/my_firefox_theme/blob/7a2d0e4ec371a283d10a42515422af001ba5b18d/firefox/chrome/userChrome.css#L1-L5), [in userContent](https://github.com/not-holar/my_firefox_theme/blob/7a2d0e4ec371a283d10a42515422af001ba5b18d/firefox/chrome/userContent.css#L7-L9).
7. Restart Firefox.

### Optional

The toolbar layout i use:
![](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/firefox/toolbar_layout.png)

## Tree Style Tabs

1. [Download Tree Style Tabs from Mozilla.org](https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
2. Set the main settings (important ones are underlined) like so: [Settings Screenshot](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/settings.png).
3. Scroll down and copy-paste everything from [tree_style_tabs/extra_style_rules.css](tree_style_tabs/extra_style_rules.css) to [here](https://raw.githubusercontent.com/not-holar/my_firefox_theme/master/tree_style_tabs/put_css_here.png).
4. Allow TST to run in private windows to not lose tabs in incognito.

## Taskbar Icon

Windows 10 instructions:
1. Right-click Firefox in the taskbar.
2. In the popup, right-click *Firefox*.
3. Click **Properties** > **Change Icon...** > **Browse...**.
4. Select [icon/Firefox_Project_Logo,_2019-2.ico](icon/Firefox_Project_Logo,_2019-2.ico).
5. If pinned, unpin Firefox, restart and repin.
6. If not, just restart.
7. If the icon still doesn't change, try restarting explorer.exe or logging out and back in.

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
