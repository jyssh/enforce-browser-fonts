# Enforce Browser Fonts

## What is this?

I prefer to use my own fonts instead of fonts set by websites. While firefox provides this configuration, it does not
let you easily toggle between browser and website fonts, which is a hassle, because quite a lot of time, I need to use
the website fonts (eg: fonts.google.com).

This Firefox WebExtension lets you toggle between browser and website fonts by:

1. clicking on the toolbar icon
2. pressing keyboard combo: <kbd>Alt-Comma</kbd>

The toolbar icon also acts as a visual cue: If it is coloured, then browser fonts are enforced. Otherwise, website fonts
are being used. The icon tooltip provides the textual cue for the same.

## Demo

![Demo](./demos/demo.gif)

## Releases

### Version 1.0

1. The user can now specify in the addon preferences which fonts - the browser fonts or the website fonts - should be
   enforced for all websites by default.

2. Enforcing browser/website fonts now operates at per-website-domain level, instead of the global level. A website
   domain by default uses the fonts set in the add-on preferences. If the user switches the fonts from the default for
   that domain, then the add-on will remember that change for that domain.

## Potential Upcoming Features

- [x] Customizable keyboard shortcuts. Firefox now lets the user to set a custom keyboard shortcut for each add-on

- [x] Configuration per website. As such, Firefox's setting is browser-wide. But I see a possibility of piping through the various extension APIs to
  make per-website configuration possible.
  *Available from v1*

- [ ] Keep the addon state in sync if a user changes the font configuration from Firefox's Preferences. Start
  from [here](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/types/BrowserSetting/onChange).

- [ ] Allow a user to edit the domains affected by the addon

- [ ] Allow a user to export/import domains affected by the addon

## Credits

Icons made by [Bainat](https://www.flaticon.com/authors/baianat) from [www.flaticon.com](https://www.flaticon.com/)
is licensed by [CC 3.0 BY](http://creativecommons.org/licenses/by/3.0/)