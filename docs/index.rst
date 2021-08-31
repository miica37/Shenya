.. Shenya Documentation master file, created by
	 sphinx-quickstart on Sat Sep  1 12:46:37 2018 (modifiend on March 2021).
	 You can adapt this file completely to your liking, but it should at least
	 contain the root `toctree` directive.

Shenya Files Overview
=====================
Welcome to the Files Overview of character Shenya, she's a character model designed by `Rabbit Heart <https://rabbit-heart.my/>`_.

.. rst-class:: special
	For more images, please check out at this page `Shenya <https://rabbit-heart.my/portfolio/shenya/>`_

.. image:: /images/Shenya-cover.jpg
	:align: center

|

Characteritic
-------------
* Female
* Stylized
* Fantasy Clothing
* Age 20+
* Tall (183cm in Maya File)
* Pointy Ears

Distributions
-------------

`Gumroad <https://gumroad.com/l/shenya>`_ | `Artstation <https://www.artstation.com/marketplace/p/DVxND/shenya>`_ | `CGTrader <https://www.cgtrader.com/3d-models/character/woman/shenya>`_ | `Turbosquid <https://www.turbosquid.com/FullPreview/Index.cfm/ID/1713172>`_

.. toctree::
	:maxdepth: 2
	:caption: Contents:

	project-files-full-list.rst
	textures-and-uv.rst
	zbrush.rst
	maya.rst
	blender.rst
	marvelous-designer.rst
	substance-painter.rst
	marmoset-toolbag.rst
	mgear.rst
	mgear-customize-rig.rst
	changelog.rst

|

✦ Model Highlights ✦
=====================

Basic Maya Rig
--------------
	 * Rig created using `mGear Rigging Framework <http://www.mgear-framework.com/>`_
	 * Facial Expressions (FACS based) (no separate controller yet, it's all in one controller)

.. note::
	 * Requires mGear to be installed (free)

Full Body Base Mesh Included
----------------------------
	 
	 * Base Mesh for Maya and Zbrush
	 * Quad topology

.. note::
	 Body's uv is spreaded into 4 UDIMS.


PBR Textures
------------
Textures are created using Specular / Glossiness Workflow in Substance Painter. (Metalness / Roughness textures will be provided soon.)

|

Geometry Parts
==============
+---------------+-------+-------+----------------------------------------------+
| Model Parts   | Tris  | Polys | Remarks                                      |
+===============+=======+=======+==============================================+
| Body          | 30072 | 15076 | All Quads. 4 UDIMs (Head, Torso, Arms, Legs) |
+---------------+-------+-------+----------------------------------------------+
| Hairs         | 13680 | 6840  |                                              |
+---------------+-------+-------+----------------------------------------------+
| Tops          | 7589  | 3888  |                                              |
+---------------+-------+-------+----------------------------------------------+
| Bottoms       | 15072 | 7693  |                                              |
+---------------+-------+-------+----------------------------------------------+
| Shoes         | 7460  | 4512  |                                              |
+---------------+-------+-------+----------------------------------------------+
| Leggings      | 2450  | 1236  |                                              |
+---------------+-------+-------+----------------------------------------------+
| Accessories   | 5636  | 3068  | Forehead Ring, Hair Bracelets                |
+---------------+-------+-------+----------------------------------------------+
| Eyes          | 1280  | 680   |                                              |
+---------------+-------+-------+----------------------------------------------+
| Corneas       | 760   | 400   | (for reflection and eye shadows)             |
+---------------+-------+-------+----------------------------------------------+
| Teeths Tongue | 1226  | 1224  |                                              |
+---------------+-------+-------+----------------------------------------------+
| ---Total---   | 85225 | 44617 |                                              |
+---------------+-------+-------+----------------------------------------------+
|               |       |       |                                              |
+---------------+-------+-------+----------------------------------------------+
| Eyebrows      | 45720 | 22860 | (! Very High Poly)                           |
+---------------+-------+-------+----------------------------------------------+
| Eyelashes     | 43020 | 21510 | (! Very High Poly)                           |
+---------------+-------+-------+----------------------------------------------+
| Underwear     | 510   | 256   | (Placeholder)                                |
+---------------+-------+-------+----------------------------------------------+

|

Software Versions and File Formats
==================================

* Maya 2020.4 (.ma)
* Zbrush 2021.1 (.ztl)
* Marvelous Designer 10 (6.0.351) (.Zprj)
* Substance Painter 2020.2.2 (6.2.2) Build 661  (.spp)
* Blender 2.93.3 (.blend)
* Fbx (.fbx)
* Obj (.obj)
* Textures (.png)
* Marmoset Toolbag 4.02 (.tbscene)

|

Textures
=============

* PBR - Specular Glossiness (more about it :ref:`here<substance_painter_bookmark>`)
* Body texture consist of 4 UDIMs x (diffuse + glossiness + specular + normal) (total of 16 textures)
* About 10 texture set (more about textures :ref:`here<textures_bookmark>`)
* File format is PNG

Others:

* Eyes has diffuse, specular, normal and height
* Hairs has diffuse, normal, opacity, depth, flow and ao
* Teeths and Tongue are sharing one texture (and they are NOT part of they body texture).
* Lantern is also using PBR and exported as png
* There's a layer of mesh on top of eye and covering it, it's mesh is named Cornea but the texture is using "eyes-shadows.png". (Sorry about the naming inconsitency, will be fixed in future updates)

|

📧 Supports
=============
For any Issues / Requests / Inquiries / Suggestions, feel free to reach me at miicaneo@gmail.com or if you prefer to be anonymous, you can also leave a comment at https://rabbit-heart.my/contacts/

|

.. note::
	 Right click "Open Image in New Tab" to see the image in full resolution 😉

	.. image:: /images/open-image-in-new-tab.jpg
		:align: center

|

**About the video "Project Files Preview" on Youtube (old)** 

A promotion video has been created for the first release of Shenya and released on Youtube, however in Version 2 there are quite some changes made, to prevent confusion, the youtube video is now hidden from public (`It is accessible only by link <https://www.youtube.com/embed/JqUTn7AywF0>`_).

