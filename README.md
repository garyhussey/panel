panel
=====

a simple flexible light-box style modal window written in jquery

EXAMPLE USE;

$('[target="panel"]').panel({'close':'<span>X</span>'});

SETTINGS;

	"close": the content to be displayed in the close button (default: <span>X</span>)

	"id": the element id for the panel parent container (default: Panel)

	"usemodal": will this panel instance will use a model (default: true)

	"modalclose": will the modal close the panel when clicked (default: true)

	"maxsize": the maximum ratio to screen size modal will alow (default: 0.9)