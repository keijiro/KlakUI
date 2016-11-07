KlakUI
======

*KlakUI* is an extension of [Klak][Klak] that provides custom UI controls and node classes for receiving input from the UI.

![gif](http://66.media.tumblr.com/d094fed9d1ae7f7cf1d8de5e1ce4da74/tumblr_og62oqbDjZ1qio469o1_400.gif)

[Klak]: https://github.com/keijiro/Klak

Components
----------

There are three types of control -- **Knob**, **Button** and **Toggle**.

![gif](http://66.media.tumblr.com/79e789d00361cd5002d36dcc394aaaa7/tumblr_og2kkyoNgI1qio469o1_400.gif)

Also there are three types of receiver -- `UIKnobInput`, `UIButtonInput` and `UIToggleInput`.

![screenshot](http://i.imgur.com/iKjCquY.png)

To receive input from the UI controls, the `Target` property in the controls should be specified. After specifying the target, it starts sending input events on the UI control to the specified node.

![screenshot](http://i.imgur.com/kv118vh.png)

License
-------

Copyright (C) 2016 Keijiro Takahashi

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
