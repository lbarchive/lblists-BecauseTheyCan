=================
Because They Can!
=================

*Why?*

Open source projects make you ask that question, or gasp

* *Wait, what?*,
* *OMG!*,
* *That's insane!*,
* etc.

They can be awesome or terribly horrendous ideas to do whatever they are trying
to do.

This list is published under the CC0_.

.. _CC0: LICENSE


.. contents:: **The List**
   :local:
   :backlinks: top


Python
======

* `quasiquotes <https://github.com/llllllllll/quasiquotes>`_:
  "I'd just like to interject for a moment..."
  by Joe Jevnik under the GPLv2

  .. code:: pycon

    >>> from quasiquotes.c import c
    >>> def f(a):
    ...     with $c:
    ...         printf("%ld\n", PyLong_AsLong(a));
    ...         a = Py_None;
    ...         Py_INCREF(a);
    ...     return a
    ...
    >>> f(0), f(1)
    (0, 1)

You can ``goto`` hell
---------------------

* `goto for Python <http://entrian.com/goto/>`_
  by Richie Hindle under the Python Software Foundation license
  [Python 2.3+] {Linux, Windows}

* `python-goto <https://github.com/snoack/python-goto>`_
  by Sebastian Noack under Unlicense
  [Python 2.6–3.6, PyPy]

  .. code:: python

    from goto import with_goto

    @with_goto
    def foobar(start, stop):

        # do something
        if is_borked():
            goto .cleanup

        # do something else

        label .cleanup
        # cleaning up


Shell
=====

Vim
---

* `Athame <https://github.com/ardagnir/athame>`_:
  true Vim for shells
  by James Kolb under GPLv3
  (`GIF <https://i.imgur.com/74EoF4X.gif>`__)
  [C]
  {Linux, macOS, Windows (WSL), readline {Bash, GDB, Python, ...}, Zsh}


Terminal Games
==============

In *Awk*
--------

Awk-My-God!

* `awkaster <https://github.com/TheMozg/awk-raycaster>`_:
  pseudo 3D shooter game using raycasting
  by Fedor Kalugin under MIT
  (`YouTube <https://youtu.be/klB1WVZ87Kw>`__)

  .. figure:: https://github.com/TheMozg/awk-raycaster/blob/master/screenshot.png?raw=true


In *sed*
--------

Yes, some cra-sed people write games in sed.

* `Gravity Defied <https://github.com/Firemoon777/gravity-defied>`_ clone
  by Vladimir Turov under MIT
  (`YouTube <https://youtu.be/Jh3gvpa-1zY>`__,
  `asciinema <https://asciinema.org/a/ddfusaite83m32k8vblg10iil>`__)

* `sfb <https://github.com/ValeriyKr/sfb>`_: *Flappy Bird* clone
  by Valeriy Kireev under MIT
  (`YouTube <https://youtu.be/G3k7rplCl4o>`__)

* `sed-snake <https://github.com/jinchizhong/sed-snake>`_
  by Chizhong Jin under BSD
  (`YouTube <https://youtu.be/WK3N38m-5Vw>`__)

* `Sedtris <https://github.com/uuner/sedtris>`_
  by Julia Jomantaite and Aurelio Marinho Jargas under Poetic License
  (`YouTube <https://youtu.be/0TFdHRIiuqc>`__)

* `SedArkanoid <http://aurelio.net/projects/sedarkanoid/>`_
  by Aurelio Marinho Jargas under GPLv2
  (`YouTube <https://youtu.be/HmhJVqwK0CQ>`__)

* `SedSokoban <http://aurelio.net/projects/sedsokoban/>`_
  by Aurelio Marinho Jargas under GPLv2
  (`YouTube <https://youtu.be/bg3x43E-yjo>`__)


Uncategorized
=============

* `bucklespring <https://github.com/zevv/bucklespring>`_: Nostalgia
  bucklespring IBM Model-M keyboard sound
  by Ico Doornekamp under GPLv2
  (`YouTube <https://youtu.be/21AuWT1lDMc>`__)
  [C, OpenAL]
  {Linux, macOS}

* `ratterplatter <https://github.com/vain/ratterplatter>`_: Don't you miss your
  hard disk?
  by Peter Hofmann under MIT
  (`YouTube <https://youtu.be/PSjHgNZTW3w>`__)
  [C, libao, opusfile, ``/proc/diskstats``]
  {Linux}
