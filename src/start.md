

# Starting BORIS


Once BORIS App is installed, it can be launched by taping on its icon.




The BORIS main window will appear. At this stage, all toolbar commands are disabled except the Preferences button.


<figure markdown>
  ![Image title](images/home.png)
  <figcaption>The BORIS App main screen</figcaption>
</figure>



# Open a project


* Press the **Open project** button

A list of BORIS project files will open

<figure markdown>
  ![Image title](images/project_list.png)
  <figcaption>The list of BORIS projects</figcaption>
</figure>




* Select a file and press the **Open project** button


BORIS App will show a summary of the selected project:

.. image:: project_details.png
   :scale: 50%


Start a new observation
-----------------------

* Press the **New observation** button


.. image:: new_observation.png
   :scale: 50%


* Input an **Observation id** (mandatory, this id must be unique in your project)

* Change the date (optional, default: current date time)

* Input a description for your observation (optional)

* If independent variables are defined, click on the **Independent var** button and fill the value for each variable.


.. image:: independent_variables.png
   :scale: 50%

* Press the **Start observation** button

You will obtain a screen with buttons corresponding to behaviors defined in your project.
You can press it to code behaviors. The event time will be recorded in your observation.


.. image:: running_observation.png
   :scale: 50%

If behavioral categories are defined in your project, the behaviors will be grouped by category and
buttons will be colored.




Select the focal subject
-------------------------

* Press the **Select focal subject** button

* Select the focal subject. If the focal subject is already selected, the subject will be deselected.

.. image:: select_focal_subject.png
   :scale: 50%

The focal subject will be show in the green button (at left bottom).

.. image:: running_observation_selected_subject.png
   :scale: 50%


State events
------------

If you press on a state event, the corresponding behavior button will be highlighted in red until you press it again
to stop the state event.

.. image:: state_event.png
   :scale: 50%




Modifiers selection
-------------------

If modifiers are defined for the triggered behavior, BORIS App will show the modifiers page.

They are 3 types of modifiers:

* Single item selection from a list

* Multiple items selection from a list

* Numerical

Various sets of modifiers can be defined for a behavior.

BORIS App will show a page with all sets of modifiers defined for the current behavior.

Example for one set of modifiers (single item).
...............................................

.. image:: select_modifiers_1set_single.png
    :scale: 50%


Example for one set of modifiers (multiple items). 2 modifiers are selected.
............................................................................


.. image:: select_modifiers_1set_multiple.png
    :scale: 50%


Example for 2 sets of modifiers (single item)
..............................................

.. image:: select_modifiers_2sets.png
    :scale: 50%




Stop the observation
---------------------

* Press the **Stop observation** red button. Confirm that you want to stop the observation.

The observation will be saved in the current project.




Limitations
===========

These limitations should be fixed in next releases.


* BORIS App can not handle independent variables defined as **set of values**

