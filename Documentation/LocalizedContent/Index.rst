.. include:: ../Includes.txt


Localized content
-----------------

The topic of localizing the actual content of pages is where different
paradigms and preferences may step in. One clear difference is whether
you want to localize or translate a page.

- If you wish you translate a page 1:1you might like to using "content
  binding" which secures exactly that. The page's content is then always
  defined by the default language records and any translation is solely
  depending on whether a localized record for the default language
  record exists. This is the least flexible method but leaves less room for errors.

- If you wish to localize a page you can build up a separate set of
  content elements for the page in their own order. You can still
  maintain references between original and translation if you wish. Most
  flexible, but could be too much freedom.

Now you will learn about the differences of these approaches in the
context of the classic Page module.


.. toctree::
   :maxdepth: 5
   :titlesonly:
   :glob:

   ContentBinding/Index

