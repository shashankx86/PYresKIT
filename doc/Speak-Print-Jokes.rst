Jokes
+++++

Through ``get_joke`` function you can speak/print joke

Print Joke
==========

.. code-block:: python

   import pyreskit

   pyreskit.get_joke()

Speak Joke
==========

By adding ``speakjok=True`` it will print and speak joke

.. code-block:: python

   import pyreskit

   pyreskit.get_joke(speakjok=True)

..

   Note: Currently speak joke only support English(en) language


Joke language
=============

**Language available**



(1) English (en)
(2) German (de)
(3) Spanish (es)
(4) Galician (gl)
(5) Basque (eu)
(6) Italian (it)

By adding ``language="<yourlangauge>"`` you can change language of joke 

.. code-block:: python

   import pyreskit

   pyreskit.get_joke(language="it")

Joke category
=============

**Category available**


* neutral in en, de, es, gl, eu, it
* chuck in en, it, de
* twister in de
* all in en, de, es, gl, eu, it

.. code-block:: python

   import pyreskit

   pyreskit.get_joke(language="en" ,category="chuck")
