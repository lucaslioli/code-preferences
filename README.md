# sublime-packages
A repository to keep synchronized my sublime packages and preferences.

### Utilities for Sublime Text
A gist with many useful plugins, preferences and shortcuts: [https://goo.gl/8xhrDL](https://goo.gl/8xhrDL)

### Why you should use Sublime Text?
An article (pt) wrote by me for PET-SI website: [https://goo.gl/jsHJ3y](https://goo.gl/jsHJ3y)

### Packages Installed
* "Additional PHP Snippets",
* "All Autocomplete",
* "AutoFileName",
* "Bootstrap 3 Autocomplete",
* "Bootstrap 3 Snippets",
* "Clickable URLs",
* "Color Highlighter",
* "DocBlockr",
* "EditorConfig",
* "Emmet",
* "GotoDocumentation",
* "Horizontal Scroll",
* "HTML-CSS-JS Prettify",
* "Indent XML",
* "Insert Callback",
* "Material Color Scheme",
* "Material Theme",
* "Package Control",
* "PhpDoc",
* "SideBarEnhancements",
* "SQLTools",
* "SublimeCodeIntel",
* "SublimeLinter",
* "SublimeLinter-php"
   
### Key Bindings setted

```
{ "keys": ["ctrl+tab"], "command": "next_view" },
{ "keys": ["ctrl+shift+tab"], "command": "prev_view" },

{ "keys": ["ctrl+pagedown"], "command": "next_view_in_stack" },
{ "keys": ["ctrl+pageup"], "command": "prev_view_in_stack" },

{ "keys": ["alt+w"], "command": "toggle_setting", "args": {"setting": "word_wrap"}},

{ "keys": ["ctrl+up"], "command": "upper_case" },
{ "keys": ["ctrl+down"], "command": "lower_case" },

{ "keys": ["ctrl+k", "ctrl+u"], "command": "scroll_lines", "args": {"amount": 1.0 } },
{ "keys": ["ctrl+k", "ctrl+l"], "command": "scroll_lines", "args": {"amount": -1.0 } },
```
To improve the plugin **Horizontal Scroll¹**
```
{ "keys": ["alt+x"], "command": "scroll_width", "args": {"amount": 30, "by_character": true} },
{ "keys": ["alt+z"], "command": "scroll_width", "args": {"amount": -30, "by_character": true} }
```
