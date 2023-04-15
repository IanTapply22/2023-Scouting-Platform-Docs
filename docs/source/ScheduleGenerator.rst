Schedule Generator
=====

.. _schedule-generator:

About
------------

The schedule generator is a tool that takes a First Robotics event key and exports a schedule that includes all teams competing and the match number to a CSV file. 
The CSV file can then be used in the official team 1114 scouting platform to automatically retrieve the current team you are scouting.

All credit goes to Cody for creating this tool.

Usage and Prerequisites
------------

The only prerequisite is Node.js. You can find the latest version here: https://nodejs.org/en/.

Before using this tool, you must first add your TBA (The Blue Alliance) API key to a file called tba_key.txt in the root directory of this project.
You can find your TBA key here: https://www.thebluealliance.com/account

Generating Schedules
----------------

To retrieve a schedule for a First Robotics event you can use the following command:

.. code-block:: console

   node ./index.js <event_key>

Be sure to replace the event key with the event key of the event you want to retrieve the schedule for and ensure you TBA API key is valid and is in the tba_key.txt file.


Examples
----------------

.. code-block:: console

   node ./index.js 2023oncomp2
   node ./index.js 2023onto3