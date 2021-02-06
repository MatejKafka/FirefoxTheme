# Monochrome Tree - a minimalistic Firefox theme

A minimalistic Firefox theme, with visual support for Tree Style Tab and automatic theme switching based on system theme.

Main design goal was to maximize useful screen space for laptop screens, even at the cost of pretty whitespace. If you enjoy working in a terminal, you'll probably feel right at home.

## Screenshots

Dark theme:

![Dark theme](https://raw.githubusercontent.com/MatejKafka/FirefoxTheme/master/assets/img/darkTheme.png)

Light theme:

![](https://raw.githubusercontent.com/MatejKafka/FirefoxTheme/master/assets/img/lightTheme.png)

## Setup

1. Install Tree Style Tab extension (https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/).
2. Enable custom styling support (see https://www.reddit.com/r/FirefoxCSS/comments/73dvty/tutorial_how_to_create_and_livedebug_userchromecss/).
3. Copy `userChrome.css` and `userContent.css` to your `chrome` directory (details in the reddit post linked above).
4. Open `about:addons` in Firefox:
	1. Allow the Tree Style Tab extension to run in private windows.
	2. In the "Options" tab, scroll to the "Advanced" section, look for an input field labeled "Extra style rules for contents provided by Tree Style Tab".
	3. Press the "Load from File" button and select the `TreeStyleTab.css` file from this repository.
5. Restart Firefox.
6. Enjoy the new look, create an issue here on GitHub if something seems to be broken.

## Questions

### How do I switch between light and dark theme?

The color scheme automatically  changes based on system theme, so switch on/off dark mode in system settings (on Windows 10, search "dark mode" in Start menu).

### How do I maximize/minimize/close the window?

Learn your keyboard shortcuts. :)

For Windows, it's `Win-UpArrow` to maximize, `Alt-f4` to close a window. Minimizing is a bit more complicated, simplest way I know is `Alt-Space`, followed by `n`. Personally, I use a custom AutoHotkey binding where `RShift` minimizes current window.