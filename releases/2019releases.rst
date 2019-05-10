===================
2019 Release Notes
===================

May 9th, 2019
-----------------

Updated Mobile Navigation
The mobile version of the platform now has updated navigation. The up arrow and down arrow from the previous update has been added into the content view. As well as the “Up Next” near the bottom of the content window.

.. image:: images/mnav1.png

.. image:: images/mnav2.png

April 19, 2019
----------------

Updated Course Navigation and Content Windows
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Previously, when clicking on any of the course content, it would redirect the user to a new page, aside from a few exceptions. The only way to continue to go through the course would be to go back to the course view and click on a new piece of content.

With this update, the entire course navigation has been overhauled. When clicking on a piece of content, a content window will appear with the content inside. There are several different parts to the interface: 

.. image:: images/nav1.png

**Exit Button**

In the top right corner of the window is a button with an “X” on it. Clicking on this will return the user back to the current lesson they are on.

.. image:: images/nav2.png

.. note::  If the user had progressed or went back to other lessons using the Navigation arrows, the button will exit them to that lesson they are currently on. 

**Navigation Bar**

Next to the navigation arrows is the Navigation bar. The Navigation bar will fill up the length of the window as a user progresses through a lesson. It will show the user the percentage of content they are into the lesson, as well as how many items are in the lesson and how far deep into the lesson they are. 

.. image:: images/nav3.png

.. note:: This does not show the completion of the lesson, just where a user is in a lesson.

**Navigation Arrows**

The two arrows at the top of the content window. The one pointing up will direct the user to the previous content, while the one pointing down will direct the user to the next content

.. image:: images/nav4.png

If it is the first piece of content in a course, the “Up” arrow will be grayed out, implying that there is no more content to view in this direction. If it the last piece of content in a course, then the “Down” arrow will be grayed out. 

.. note:: The arrow buttons will still work to cross through different lessons.

**Up Next Section**

At the bottom of the content window is a section displaying the next piece of content in a lesson or the next lesson if the user is at the end of a lesson. Activating it will move the user to the next content window. This has the same effect as activating the “Down” arrow.

.. image:: images/nav5.png
.. image:: images/nav6.png

**Discussions and Instructions**

Discussions and instructions now appear as boxes outside of content window. Their functions are still the same.

.. image:: images/nav7.png

**Video**

Activating a video will now open a video content window. The video title will appear below the video along with its run time. With this redesign,the transcript appears below the video. 

.. image:: images/nav8.png

Clicking on the transcript wording will allow for the video to skip to the part of the video. If the transcript is long enough to scroll down, the video will shrink and follow the user in their window. If a user desires to see the default Media Viewer, the option to view the video in this mode is right below the video.

.. image:: images/nav9.png

Display Learners in Sidebar on Discussions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Learners who have commented in a discussion now display on the right-hand sidebar while viewing the discussion.

.. image:: images/userdis.png

Februrary 21, 2019
------------------

Allow Multiple Attempts on Assignments
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Add Multiple Attempts:**

Instructors and Admins can now set the number of attempts a learner can take on an assignment. 

To set the number of attempts, select the “Options” button while editing an assignment, and scroll down.

.. note:: Both a value and passing score must be defined in order to add multiple attempts.

Choose between one attempt, multiple attempts, or unlimited attempts.

.. image:: images/multisubs1.png

To select a range between two and twenty attempts, select the middle dropdown option.

.. image:: images/MultiSubs2.png

Select a value to set the desired number of attempts. 

.. image:: images/MultiSubs3.png

**Assignment Completion:**

Successful completion of an assignment can be defined as:

- **Submission Only** (Once the learner submits the assignment, the assignment is marked as complete.)
- **Passing Score** (The learner must gain a passing score.)
- **Excused** (If the facilitator excuses the assignment, the assignment will be marked as complete despite any other parameters.)
- **No Submit Grade** (A no submit assignment type cannot have multiple attempts. For no submit assignments, adding a grade will act as a “submission.”)

Multiple attempts can be added in order to allow the learner multiple attempts to gain a passing score, and thus multiple attempts for successful completion of the assignment. The displayed score on the assignment will be the highest score achieved of all attempts. Once the learner achieves the passing score or above, no more attempts will be allowed. 

To learn more about this feature, click here!
https://help.nextthought.com/editorguide/assignment.html#adding-multiple-attempts

Enrollment Management in Course Roster
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The course roster now has an option for site admins to enroll or drop users from the Course’s Admin Tools > Course Roster.

Selecting ”Manage Enrollment” will open a window displaying all site users and a search bar. Search for learners within the search bar and select a learner.

.. image:: images/ManEn1.png

After selecting a learner, the learner’s current course enrollment status will display. If they are not enrolled, you can select “Enroll User” to add them to the course.

.. image:: images/ManEn2.png

.. image:: images/ManEn3.png

If the learner is enrolled, the “Enrolled” text and course information will display. The enrolled user can be removed from the course by selecting the “Remove User” button.

.. image:: images/ManEn4.png

**Advanced Enrollment Options**

Each site will have a defined set of user enrollment scopes. The “Advanced” dropdown will allow admins to enroll a learner into a specific scope.

For example, a university site may have two defined scopes: “enrolled” and “open.” By default learners may be enrolled into the “open” scope; however, using the advanced dropdown, and knowing the scopes allowed on the site, you can define the user as “enrolled” to enroll them in that scope.

.. note:: Please ask your project manager if you’d like to enroll a learner into a specific scope.

Add and Remove Group Members
^^^^^^^^^^^^^^^^^^^^^^^^^

Site admins have the ability to add site users to a group.

After selecting “Create a Group,” you will be presented with a window to type a group name, and automatically add group members across the site. Select “Create” to create the group.

.. image:: images/creategroup1.png

You can also choose to edit a group, and add or remove group members. Click “Save” to save your changes.

.. image:: images/creategroup2.png

January 31, 2019
-----------------

Calendar Notifications
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Calendars will now notify the user when events are created or modified and are directly related to the user. The notifications will be sent on the platforms as well as by email. 

Passing and Failing Assignments Based on Scores
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Assignments can now be set to pass or fail based on grade. The grade will be determined by the percentage of points earned in the assignment. 

To activate this feature on an assignment, open an assignment in edit mode. At the top of of the screen click on the “PASSING SCORE” field and click the checkbox labeled “Passing Score”. Enter the desired passing percentage to set the passing score. 

.. image:: images/passfail.png

.. note:: Please note, you must have the value field set for this feature to activate. If you do not, a prompt will direct you to set a value. 

Once you have saved and published the assignment, the learner can view the passing score requirement by opening up the assignment and viewing the top of the assignment for the newly designed field. The learner will now have to not only complete the assignment, but have a passing score in order to complete assignment and, thus, the course.

.. image:: images/studentpassfail.png


Course Switcher
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Site administrators can switch between different sections of a course by using this new feature. To use the Course Switcher, the admin should navigate to the desired course and then click the arrow beside the course name. The drop down menu will contain all other sections as well as other options such as a course visibility option, a delete button to delete the course and a link to edit the course information.

.. image:: images/courseswitcher.png

January 10, 2019
-----------------

Calendar URL
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

You can now export and sync the NextThought Calendar to your personal calendar using the provided URL within the calendar feature. Click the ellipsis icon to reveal the dropdown.

.. image:: images/calendarurl.png
