my emacs settings, it works only on the emacs 24 version.

 - copy this folder to ~/.emacs.d/
 - create file ~/.emacs, add the follow lines:
     (add-to-list 'load-path "~/.emacs.d/emacs.d")
     (require 'init)



