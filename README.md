# Semantic UI for Sublime Text

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![Package Control](https://packagecontrol.herokuapp.com/downloads/Semantic%20UI.svg?style=flat-square)](https://packagecontrol.io/packages/Semantic%20UI)
[![GitHub release](https://img.shields.io/github/release/idleberg/sublime-semantic-ui.svg?style=flat-square)](https://github.com/idleberg/sublime-semantic-ui/releases)
[![Travis](https://img.shields.io/travis/idleberg/sublime-semantic-ui.svg?style=flat-square)](https://travis-ci.org/idleberg/sublime-semantic-ui)

Sublime Text snippets for the [Semantic UI](http://semantic-ui.com/) framework.

*This package is work in progress*

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose *“Install Package”* from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type *“Semantic UI”* and press <kbd>Enter</kbd>

### Using Git

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/sublime-semantic-ui.git 'Semantic UI'`

### Manual installation

1. Download the latest [stable release](https://github.com/idleberg/sublime-semantic-ui/releases)
2. Unzip the archive to your Sublime Text `Packages` directory

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

This work is licensed under the [The MIT License](LICENSE).

## Donate

You are welcome support this project using [Flattr](https://flattr.com/submit/auto?user_id=idleberg&url=https://github.com/idleberg/sublime-semantic-ui) or Bitcoin `17CXJuPsmhuTzFV2k4RKYwpEHVjskJktRd`
