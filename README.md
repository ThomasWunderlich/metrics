## Metrics package
[![OS X Build Status](https://travis-ci.org/atom/metrics.svg?branch=master)](https://travis-ci.org/atom/metrics) [![Windows Build Status](https://ci.appveyor.com/api/projects/status/b5doi205xl3iex04/branch/master?svg=true)](https://ci.appveyor.com/project/Atom/metrics/branch/master) [![Dependency Status](https://david-dm.org/atom/metrics.svg)](https://david-dm.org/atom/metrics)

Report Atom usage metrics to the team by way of [Google Analytics][GA].



If you do not want this information reported, you can disable this package. Open the Settings View by running the `Settings View: Open` command from the Command Palette, go to the Packages section, and then find and disable the Metrics package.

### Collected data

* A unique UUID v4 random identifier is generated according to [RFC4122][RFC4122]
* Screen and window width and height
* Version of Atom being used including which release channel (stable, beta, dev)
* Name of each Atom view class or Atom configuration file opened in a pane, e.g. `EditorView`, `SettingsView`, `MarkdownPreviewView`, and `UserKeymap`. **No other pane item information is collected.**
* Exception messages (without paths)
* Heap memory used as MB and %
* Commands run (save core commands)
* Amount of time the current window was open for
* Amount of time the current window took to load
* Amount of time the app took to launch
* Deprecated package names and versions

[GA]: http://www.google.com/analytics
[RFC4122]: http://www.ietf.org/rfc/rfc4122.txt
