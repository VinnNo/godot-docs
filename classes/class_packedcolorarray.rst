:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PackedColorArray.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PackedColorArray:

PackedColorArray
================

A packed :ref:`Array<class_Array>` of :ref:`Color<class_Color>`\ s.

Description
-----------

An :ref:`Array<class_Array>` specifically designed to hold :ref:`Color<class_Color>`. Packs data tightly, so it saves memory for large array sizes.

**Note:** This type is passed by value and not by reference.

Methods
-------

+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`PackedColorArray<class_PackedColorArray>` | :ref:`PackedColorArray<class_PackedColorArray_method_PackedColorArray>` **(** :ref:`Array<class_Array>` from **)**                |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`append<class_PackedColorArray_method_append>` **(** :ref:`Color<class_Color>` color **)**                                   |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`append_array<class_PackedColorArray_method_append_array>` **(** :ref:`PackedColorArray<class_PackedColorArray>` array **)** |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                         | :ref:`empty<class_PackedColorArray_method_empty>` **(** **)**                                                                     |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`insert<class_PackedColorArray_method_insert>` **(** :ref:`int<class_int>` idx, :ref:`Color<class_Color>` color **)**        |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`invert<class_PackedColorArray_method_invert>` **(** **)**                                                                   |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`push_back<class_PackedColorArray_method_push_back>` **(** :ref:`Color<class_Color>` color **)**                             |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`remove<class_PackedColorArray_method_remove>` **(** :ref:`int<class_int>` idx **)**                                         |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`resize<class_PackedColorArray_method_resize>` **(** :ref:`int<class_int>` idx **)**                                         |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| void                                            | :ref:`set<class_PackedColorArray_method_set>` **(** :ref:`int<class_int>` idx, :ref:`Color<class_Color>` color **)**              |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                           | :ref:`size<class_PackedColorArray_method_size>` **(** **)**                                                                       |
+-------------------------------------------------+-----------------------------------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_PackedColorArray_method_PackedColorArray:

- :ref:`PackedColorArray<class_PackedColorArray>` **PackedColorArray** **(** :ref:`Array<class_Array>` from **)**

Constructs a new ``PackedColorArray``. Optionally, you can pass in a generic :ref:`Array<class_Array>` that will be converted.

----

.. _class_PackedColorArray_method_append:

- void **append** **(** :ref:`Color<class_Color>` color **)**

Appends an element at the end of the array (alias of :ref:`push_back<class_PackedColorArray_method_push_back>`).

----

.. _class_PackedColorArray_method_append_array:

- void **append_array** **(** :ref:`PackedColorArray<class_PackedColorArray>` array **)**

Appends a ``PackedColorArray`` at the end of this array.

----

.. _class_PackedColorArray_method_empty:

- :ref:`bool<class_bool>` **empty** **(** **)**

Returns ``true`` if the array is empty.

----

.. _class_PackedColorArray_method_insert:

- :ref:`int<class_int>` **insert** **(** :ref:`int<class_int>` idx, :ref:`Color<class_Color>` color **)**

Inserts a new element at a given position in the array. The position must be valid, or at the end of the array (``idx == size()``).

----

.. _class_PackedColorArray_method_invert:

- void **invert** **(** **)**

Reverses the order of the elements in the array.

----

.. _class_PackedColorArray_method_push_back:

- void **push_back** **(** :ref:`Color<class_Color>` color **)**

Appends a value to the array.

----

.. _class_PackedColorArray_method_remove:

- void **remove** **(** :ref:`int<class_int>` idx **)**

Removes an element from the array by index.

----

.. _class_PackedColorArray_method_resize:

- void **resize** **(** :ref:`int<class_int>` idx **)**

Sets the size of the array. If the array is grown, reserves elements at the end of the array. If the array is shrunk, truncates the array to the new size.

----

.. _class_PackedColorArray_method_set:

- void **set** **(** :ref:`int<class_int>` idx, :ref:`Color<class_Color>` color **)**

Changes the :ref:`Color<class_Color>` at the given index.

----

.. _class_PackedColorArray_method_size:

- :ref:`int<class_int>` **size** **(** **)**

Returns the size of the array.

