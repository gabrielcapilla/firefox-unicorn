# LACONIC

Tabs in Laconic make less noise, giving more room to browse the web letting you see what’s important to prevent you from getting distracted. One file without surprises. Only 3.6KiB, as simple as you always wanted.

![image](/assets/images/headerdark.png)

## Keyboard Centered Design

See quick definitions and answers. Jump to any site quickly. Use the shortcuts.

- `Ctrl + W` Closes a Tab
- `Ctrl + T` Opens a New Tab
- `Ctrl + L` focuses the URL bar
- `Ctrl + B` shows you the Bookmarks
- `Ctrl + H` shows you the History Bar
- `Ctrl + R` Refresh the page you're on
- `Ctrl + Shift + A` Quick open for Add-Ons
- `Ctrl + Shift + T` Re-opens a tab that you just closed

## Protect your privacy

Works on top of Firefox, and [uBlock Origin works best on Firefox](https://github.com/gorhill/uBlock/wiki/uBlock-Origin-works-best-on-Firefox). Stops ads and trackers, so you can browse faster without being tracked. And when you’re using a slow or expensive internet connection, it lets you block scripts and images, so pages load faster and use less data.

## Installation

To install this theme, do the following:

    Type about:config in the address bar of Firefox.
    Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and put it on `true`. Then restart the browser.

Chrome folder:

    Type about:profiles in the address bar of Firefox and find your profile folder.
    Create a folder named `chrome` in your profile folder(s). Add the file `userChrome.css` in the `chrome` folder.

## Make it yours

### Do you use KDE?

Add to your `about:config` the following parameters:

`widget.use-xdg-desktop-portal.file-picker` `1`
`widget.use-xdg-desktop-portal.mime-handler` `1`

### Rounded corners

In `about:config` you can make the bottom window corners rounded by setting `widget.gtk.rounded-bottom-corners.enabled` to `true`.

### Inspiration

Inspired by [Min Browser](https://github.com/minbrowser/min). I wanted to bring the Min Browser experience closer to Firefox. Min is written entirely with CSS and JavaScript using Electron, and is open-source software.
