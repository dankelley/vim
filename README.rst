http://ontwik.com/tools/vim-from-novice-to-professional-by-derek-wyatt-p1/

Cool
====

``*`` finds next occurrence of word under cursor.

Plugins
=======

MRU - most recent file ('u' for ... what?)

Finding
=======

``*`` find next occurrence of word under cursor

marking
=======

``ma`` puts mark named ``a`` at cursor; ``a-z`` are available.  Later
on, can jump to this mark with ``'a``.

``v`` turn on character marking.

Format whole file
=================

``gg=G``
	
registers
=========

``"ayy`` yank current line into register ``a``

copy a region
=============

1. go to start
2. ``mk``   to put a mark there, called ``k``
3. go to end of desired region
4. ``y'k``   to yank from the mark (named ``k``) to the present spot
   you can then copy it somewhere with ``p``

delete a region
===============

1. go to start
2. ``mk``   to put a mark there, called ``k``
3. go to end of desired region
4. ``d'k``

Links
=====
1. http://tottinge.blogsome.com/use-vim-like-a-pro

