# AlignCursors

A [Sublime Text](http://www.sublimetext.com) plug-in to align multiple cursors at one column. Useful when making tables in markdown-files.


### Demo

![Demo](https://github.com/shagabutdinov/sublime-enhanced-demos/raw/master/align_cursors.gif "Demo")


### Features

Align cursors example:

```
# before
| Open project folder | f10 [cursor]| OpenPath: Open project folder |
| Open file folder    | ctrl+f10 [cursor]| OpenPath: Open file folder    |

# after
| Open project folder | f10      [cursor]| OpenPath: Open project folder |
| Open file folder    | ctrl+f10 [cursor]| OpenPath: Open file folder    |
```


### Usage

Add several cursors to view. Hit keyboard shortcut to align cursors.


### Commands

| Description   | Keyboard shortcuts | Command palette     |
|---------------|--------------------|---------------------|
| Align cursors | ctrl+u, ctrl+q     | AlignCursors: Align |


### Notes

This fork of https://github.com/shagabutdinov/sublime-align-cursors reduces the package to the least required stuff.
