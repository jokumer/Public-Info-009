.. Tip - just do it:
      don't use TABs (= \t, tabulators)
      replace each TAB by *three blanks* (enable RegExp for Search and Replace in your IDE)
      set TAB width and indentation to THREE in your IDE
      set 'Use blanks instead of TABs' in your IDE


.. With the following include we import some definition. We do this in each and every file.
   so we can change the definition at a single place. Use the relative path to the Includes.txt file,
   which may look as well like ../../../Includes.txt for a deeply nested source file.

.. include:: Includes.txt


.. Usually we define 'php' as default highlight language in Includes.txt.
   With the following 'highlight' directive we switch to reStructuredText as default highlight language.

.. highlight:: rst


.. The following, first section (= headline) is the 'Document Title'.


======================
TYPO3 at StackOverflow
======================


.. The following is 'field list' which is rendered as a horizontal table.
   Think of it as key-value pairs.


:Writing here:    Bernd Wilke
:Rendered:        |today|
:Buildinfo:       `buildinfo <_buildinfo>`_
:Others:          `overview <..>`__


.. attention::

   We are asking the TYPO3 community to help and contribute!
   
**How you can help:**

-  add to this manual
-  ...


.. toctree::
   :hidden:

   StackOverflow/Index
   Notizen/Index
   Hyperlinks/Index
   reStructuredText/Index

