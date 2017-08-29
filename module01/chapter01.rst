Arithmetic
----------

This chapter demonstrates definition of a multiple choice questionnaire
inside chapter content. The syntax is poorly documented but it includes
answer options, points to grade, and feedback hints.

.. admonition:: File format
  :class: alert alert-info

  Everything is defined in
  `RST syntax <http://docutils.sourceforge.net/docs/user/rst/quickref.html>`_.

The interactive part is up next.

.. questionnaire:: keyword 7

  Some arithmetic multiple choice questions:

  .. pick-one:: 2

    1 + 1 = ?

    a. 1
    *b. 2
    c. 3

    a § Maybe more?
    c § Maybe less?

  .. pick-any:: 2

    2 * x = y

    *a. x = 3, y = 6
    b. x = 4, y = 7
    *c. x = 5, y = 10

    b § Check your arithmetic.

  .. freetext:: 3 int

    3 * 5 = ?

    15
    16 § One too much!


The end
.......

.. image:: /images/apluslogo.png

Above there is an example image.

Final words and end of chapter.
