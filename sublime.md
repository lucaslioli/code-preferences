## Utilities for Sublime Text
A gist with many useful plugins, preferences and shortcuts: [https://goo.gl/8xhrDL](https://goo.gl/8xhrDL)

## Why you should use Sublime Text?
An article (pt) wrote by me for PET-SI website: [https://goo.gl/jsHJ3y](https://goo.gl/jsHJ3y)

## Packages Installed
* A File Icon
* Additional PHP Snippets
* AlignTab
* All Autocomplete
* AutoFileName
* BracketHighlighter
* CSS3
* DocBlockr
* Emmet
* Git
* GitGutter¹
* GitHub Build Status
* GotoDocumentation
* Horizontal Scroll²
* Indent XML
* jQuery
* Material Color Scheme
* Material Theme
* Package Control
* PhpDoc
* SideBarEnhancements
* SQLTools
* SublimeCodeIntel
* SublimeLinter
* SublimeLinter-php
* Sublimerge 3

## Key Bindings setted

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

{ "keys": ["shift+delete"], "command": "run_macro_file", "args": {
     "file": "res://Packages/Default/Delete Line.sublime-macro"} },

{ "keys": ["alt+shift+,"], "command": "fold" },
{ "keys": ["alt+shift+."], "command": "unfold" },
{ "keys": ["alt+1", "alt+1"], "command": "fold_by_level", "args": {"level": 1} },
{ "keys": ["alt+2", "alt+2"], "command": "fold_by_level", "args": {"level": 2} },
{ "keys": ["alt+3", "alt+3"], "command": "fold_by_level", "args": {"level": 3} },
{ "keys": ["alt+4", "alt+4"], "command": "fold_by_level", "args": {"level": 4} },
{ "keys": ["alt+5", "alt+5"], "command": "fold_by_level", "args": {"level": 5} },
{ "keys": ["alt+6", "alt+6"], "command": "fold_by_level", "args": {"level": 6} },
{ "keys": ["alt+7", "alt+7"], "command": "fold_by_level", "args": {"level": 7} },
{ "keys": ["alt+8", "alt+8"], "command": "fold_by_level", "args": {"level": 8} },
{ "keys": ["alt+9", "alt+9"], "command": "fold_by_level", "args": {"level": 9} },
{ "keys": ["alt+0", "alt+0"], "command": "unfold_all" },
{ "keys": ["alt+d", "alt+d"], "command": "unfold_all" },
{ "keys": ["alt+t", "alt+t"], "command": "fold_tag_attributes" },
```
**GitGutter** Settings**²**
```
{
  "show_line_annotation": "false"
}
```
To improve the plugin **Horizontal Scroll¹**
```
{ "keys": ["alt+x"], "command": "scroll_width", "args": {"amount": 30, "by_character": true} },
{ "keys": ["alt+z"], "command": "scroll_width", "args": {"amount": -30, "by_character": true} }
```
