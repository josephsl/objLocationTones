# Object Location Tones

* Author: Joseph Lee
* Maintainer: Dalen
* Download [stable version][1]
* NVDA compatibility: 2023.1 and later

After installing this add-on and restarting NVDA (or when you enable this add-on), as you navigate to different controls, you'll hear tones to indicate where the object is located on screen. To turn object location tones off, press Ctrl+NumpadDelete. To enable it once more, use the same gesture again.

Features:

* Report the currently focused object's location using a positional tone during the navigation. If in a text editable input field, the caret location will be reported instead. Ability to perceive the caret location while navigating, means you can get a sense of how document is scrolled, both horizontally and vertically, how long your lines are, it can help you with managing indentations and a number of other useful things. Ability to hear the location of an object during navigation means that you can get the sense of application's or website's layout, scroll faster through long menus or lists of files, and understand better how your OS looks like and acts in general.
* Turn the automatic positional tones on or off using Ctrl+NumpadDelete gesture. This feature allows you to use positional tones during navigation only when you need them.
* Explicitly report the currently focused object's location via positional tone by pressing the NumpadDelete key. If in a text editable input field, location of the caret will be reported instead. This is especially useful when tones during navigation are turned off, or you wish to hear the location of the focused object again, without navigating away and returning to it first.
* Explicitly report the mouse cursor location via positional tone using Windows+NumpadDelete gesture.
* Report currently focused object's outline using positional tones by pressing Ctrl+Shift+NumpadDelete. This feature enables you to acquire a sense of both location and size of the a GUI control.
* Report outline of a parent of the currently focused object using positional tones by pressing Ctrl+Alt+Shift+NumpadDelete. If triggered multiple times, it goes further down the ancestory list. This feature allows you to acquire a sense of location and size of the object's ancestors, thus, in conjunction with the regular layout feature, to ascertain locational and sizing relations between the GUI control and its ancestors. These two features are especially useful in GUI development.

* Turn continuous mouse cursor location position in relation to the currently focused object reporting using Shift+NumpadDelete. This feature plays one tone for mouse cursor and another for currently focused object, or a system caret within text editable controls, until turned off by the same gesture, or mouse stopped moving for a time. It lets you navigate your mouse toward the focused object or a letter on a screen. It is most useful in applications or websites that will not let you activate the ocontrol or a context menu in no other way but by using the mouse. It, also, allows you to use the mouse, with some exercise, for text editing and text selection, which is otherwise pretty difficult to achieve non-visually.

Important notes:

* If a control is offscreen, tones will not be played.
* There are some inaccurate caret location reports possible in certain types of input fields, mostly in apps with no native GUI controls

[1]: https://addons.nvda-project.org/files/get.php?file=objLocTones
