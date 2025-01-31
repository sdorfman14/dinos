    Dinos v.alpha
                    by Sam Dorfman <samdorfman0@gmail.com>

Dinos is a mesozoic animation in ASCII art based on asciiquarium.

Installation
------------

Dinos is a single perl script, so all you have to do is make sure
it's executable and put it somewhere convenient, like /usr/local/bin or
/usr/local/games.

  Ubuntu
  ------

  Out-of-the-box ubuntu doesn't satisfy the Requirements below, so
  here's how to get them:
  1) Get perl's curses package which is available from apt:
       sudo apt-get install libcurses-perl
  2) Run
       cpan
     at the shell.  Agree to the defaults for everything.
     To leave cpan, type 
       quit
  3) Type
    sudo cpan Term::Animation

Requirements
------------

You must have the Term::Animation module, which you can get from
http://www.cpan.org. The Term::Animation module also requires the Curses
module, which you can also get from CPAN. This program will only run on
platforms that have a Curses library (so it won't work on Windows, but
you might get it to run under cygwin).

Usage
-----

While running:
	q	quit
	r	redraw (will recreate all entities)
	p	toggle pause
  a asteroid (not working yet)

Contributors
------------

All original code from Kirk Baucom (asciiquarium)
