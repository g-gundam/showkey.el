# showkey.el

a copy of showkey.el that's installable via use-package

## About

This is a copy of [showkey](https://www.emacswiki.org/emacs/ShowKey) by Drew Adams.
I put it in its own git repo so that it could be installed via use-package.

This minor mode provides a nice way to show what keys your pressing and what functions
they're calling.  It's useful for demonstration purposes.

## Installation

```elisp
(use-package showkey
  :vc (:url "https://github.com/g-gundam/showkey.el" :branch "main"))
```

This should work in Emacs 30+.

- https://tony-zorman.com/posts/use-package-vc.html

