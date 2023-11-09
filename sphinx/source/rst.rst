=================
Restructured Text
=================

Nagłówki
========

Przykład:

.. code-block :: rst

   ===============
   Główny Nagłówek
   ===============

   Nagłówek
   ========

   Nagłówek 2
   ----------

   Nagłówek 3
   ~~~~~~~~~~

Użycie:

===============
Główny Nagłówek
===============

Nagłówek
========

Nagłówek 2
----------

Nagłówek 3
~~~~~~~~~~

Notatki i Uwagi
===============

Przykład:

.. code-block :: rst

   .. warning::
      This is warning text. Use a warning for information the user must
      understand to avoid negative consequences.

   .. note::
      This is note text. Use a note for information you want the user to
      pay particular attention to.

.. warning::
   This is warning text. Use a warning for information the user must
   understand to avoid negative consequences.

.. note::
  This is note text. Use a note for information you want the user to
  pay particular attention to.

Linki
=====

.. code-block :: rst

   `Link to Write the Docs <https://www.writethedocs.org/>`_

`Link to Write the Docs <https://www.writethedocs.org/>`_

Tabele
======

.. code-block :: rst

   +------------------------+-----------------+
   | Header 1               | Header 2        |
   +========================+=================+
   | row 1, column 1        | row 1, column 2 |
   +------------------------+-----------------+
   | row 2, column 1        | row 2, column 2 |
   +------------------------+-----------------+

+------------------------+-----------------+
| Header 1               | Header 2        |
+========================+=================+
| row 1, column 1        | row 1, column 2 |
+------------------------+-----------------+
| row 2, column 1        | row 2, column 2 |
+------------------------+-----------------+