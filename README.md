emacs-no-easy-keys
==================

http://danamlund.dk/emacs/no-easy-keys.html

An Emacs mode to help you learn the proper Emacs movement keys

This mode teaches you to use the proper Emacs movement keys in a
rather harsh manner.

No-easy-keys disables arrow, end, home and delete keys, as well as
their control and meta prefixes. When using any of these keys, you
instead get a message informing you of the proper Emacs shortcut
you should use instead (e.g. pressing down informs you to use C-n).

The easy keys are not disabled in the minibuffer. The minibuffer
has different proper keys replacements than regular buffers and
depending on various extensions such as icicles, ido, etc.

To install, save no-easy-keys.el in your load path and add the
following to your .emacs file:

(require 'no-easy-keys)
(no-easy-keys 1)

You can toggle no-easy-keys using 'M-x no-easy-keys'.
