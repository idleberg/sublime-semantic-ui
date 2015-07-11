# Semantic UI for Sublime Text

[![GitHub release](https://img.shields.io/github/release/idleberg/Semantic-UI-Sublime-Text.svg?style=flat-square)](https://github.com/idleberg/Semantic-UI-Sublime-Text/releases)
[![Travis](https://img.shields.io/travis/idleberg/Semantic-UI-Sublime-Text.svg?style=flat-square)](https://travis-ci.org/idleberg/Semantic-UI-Sublime-Text)

Sublime Text snippets for the [Semantic UI](http://semantic-ui.com/) framework.

*This package is work in progress*

## Installation

### Package Control

1. Make sure you already have [Package Control](http://wbond.net/sublime_packages/package_control/) installed
2. Choose *Install Package* from the Command Palette (`Ctrl+Shift+P` on Windows/Linux, `⇧⌘P` on OS X)
3. Select *Semantic UI* and press `Enter`

### GitHub

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/Semantic-UI-Sublime-Text.git`

### Manual installation

1. Download the files using the GitHub .zip download option
2. Unzip the files to your Sublime Text `Packages` directory

## Usage

### Completions
All command completions are prefixed with `ui`, typing dash-connected class names should trigger the element of choice.

Examples:

* `ui-image` completes to an image tag
* `ui-form` will complete to form tags
* `ui-blue-label` completes to a blue label

### Snippets
There are some extra snippets for elements with children. For instance, you can use `ui-4-button` for a button group with four buttons inside.

### Icons

To add icon support, please install [Icon Fonts](https://packagecontrol.io/packages/Icon%20Fonts) via Package Control.

## Troubleshooting

By default, command completion should be enabled in all versions of Sublime Text. If the completion pop-up doesn't work, you can use `Ctrl+Space` to force it to show up. Alternatively, you might also have to add the HTML scope (`text.html`) to your user settings under `auto_complete_selector`.

## License

The MIT License (MIT)

Copyright (c) 2014 Jan T. Sott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/Semantic-UI-Sublime-Text) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
