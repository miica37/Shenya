###############################
Blender
###############################

Blender is used for creation of the hairs (using the addon `Hair Tool for Blender <https://gumroad.com/l/hairtool>`_). Hairs in Blender scene are in the form of curves and can be manipulated (twist, adjust width, etc) easily with the curve tool operations in Blender. The hairs is later exported into Maya to be further modified before reaching the final state.

In Shenya Version 2, a few Blender scenes used in rendering the images shown in Artstation and Rabbit Heart website are added.

Please be aware that Megascans assets is used to create the environments but Megascans assets are not allowed to be distributed so in the Blender scene you will find decimated geometry with pink textures. To restore the scene you will need to download the Megascans assets and reimport them to the Blender scene.

.. admonition:: File List in Blender Folder
   :class: refbox

   * Shenya Hairs.blend
   * Shenya Poses.blend
   * Shenya Pose - Sketchfab.blend
   * Shenya Pose - Sitting on Stairs.blend
   * [textures]
      ... textures used in lighting (from Pro Lighting Studio) ...

|

********************************************************
 🗋 Hair Texture Bake.blend
********************************************************

This Blender scene is used to bake out all the various texture for hairs (diffuse, opacity, normal, height, ao, etc). The functionality is provided by `Hair Tool for Blender <https://gumroad.com/l/hairtool>`_.

.. image:: /images/Blender-Hair-Texture-Bake-viewport.jpg
	:align: center

|

********************************************************
 🗋 Shenya Hairs.blend
********************************************************

Hairs for Shenya, created in Blender 2.93.3

`Hair Tool for Blender <https://gumroad.com/l/hairtool>`_ is used for creating the hair (not required to be installed to open the file).

.. image:: /images/Blender-Shenya-Hairs-viewport.jpg
	:align: center

.. note::
   Please be aware that hairs from Blender is not the exact same as the one in Final Maya file. The hairs in Final Maya File has some modifications: reduce edge loops for polycount opimizations, uv adjustment after reducing edge loops and also some shape adjustment to fix some geometry intersections and refinement on the shape of the hair).

|

********************************************************
 🗋 Shenya Poses.blend
********************************************************

Cycles test render using Blender addon `Pro Lighting Studio <https://blendermarket.com/products/pro-lighting-studio>`_

.. image:: /images/Blender-Shenya-Poses-viewport.jpg
	:align: center

|

********************************************************
 🗋 Shenya Pose - Sketchfab.blend
********************************************************

Eevee test render.

.. image:: /images/Blender-Shenya-Pose-Sketchfab-viewport.jpg
	:align: center

|

********************************************************
 🗋 Shenya Pose - Sitting on Stairs.blend
********************************************************

.. note::
   Paragraphs above explained about the pink textures

.. image:: /images/Blender-Shenya-Pose-Sitting-on-Stairs-viewport.jpg
	:align: center





