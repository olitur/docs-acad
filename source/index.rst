.. include:: _templates/Includes.txt


###############################
  Documentation |acad| *BETA*
###############################

**Bienvenue!**

.. _about:

.. include:: ../README.rst
   :start-line: 22
   :end-line: 50




.. only:: builder_html

Nouvelles du site
==================

-  2017-03-02 :ref:`news-2017-03-02`
-  2017-01-12 :ref:`news-2017-01-12`

-  :ref:`Voir l'ensemble des nouvelles <news>`

.. -  :ref:`Voir l'ensemble des nouvelles <news>`

..   :doc:`docs/news`

..
   .. toctree::
      :hidden:
      :maxdepth: 1

      docs/news/index



Installation & configuration
==============================

Pour les pressés, voir la section ci-dessous contenant les diverses documentations, pour les autres qui doivent installer & configurer |acad|, c'est ici.

.. hlist::
   :columns: 2

   * :doc:`docs/refs/start/index`
   * :doc:`docs/refs/config/index`




Si l'on veut apprendre un logiciel utilisé par tous et très efficace en 2D, il faut se concentrer sur celui qui est une référence incontournable.


Sections
========

.. The image ratio is: width: 350px; height: 350/4 + (2x5) ~= 98px


.. only:: builder_html and (not singlehtml)

   .. container:: tocdescr

      .. container:: descr

         .. figure:: docs/images/img-tuts.png
            :width: 450
            :target: docs/tuts/index.html

         :doc:`docs/tuts/index`
            Des tutoriels courts, pas à pas, pour débuter.

      .. container:: descr

         .. figure:: docs/images/img-guides.png
            :width: 450
            :target: docs/guides/index.html

         :doc:`docs/guides/index`
            Des guides plus complets basés sur des cas de figure réels.

      .. container:: descr

         .. figure:: docs/images/img-refs.png
            :width: 450
            :target: docs/refs/index.html

         :doc:`docs/refs/index`
            Une tentative d'établir des références sur |acad| ...

      .. .. container:: descr
      ..
      ..    :doc:`Glossaire <docs/refs/autocad-gloss>`
      ..       A list of terms and definitions used in Blender and this manual.



.. only:: latex or epub or singlehtml


   .. toctree::
      :hidden:
      :maxdepth: 2
      :caption: Tutoriels courts

      docs/tuts/index


   .. toctree::
      :hidden:
      :maxdepth: 2
      :caption: Guides complets

      docs/guides/index


   .. toctree::
      :hidden:
      :maxdepth: 2
      :caption: Références

      docs/refs/index

..      docs/refs/start/index
      docs/refs/config/index
      docs/refs/autocad-refs
      docs/refs/autocad-faq
      docs/refs/autocad-gloss


A faire
------------


   - :strike:`faire le lit, la vaisselle et ranger la maison!`
   - :strike:`prendre du lait` et du café



.. todolist::
