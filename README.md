panel v 0.1
========================

A simple flexible light-box style modal window written in jquery.

EXAMPLE USE
------------------------
	$('[target="panel"]').panel({'close':'<span>X</span>'});

- - - - - - - - - - - - -

SETTINGS
------------------------
+ **close**: the content to be displayed in the close button _(default: <span>X</span>)_
+ **id**: the element id for the panel parent container _(default: Panel)_
+ **usemodal**: will this panel instance will use a model _(default: true)_
+ **modalclose**: will the modal close the panel when clicked _(default: true)_
+ **maxsize**: the maximum ratio to screen size modal will alow _(default: 0.9 AKA 90%)_

- - - - - - - - - - - - -

TO DO
------------------------
1. make the _maxsize_ calculate from margin values instead of a static ratio