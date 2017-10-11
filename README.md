# Emacs Lispeed

A set of programs and Emacs packages that share same goal - making Emacs Lisp more efficient.
```
Lispeed = Lisp + Speed
```

----

### Meta repository

This repository is not intended for active development.  
What you can find here:

* Project overview, as a whole.
* High-level documentation.
* Bundle of sources via submodules[1].
* Utility scripts and other niceties.

[1] You may want to clone all
included repositories by yourself, from their upstreams.

###  Getting the sources

This repository uses submodules. Use instructions below to fetch submodules.

```bash
# (1) With '--recursive' option:
git clone --recursive https://github.com/Quasilyte/emacs-lispeed/

# (2) Without '--recursive' option:
git clone https://github.com/Quasilyte/emacs-lispeed/
cd emacs-lispeed
git submodule update --init --recursive
``` 
