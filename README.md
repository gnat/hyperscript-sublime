# [Hyperscript](https://hyperscript.org) for Sublime Text

Provides syntax highlighting for the Hyperscript (`_hyperscript`) language, both embedded in HTML and in a standalone file.

[Hyperscript](https://hyperscript.org) is the companion project of [HTMX](https://htmx.org). A recommended alternative to Stimulus, Alpine.js, jQuery.

<a href="https://github.com/gnat/hyperscript-sublime/tags">
    <img src="https://img.shields.io/github/v/tag/gnat/hyperscript-sublime?label=release&style=for-the-badge&color=%230288D1" /></a>
<!--<a href="https://packagecontrol.io/packages/Sublime%20Outline%20Notes%20Publisher">
    <img src="https://img.shields.io/packagecontrol/dt/Sublime%20Outline%20Notes%20Publisher?style=for-the-badge&color=%2315b713" /></a>-->
<a href="https://www.sublimetext.com/">
    <img src="https://img.shields.io/badge/Only%20For-Sublime-ff9800?logo=sublime%20text&style=for-the-badge" /></a>

### What is Hyperscript?

* Event-oriented language.
* [Locality of Behaviour](https://htmx.org/essays/locality-of-behaviour) instead of verbose javascript modules.
* Async transparency.
* No long event chains / christmas trees.
* Null safe.
* Self-documenting natural syntax inspired by [Hypertalk](https://en.wikipedia.org/wiki/HyperTalk) and [AppleScript](https://en.wikipedia.org/wiki/AppleScript).
* Saves a ton of code in components.

See: [A First Look at Hyperscript](https://putyourlightson.com/articles/a-first-look-at-hyperscript)

[![What is hyperscript / HTMX ?](http://img.youtube.com/vi/u2rjnLJ1M98/0.jpg)](http://www.youtube.com/watch?v=u2rjnLJ1M98 "What is hyperscript / HTMX ?")

### Sample Highlighting

![image](https://user-images.githubusercontent.com/24665/174639996-2daf319b-2d4c-4be7-93ac-4b3540908c2c.png)
(Color scheme: [Invader Zim](https://github.com/gnat/sublime-invader-zim))

### Installation

Option A (Package Control. 🙏🏻 Soon!): `Preferences` ➡️ `Package Control` ➡️ `Install Package` ➡️ `Hyperscript` ➡️ ENTER

Turn it on: `View` ➡️ `Syntax` ➡️ `Hyperscript` ➡️ `HTML (Hyperscript)`

Option B (Direct): `Preferences` ➡️ `Browse Packages ...` ➡️ `cd User` ➡️ [Download and extract the latest.](https://github.com/gnat/hyperscript-sublime/archive/refs/heads/main.zip)

Turn it on: `View` ➡️ `Syntax` ➡️ `User` or `hyperscript-sublime` or `Hyperscript` ➡️ `HTML (Hyperscript)`

Enjoy! 🙂 Find the community [on the discord](https://htmx.org/discord)! Check out the [Hyperscript Cheatsheet](https://thisweek.htmx.org/assets/2021-12-19/hyperscript-cheatsheet.pdf)!

### What is the relationship between HTMX and Hyperscript?

* HTMX and Hyperscript are sibling projects.
* They are designed to work well together, HTMX for server-interactions and Hyperscript for pure front-end interactions, but neither requires the other.

### Highlighting enabled for...

Tag attributes supported:

* `_=""`
* `hs=""`
* `data-hs=""`

Script tag:

* `<script type="text/hyperscript"></script>`

### Suggested Sublime Color Schemes

* [Invader Zim](https://github.com/gnat/sublime-invader-zim) 🛸
* Mariana (Built-in)
* Monokai (Built-in)

### Special Thanks

* [Carson Gross](https://github.com/bigskysoftware), creator of hyperscript and HTMX.
* [Deniz Akşimşek (dz4k)](https://github.com/dz4k) for the original syntax highlighter for VS Code / VS Codium.
* [deathaxe](https://github.com/deathaxe) and [jfcherng](https://github.com/jfcherng) for ensuring a smooth launch to Sublime Package Control.
* The hyperscript and HTMX community.

### References

* [Hyperscript](https://hyperscript.org/)
* [HTMX](https://htmx.org)
* [A first look at Hyperscript](https://putyourlightson.com/articles/a-first-look-at-hyperscript)
* [Hyperscript Cheatsheet](https://thisweek.htmx.org/assets/2021-12-19/hyperscript-cheatsheet.pdf)
* [Plugin for VSCode](https://marketplace.visualstudio.com/items?itemName=dz4k.vscode-hyperscript-org)
