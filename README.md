# emacs-skel

Default emacs config for new users.

## What?

This  is a  configuration  file  for the  emacs  editor with  sensible
defaults. While there are already  a couple of such configs available,
this one tries to customize some more aspects of emacs while keeping
things simple.

It  doesn't require  any additional  stuff to  be installed,  no emacs
modules or libraries etc. Also it  only consists of one file. Well, in
fact,  there are  two files,  one contains  german and  the other  one
english comments inside.

## Screenshot

![demo](http://www.daemon.de/idisk/Misc/emacs-skel.png)

## Install

Copy  the file  `dot-emacs-de`  or `dot-emacs-en`  into the  directory
`/etc/skel/.emacs`, so  that new users  on the system can  start using
emacs with sensible defaults.

You may  also copy the  file to  your `$HOME/.emacs` directory  if you
want to use it yourself.

## Testing

If you just want to test it without installing, issue:

    emacs -q -l dot-emacs-en
    
## Requirements

None (beside emacs, of course).

## Author

T.v.Dein <tlinden@cpan.org>

## License

Licensed under the terms of the GPL3.

