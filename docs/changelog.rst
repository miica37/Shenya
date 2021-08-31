###############################
Changelog
###############################


|

********************************************************
 v2.0
********************************************************

2021-08-20

❒ File Organization
====================

* Textures moved from < \\Project\\Maya\\sourceimages > to < \\Project\\Textures >

.. rst-class:: tab

Maya's project configuration file "workspace.mel" has been moved to < \\Project\\ >, previously you would set Maya project at < \\Project\\Maya\\ > but now changed to setting the Maya project at < \\Project\\ >


❒ Rendered Images
==================

* Added 14 rendered images from Blender and Marmoset Toolbag. They are inside a new folder "Images".


❒ Rig
======

* Rebuilt mGear rig with new version 4.0.0

.. rst-class:: tab

Also adjusted the shapes of some of the controls


* Added skirt rig

.. image:: /images/changelog/v2/skirt-rig.jpg
   :align: center

* Added Facial Blendshapes (FACS based)

.. image:: /images/changelog/v2/facial-blendshapes.jpg
   :align: center

.. rst-class:: tab

List of blendshape targets (each splited to left side and right side): look_left, look_right, look_up, look_down, look_up_altcopy, eye_close, upper_lid_raiser, lid_tightener, brow_raiser, brow_lower, brow_inner_raise, brow_outer_raise, cheek_raiser, nose_wrinkler, nostril_dilator, nostril_compressor, smile, corner_puller, corner_depressor, upper_lip_raiser, lower_lip_depressor, chin_raiser, chin_depressor, dimpler, pucker, pucker, funneler, lip_pressor, lip_suck, lip_stretch, cheek_puff, lips_puff, lips_seal, mouth_narrow, mouth_push, mouth_slide


* Added Corrective shape when knee bend

* Added Corrective shape to tops when shoulder down


❒ Model
========

* Subtle changes to facial features (very subtle on the cheeks and eyelids looking upwards more), also lowered the hairline slightly

.. image:: /images/changelog/v2/facial-subtle-change.gif
   :align: center

* Fixed Jaw and added more thickness to corner lips (area in the mouth)

.. image:: /images/changelog/v2/fix-jaw.jpg
   :align: center

* Updated body's shape and topolgy

.. image:: /images/changelog/v2/topology-change-head.gif

.. image:: /images/changelog/v2/topology-change-breast.gif

.. image:: /images/changelog/v2/topology-change-back.gif

.. image:: /images/changelog/v2/body-shape-tweak-front.gif

.. image:: /images/changelog/v2/body-shape-tweak-elbow.gif

.. image:: /images/changelog/v2/body-shape-tweak-butt-cleavage.gif

.. image:: /images/changelog/v2/body-shape-tweak-foot.gif

.. rst-class:: tab

Topology: Added some edge loops to the area between the brows, the breast and the back (for slightly more resolution to play with when doing brows expression, etc)

.. rst-class:: tab

Shape: Elbow is moved towards lower-arm (lower-arm is now shorter than upper-arm). Butt cleavage is moved lower (previously is too high and deep)

.. rst-class:: tab

Topology and shape is also updated in Zbrush, the normal map is rebaked (though it wasn't very noticable)

* Update underwear shape

.. image:: /images/changelog/v2/underwear-change.jpg

* Update Hairs

.. rst-class:: tab 

 - lower polycount (V1: 17928 Tris, V2: 13680 Tris)
 
.. rst-class:: tab

 - filled some inner areas
 
.. rst-class:: tab

 - adjusted shape around the hairline


❒ Blender
==========

* Added 3 Blender scenes with lighting (Note: model is not rigged but brought in as fbx (mesh without skeleton) from Maya)

* Updated Blender hairs (Blender\Shenya Hairs.blend)


❒ Others
=========

* Megascans assets are used as props in some of the rendered images. They are not allowed to be distributed so I replace the geometry in scenes with a heavily reduced mesh. Megascans Textures also not included.

|

********************************************************
 v1.0
********************************************************

2021-03-31

First Release
