# Emmet package

[Emmet](http://emmet.io) support for Atom.

### Features:

* Multiple cursors support
* Interactive actions (Interactive Expand Abbreviation, Wrap With Abbreviation, Update Tag) allows you to preview result real-time as you type
* Better tabstops in generated content
* User extensions support
* CSP-compatible core, no need to manually patch it with `loophole`.

### Installation

```bash
cd ~/.atom/packages
git clone https://github.com/emmetio/emmet-atom
cd emmet-atom
npm install
```

Please report any issues at https://github.com/emmetio/emmet-atom/issues

## Default Keybindings

You can change these by simply making up your own keybindings in _keymaps/emmet.cson_.

```cson
'meta-E': 'emmet:expand-abbreviation'
'ctrl-d': 'emmet:match-pair-outward'
'alt-d': 'emmet:match-pair-inward'
'ctrl-alt-j': 'emmet:matching-pair'
'ctrl-alt-right': 'emmet:next-edit-point'
'ctrl-alt-left': 'emmet:prev-edit-point'
# 'command+/': 'emmet:toggle_comment' already exists in Atom
'meta-J': 'emmet:split-join-tag'
'meta-K': 'emmet:remove-tag'
'meta-Y': 'emmet:evaluate-math-expression'
'ctrl-shift-up': 'emmet:increment-number-by-1'
'ctrl-shift-down': 'emmet:decrement-number-by-1'
'alt-shift-up': 'emmet:increment-number-by-01'
'alt-shift-down': 'emmet:decrement-number-by-01'
'ctrl-alt-up': 'emmet:increment-number-by-10'
'ctrl-alt-down': 'emmet:decrement-number-by-10'
'alt-meta-.': 'emmet:select-next-item'
'alt-meta-,': 'emmet:select-previous-item'
'meta-R': 'emmet:reflect-css-value'
'ctrl-D': 'emmet:encode-decode-data-url' # decoding doesn't work--we need dialogs
'ctrl-I': 'emmet:update-image-size'
#'ctrl+alt+enter': 'emmet:expand_as_you_type' doesn't work--we need dialogs
# 'shift+ctrl+g': 'emmet:wrap_as_you_type' doesn't work--we need dialogs
# 'Tab': 'emmet:expand_abbreviation_with_tab'
# 'shift+ctrl+a': 'emmet:wrap_with_abbreviation' doesn't work--we need dialogs
```
