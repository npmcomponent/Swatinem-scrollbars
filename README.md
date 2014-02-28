*This repository is a mirror of the [component](http://component.io) module [swatinem/scrollbars](http://github.com/swatinem/scrollbars). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/swatinem-scrollbars`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# scrollbars

An efficient overflow area with custom scrollbars

Heavily influenced by [Trackpad Scroll Emulator](https://github.com/jnicol/trackpad-scroll-emulator),
but with support for both directions, without the need to call update on size
changes or to wrap the elements in a container and without a nasty jQuery dependency.

You also can style the scrollbars yourself by overriding the `.scrollbars-handle`
style.

[![Build Status](https://travis-ci.org/Swatinem/scrollbars.png?branch=master)](https://travis-ci.org/Swatinem/scrollbars)
[![Coverage Status](https://coveralls.io/repos/Swatinem/scrollbars/badge.png?branch=master)](https://coveralls.io/r/Swatinem/scrollbars)

## Installation

    $ component install Swatinem/scrollbars

## Usage

```
var scrollbars = require('scrollbars');

var scroller = scrollbars(document.querySelector('#yourcontainer'));

// if you are done with it:
scroller.destroy();
```

## License

  LGPLv3

