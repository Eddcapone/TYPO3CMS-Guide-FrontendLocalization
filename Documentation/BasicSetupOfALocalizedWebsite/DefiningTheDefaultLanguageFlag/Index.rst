.. include:: ../../Includes.txt
.. include:: Images.txt


Defining the "default" language flag
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If you want to specify the name of the default language and a flag
icon you can do so for a branch of the page tree by setting this Page
TSconfig for the root page of your website:

TSconfig:

.. code-block:: typoscript

      mod.SHARED {
        defaultLanguageFlag = gb
        defaultLanguageLabel = English
      }


|img-6|

This setting is for example used by the Web>Page module and the Web>List
module.

