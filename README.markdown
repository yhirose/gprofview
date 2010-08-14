gprofview - a gprof log viewer
==============================

This is a ncurses-based text-mode gprof log viewer.

Author: Yuji Hirose <yuji.hirose.bug at gmail.com>
License: GPLv2
Requirement: Ruby 1.8.x

Command line usage
------------------

    gprofview [gprof log file]


General operation
-----------------

    'c'    clear filter result
    'e'    filter entries (include)
    'i'    filter entries (exclude)
    'q'    quit
    'v'    change view type (percentage <-> time)
    's'    change sort type (total -> self -> count)
    't'    go back to flatlist view 
    'u'    go back one level
    '?'    you know what it is...
    SPACE  go to callgraph (ENTER key can also be used.)

Cursor movement
---------------

    'g'     go to top
    'G'     go to bottom
    'h'     scroll left
    'j'     move cursor down
    'k'     move cursor up
    'l'     scroll right
    'n'     find next
    'N'     find previous
    'zz'    go to center of screen
    '0'     go to left
    '/'     find
    CTRL-B  page up
    CTRL-D  half page down
    CTRL-E  scroll up
    CTRL-F  page down
    CTRL-U  half page up
    CTRL-Y  scroll down
