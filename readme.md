# Demo

![](demo.gif)

# Roadmap

- [] Customizable keyboard shortcut
- [] Configuration per website. As such, Firefox's setting is browser-wide. But I see a possibility of piping through the various extension APIs to make per-website configuration possible.

# Current Limitations

- Firefox stores this configuration browser-wide, not per-site. There is a way to emulate per-site enforcement, which is a milestone in the roadmap.
- Firefox has not (yet) implemented [this API](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/API/types/BrowserSetting/onChange), without which the addon cannot detect when user toggles the document fonts outside of addon, from browser preferences. Hence, the addon icon will go out of sync, at least until user uses the addon to toggle the fonts, or restarts the browser. This is not such a major annoyance, but worth mentioning anyway.

# Credits

- In-use icons: <div>
    Icons made by
    <a href="https://www.flaticon.com/authors/baianat" title="Baianat">Baianat</a>
    from
    <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
    is licensed by
    <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
</div>

- Backup icons: <div>
    Icons made by
    <a href="https://www.freepik.com/" title="Freepik">Freepik</a>
    from
    <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a>
    is licensed by
    <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
</div>


