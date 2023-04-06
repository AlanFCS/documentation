==============================
Getting started with Appraisal
==============================

Employee goals can be set, appraisals performed, and reports can be run, all through the three main
sections of the :guilabel:`Appraisal` application. Integration with the :guilabel:`Employees`
application means all employees in the company automatically appear in the :guilabel:`Appraisals`
application and are available for appraisals.

Appraisal
=========

The main :guilabel:`Appraisal` view displays all the employees in a kanban view. A banner indicating
the state of their appraisal, either :guilabel:`Ready`, :guilabel:`Done`, or :guilabel:`Canceled`,
appears on each card, if applicable. If the kanban view is grouped by :guilabel:`Status`, the
columns that appear are :guilabel:`To Confirm`, :guilabel:`Confirmed`, :guilabel:`Done`, and
:guilabel:`Canceled`. Drag and move an employee card to a different stage to change the status of
the appraisal. Employees can be filtered by selecting specific companies or departments on the left
side navigation.

.. image:: overview/appraisal-employees.png
   :align: center
   :alt: View all employees and their appraisal status

Goals
=====

Each employee's individual goals are organized in the :guilabel:`Goals` section. The default view
displays all the goal cards individually. :guilabel:`Goals` can be grouped by name or deadline to
better visualize the goals. Each card shows the name of the goal, the progress the employee has
made, the deadline for the goal, the employee's photo, and a :guilabel:`Done` banner when the goal
has been achieved. Each employee requires their own card for each individual goal, so it is common
to see multiple cards for the same goal, assigned to different employees.

.. image:: overview/appraisal-goals.png
   :align: center
   :alt: View all goals for each employee along with the stauts.

Reporting
=========

The :guilabel:`Reporting` tab displays the :guilabel:`Appraisal Analysis` report for the company.
The appraisal are grouped by department and can be displayed by the :guilabel:`Day`,
:guilabel:`Week`, :guilabel:`Month`, or :guilabel:`Year`.

.. image:: overview/appraisal-reporting.png
   :align: center
   :alt: View a color-coded chart of the appraisal status for each employee.

The color of each employee's appraisal indicates the status:

.. list-table::
   :header-rows: 1
   :stub-columns: 1

   * - Color
     - Status
   * - Turquoise
     - Not Started
   * - Peach
     - Sent
   * - Yellow
     - Done
   * - Salmon
     - Cancelled

Configuration
=============

Settings
--------

Go to :menuselection:`Appraisal --> Configuration --> Settings`, and turn on automatic appraisals by
checking the :guilabel:`Appraisal Plans` box. Click on the :guilabel:`Appraisal Plans` internal link
to open the :guilabel:`Appraisal Plans` section.

Checking the :guilabel:`360 Feedback` box will send out pre-configured surveys. This integrates with
the :guilabel:`Surveys` application, so :guilabel:`Surveys` must be installed in order to use this
option. Select a :guilabel:`Default Template`, and edit the template with the
:guilabel:`External Link` button. Edit the form in the pop up, and then click :guilabel:`Save`.

Email feedback templates can be modified in the :guilabel:`Feedback Templates` section. Enter the
text using the text editor to edit the email. Default templates are for employees and managers.

.. image:: overview/appraisal-feedback-template.png
   :align: center
   :alt: View and edit the Feedback Templates for employees and managers.

Click on the :guilabel:`Jobs Configuration` internal link to pull up a list view of all the
:guilabel:`Job Positions` within the company. Add a new position by clicking :guilabel:`Create`,
then enter the :guilabel:`Job Position` and add a description in the :guilabel:`Job Description`
tab. Click on the :guilabel:`Recruitment` tab and enter all the other information for the positoin.
The :guilabel:`Appraisals` tab will be filled in with the emails configured in the
:guilabel:`Feedback Template` section of the :guilabel:`Settings` page. Click :guilabel:`Save` when
done.

Employees
---------

Clicking on :guilabel:`Employees` will take you to a view of all the employees in the company. This
is an identical view to the main view in the :guilabel:`Employees` application. Any changes made
here will be reflected on any application that uses the employees list.

Appraisal Plans
---------------

This is the same view that will appear by going to :menuselection:`Settings --> Appraisal -->
Appraisal Plans Internal Link`. Here, view how often appraisals are automatically created. The
default appraisals are set to be created 6 months after an employee is hired, and 6 months after the
previous appraisal is completed.

New automatic appraisals can be created by clicking the :guilabel:`Create` smart button. Enter how
months should pass before the new appraisal, and select whether or not the appraisal happens after
the employee is hired or after the previous appraisal. This list can be exported to a spreadsheet.

Evaluation Scale
----------------

See the available options for an evaluation in this list. Add a new scale by clicking
:guilabel:`Create`, entering the text to appear on the evaluation, and select the company the
specific line applies to. Delete a line by checking the box next to it, and clicking
:menuselection:`Actions --> Delete`. Click and drag the entries to change the order in which they
appear on the appraisal.
