###############################
Maya
###############################

Character model is built with Maya 2020.

Character height in scene: 186cm

.. admonition:: File List in Maya Folder
   :class: refbox

   * Shenya Rig.ma
   * Shenya Rig (Cloth Setup).ma
   * Pose - Turntable.ma
   * Pose - Holding Lantern.ma
   * Pose - Sitting on Stairs.ma
   * Lantern.ma
   * anim-layer-breath.ma
   * cloth-setup.ma
   * lightings-A.ma
   * maya-env.txt
   * workspace.mel
   * [rig-build]
      ... files related to building mgear rig ...
   * [scripts]
      ... various helper scripts ...
   * [sourceimages]
      ... list of textures ...

.. note::
   Naming conventions for the files: lower case files are mostly used as import 
   
   ie.
   < anim-layer-breath.ma >, < cloth-setup.ma > and < lightings-A.ma > are files to be imported


********************************************************
 | Shenya Rig.ma
********************************************************

Main character model file with rig.

.. image:: /images/Maya-Shenya-Rig-viewport.jpg
	:align: center

.. image:: /images/Maya-Shenya-Rig-outliner.jpg
	:align: center

|

********************************************************
 | Shenya Rig (Cloth Setup).ma
********************************************************

Character model file with rig, plus ncloth setup for skirt.

Play the timeline (set Playback Speed to Real-time) to see skirt simulation.

This file is refereced by "Pose - Sitting on Stairs.ma", to simulate the skirt sitting on stairs.

.. image:: /images/Maya-Shenya-Rig-(Cloth-Setup)-viewport.jpg
	:align: center

.. image:: /images/Maya-Shenya-Rig-(Cloth-Setup)-outliner.jpg
	:align: center

|

********************************************************
 | Pose - Turntable.ma
********************************************************

Pose file for youtube video.

Referencing Shenya Rig.ma

.. image:: /images/Maya-Pose-Turntable-viewport.jpg
	:align: center

.. image:: /images/Maya-Pose-Turntable-outliner.jpg
	:align: center

.. note::
	Pose_Export is a duplicate of Shenya:geo_root, the mesh is further tweaked in Zbrush.

|

********************************************************
 | Pose - Holding Lantern.ma
********************************************************

Pose file for marmoset.

Referencing Shenya Rig.ma and Latern.ma

.. image:: /images/Maya-Pose-Holding-Lantern-viewport.jpg
	:align: center

|

********************************************************
 | Pose - Sitting on Stairs.ma
********************************************************

Pose file for marmoset.

Referencing Shenya Rig (Cloth Setup).ma

.. image:: /images/Maya-Pose-Sitting-on-Stairs-viewport.jpg
	:align: center

|

********************************************************
 | Lantern.ma
********************************************************

Referenced by "Pose - Holding Lantern.ma"

|

********************************************************
 | anim-layer-breath.ma
********************************************************

Animation layer for importing. Used in Pose - Turntable.ma

|

********************************************************
 | cloth-setup.ma
********************************************************

Shenya Rig.ma + cloth-setup.ma => Shenya Rig (Cloth Setup).ma

|

********************************************************
 | lightings-A.ma
********************************************************

Just a few lights, for viewing model with lighting in Maya viewport.

|

********************************************************
 | workspace.mel
********************************************************

Maya Project definition file, for setting up maya project so the textures can be linked properly.

|

********************************************************
Rig
********************************************************
Shenya is rigged with `mGear <http://www.mgear-framework.com/>`_, more on :ref:`this page<mgear>`

