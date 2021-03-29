###############################
mGear Customize Rig
###############################

If you like to customize the rig, this section might be some help.

********************************************************
Rebuild Rigs
********************************************************

Before building the rig using guide, you need to set an enviroment variable to point to the location of custom scripts:

You can add the following line to maya.env (located under C:\\Users\\<username>\\Documents\\maya\\2020)


.. code-block:: bat

	set MGEAR_SHIFTER_CUSTOMSTEP_PATH=C:\Projects\Personal\Global Game Art Contest\Marketplace\Project Files\Maya\rig-build




or run the following Python command inside Maya:

.. code-block:: python

	import os
	os.environ['MGEAR_SHIFTER_CUSTOMSTEP_PATH'] = 'C:/Projects/Personal/Global Game Art Contest/Marketplace/Project Files/Maya/rig-build'


.. note::
   Replace the path above to point to the correct location on your system.

   eg. if the project files are extracted to to D:\\Downloads\\Shenya, the path then becomes D:\\Downloads\\Shenya\\Maya\\rig-build


