# [Hyperscript](https://hyperscript.org) for Sublime Text

Provides syntax highlighting for the Hyperscript (`_hyperscript`) scripting language, both embedded in HTML and in a standalone file.

[Hyperscript](https://hyperscript.org) is the companion project of [HTMX](https://htmx.org).

### What is hyperscript?

* Event-oriented language.
* [Locality of Behaviour](https://htmx.org/essays/locality-of-behaviour) in components instead of long javascript modules.
* Async transparency.
* No long event chains / christmas trees.
* Null safe.
* Saves a ton of code in components.

[![What is hyperscript / HTMX ?](http://img.youtube.com/vi/u2rjnLJ1M98/0.jpg)](http://www.youtube.com/watch?v=u2rjnLJ1M98 "What is hyperscript / HTMX ?")

### Installation

Option A (Package Control. 🙏🏻 Soon!): `Preferences` ➡️ `Package Control` ➡️ `Install Package` ➡️ `Hyperscript` ➡️ ENTER

Option B (Direct): `Preferences` ➡️ `Package Control` ➡️ `Browse Packages ...` ➡️ `cd User` ➡️ (Download and extract the latest.)[https://github.com/gnat/hyperscript-sublime/archive/refs/heads/main.zip]

Turn it on: Open your file containing hyperscript! ➡️ `View` ➡️ `Syntax` ➡️ `Hyperscript` ➡️ `HTML (Hyperscript)`

Enjoy!

### Questions? Issues?

Find the community (on the discord)[https://htmx.org/discord]!

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

File extensions:

* `*.hs`

### Suggested Sublime Color Schemes

* (Ghostbusters)[https://github.com/gnat/sublime-ghostbusters]
* Mariana (Comes with Sublime)
* Monokai (Comes with Sublime)

### Special Thanks

* [Carson Gross](https://github.com/bigskysoftware), creator of hyperscript and HTMX.
* [Deniz Akşimşek (dz4k)](https://github.com/dz4k) for the original syntax highlighter for VS Code / VS Codium.
* [deathaxe](https://github.com/deathaxe) and [jfcherng](https://github.com/jfcherng) for ensuring a smooth launch to Sublime Package Control.
* The hyperscript and HTMX community.

### References

* [Hyperscript](https://hyperscript.org/)
* [HTMX](https://htmx.org)
* https://marketplace.visualstudio.com/items?itemName=dz4k.vscode-hyperscript-org
* https://github.com/dz4k/vscode-hyperscript
