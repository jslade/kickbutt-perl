# kickbutt-perl
Old version of kickbutt utility panel implemented in perl

The idea
========

Kickbutt is a little utility panel containing configurable buttons. Each button kicks off a command - ergo "kick-butt". I use it to run frequently used commands during development, and it executes the commands in the environment of the shell from which it was launched.

For example, I might have a panel configured with thse commands:
    make
    make test

I have the kickbutt panel located near the terminal it was launched from, so it's convenient to click the button as I'm transitioning from my editor (emacs) to the terminal -- it's kind of like a poor-man's IDE in that case, where a full-blown IDE like eclipse has run, run  debug, run unit tests, and other similar actions built in. I just don't like such bloated IDE's.


History
=======

This script was originally written around 2006 or so. This latest version from 2009 is the end of my development of the perl-based version. New development will be done at [jslade/kickbutt](http://github.com/jslade/kickbutt)

