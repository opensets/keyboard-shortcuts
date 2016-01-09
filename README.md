# Encyclopedia of Keyboard Shortcuts

## Structure

Each file is a set of definitions.

## application

A string naming the application described by the document.

## shortcuts

- keys: An array of strings (or an array of arrays of strings) describing the keys.
- mode (optional): the mode this shortcut applies in, for modal applications.
- action: The action taken by this keyboard shortcut.
- wikidata: A wikidata identifier for the action. Should **not** be a Wikidata
  identifier for the *keyboard shortcut*, unless the action is traditionally
  described only by its key sequence (ie Ctrl+Alt+Del is OK, Ctrl+X instead of Cut
  is not).

## keyboard

String naming the type of keyboard layout the keys are defined around, if different
from the standard ISO 9995 set of keys.
