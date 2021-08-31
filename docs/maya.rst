###############################
Maya
###############################

Character model is built with Maya 2020.

Character height in scene: 186cm

.. admonition:: File List in Maya Folder
   :class: refbox

   * Shenya Rig.ma
   * Shenya Rig (Cloth Setup).ma
   * Pose - Sketchfab.ma
   * Pose - Marketplace Cover.ma
   * Pose - Holding Lantern.ma
   * Pose - Sitting on Stairs.ma
   * Lantern.ma
   * cloth-setup.ma
   * lightings-A.ma
   * [rig-build]
      ... files related to building mgear rig ...
   * [scripts]
      ... some Python scripts ...
   * [cache]
      ... ncloth cache for Pose - Sitting on Stairs.ma ...

.. note::
   Naming conventions for the files: lower case files are mostly used as import 
   
   ie.
   < mgear-guide.ma >, < cloth-setup.ma > and < lightings-A.ma > are files to be imported

|

.. note::
   If the image displayed in this document is too small, right click on the image and "Open Image in New Tab" to see the full resolution.

|

********************************************************
About the Rig
********************************************************
Shenya is rigged with `mGear <http://www.mgear-framework.com/>`_, more about mGear on :ref:`this page<mgear_bookmark>`

Please be aware that it is however not a game friendly rig, it is using some "gimmick joints" and the elbow and knees got double joints for slightly more realistic deformations. It can still be brought into game engines I think it will probably needs some extra works to set it up correctly.

|

********************************************************
 🗋 Shenya Rig.ma
********************************************************

Main character model file with rig.

.. image:: /images/Maya-Shenya-Rig-viewport.jpg
	:align: center

.. image:: /images/Maya-Shenya-Rig-outliner.jpg
	:align: center

|

********************************************************
 🗋 Shenya Rig (Cloth Setup).ma
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
 🗋 Pose - Marketplace Cover.ma
********************************************************

Pose file for rendering images to be used on websites.

Referencing Shenya Rig.ma

.. image:: /images/Maya-Pose-Marketplace-Cover-viewport.jpg
	:align: center

.. image:: /images/Maya-Pose-Marketplace-Cover-outliner.jpg
	:align: center

|


********************************************************
 🗋 Pose - Sketchfab.ma
********************************************************

Pose file for Sketchfab.

Referencing Shenya Rig.ma

.. image:: /images/Maya-Pose-Sketchfab-viewport.jpg
   :align: center

|

********************************************************
 🗋 Pose - Holding Lantern.ma
********************************************************

Pose file for marmoset.

Referencing Shenya Rig.ma and Latern.ma

.. image:: /images/Maya-Pose-Holding-Lantern-viewport.jpg
	:align: center

|

********************************************************
 🗋 Pose - Sitting on Stairs.ma
********************************************************

Pose file for marmoset.

Referencing Shenya Rig (Cloth Setup).ma

.. image:: /images/Maya-Pose-Sitting-on-Stairs-viewport.jpg
	:align: center

|

********************************************************
 🗋 mgear-guide.ma
********************************************************

This file contain the mgear guide, it is needed if you need to rebuild the rig using mgear (for any reason like adjusting the joint positions, or modifying the mgear component to adjust the functionality, etc)

.. image:: /images/Maya-mgear-guide-viewport.jpg
   :align: center

|

********************************************************
 🗋 cloth-setup.ma
********************************************************

This file contains the setup for ncloth meshes. It is used with "Shenya Rig.ma" to create "Shenya Rig (Cloth Setup).ma". The result file "Shenya Rig (Cloth Setup).ma" is used for simulating cloth in the stairs scene "Pose - Sitting on Stairs.ma".

I use a script that you can find under "Maya\scripts\Shenya Setup nCloth.py" to create the "Shenya Rig (Cloth Setup).ma".

If you modified "Shenya Rig.ma", you can use that script to regenerate "Shenya Rig (Cloth Setup).ma".

.. image:: /images/Maya-cloth-setup-viewport.jpg
   :align: center

|

********************************************************
 🗋 lightings-A.ma
********************************************************

Just a few lights, for viewing model with lighting in Maya viewport.

|

********************************************************
 🗋 workspace.mel
********************************************************

Maya Project definition file, for setting up maya project so the textures can be linked properly.

|


********************************************************
 🗋 Lantern.ma
********************************************************

Referenced by "Pose - Holding Lantern.ma"
