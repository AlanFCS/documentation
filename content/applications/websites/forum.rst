=====
Forum
=====

Odoo Forum enables you to connect with your community, give visitors' websites the information they
need and provide outstanding customer satisfaction.

.. seealso::
   - `Forum <https://www.odoo.com/app/forum>`_
   - `eLearning <https://www.odoo.com/app/elearning>`_
   - :doc:`Website documentation <website>`

Configuration
=============

Forum is not automatically installed with :guilabel:`Website`. To enable it, go to :guilabel:`Apps`,
search :guilabel:`Forum` module, and install it.

.. note::
   You can manage **Forum** on both the **front end** and the **back end**. The **front end** allows
   you to create a new forum quickly from your website, while the **back end** allows you to work
   directly from the app. It gives the same options as the front end, but it also provides access to
   more advanced configurations and allows collaboration.

Front-end Forum management
==========================

Forum creation
--------------

From your website, click on :guilabel:`+NEW` and on :guilabel:`Forum` to create a new forum. A new
page pops up. Fill in the following information:

- :guilabel:`Forum Name`: Add the name of your forum;
- :guilabel:`Forum Mode`: Select :guilabel:`Questions mode` (only one answer allowed) or
  :guilabel:`Discussions mode` (multiple answers allowed);
- :guilabel:`Privacy`: Select :guilabel:`Public` (your forum is public), :guilabel:`Signed in` (your
  forum is visible for signed in users only), or :guilabel:`Some users` (your forum and their
  content are hidden for non members of selected group).

Click :guilabel:`SAVE`. Your forum is now created.

.. note::
   You can also create a forum from the :guilabel:`Website` application by going to
   :menuselection:`Website --> Configuration --> Forum --> Forum` and clicking :guilabel:`New`.

New post creation
-----------------

Click :guilabel:`New Post` to create a new post and fill in the following information:

- :guilabel:`Title`: Add a title to your question;
- :guilabel:`Description`: Add a description to your question. Type "/" to use a command and open
  the powerbox;
- :guilabel:`Tags`: Add tags to help filter questions and answers related to the same topic.

Click :guilabel:`Post Your Question`. A new window pops up inviting you to share your question on
social networks.

.. tip::
   Generally, many questions posted on social media platforms receive a response within 5 hours.
   However, if the same questions are shared on two different social networks, the chances of
   obtaining an answer are significantly higher.

.. note::
   Only logged-in users can post questions and answer existing ones to avoid one-time participants
   and spam.

Manage your posts
-----------------

Go to your forum to see questions or discussions available.

A menu bar offers several options:

- :guilabel:`Topics`: By default, all topics are displayed;
- :guilabel:`People`: Display the people that created questions/discussions and small statistical
  information related to XP, Badges, and Certifications;
- :guilabel:`Tags`: See the tags used and retrieve specific questions or discussions that have been
  tagged;
- :guilabel:`Badges`: In addition to building your credibility through your questions and answers,
  you can reward your active contributors with badges according to their participation. Badges are
  visible on both your profile page and your posts;
- :guilabel:`About`: provide guidelines to answer any questions users might have.

You can also refine your search by selecting:

- :guilabel:`All`: To display all questions/discussions for this forum;
- :guilabel:`Solved`: To only display solved questions/discussions;
- :guilabel:`Unsolved`: To only display unsolved questions/discussions;
- :guilabel:`Unanswered`: To only display unanswered questions/discussions.

Interacting with posts
----------------------

When a post is created, you can :guilabel:`answer`, :guilabel:`comment` and :guilabel:`share` it on
social networks.

As the creator of the forum, you also have the possibility to :guilabel:`Edit`, :guilabel:`Close`,
:guilabel:`Delete`, :guilabel:`Flag`, or :guilabel:`View Ticket`, by clicking on ⋮.

You can also :guilabel:`Follow` or :guilabel:`Unfollow` a post by clicking the bell.

Moderation tools
----------------

Use the :guilabel:`Moderation tools` to validate posts or to see posts that have been flagged.

.. note::
   You need enough karma points to be able to moderate. The karma points needed to moderate can be
   updated by going to :guilabel:`Karma Related Rights: Moderate posts`.

Back-end Forum management
=========================

Go to the :menuselection:`Website --> Configuration --> Forum` to access your forum advanced
features.

Forums
------

You can manage your forums by going to :menuselection:`Website --> Configuration --> Forum: Forums`.

Create a forum or update an existing one by clicking on it and fill in the following information:

- :guilabel:`Forum name`: Add a name to your forum;
- :guilabel:`Website`: Select one of your websites if you want your forum to be restricted to this
  website.

3 tabs are available: :ref:`Options <forum/options>`, :ref:`Karma Gains <forum/karma-gains>`,
:ref:`Karma Related Rights <forum/karma-related-rights>`.

.. _forum/options:

Options
~~~~~~~

From this tab you can set the order and visibility of your website.

- :guilabel:`Default Sort`: select :guilabel:`Newest`, :guilabel:`Last Updated`,
  :guilabel:`Most Voted`, :guilabel:`Relevance`, :guilabel:`Answered`.

- :guilabel:`Privacy`:

   - :guilabel:`Public`: Forum is public;
   - :guilabel:`Signed in`: Forum is visible for signed in users;
   - :guilabel:`Some users`: Forum and their content are hidden for non members of selected group.

You also have the possibility to add a short :guilabel:`description visible on your website`.

.. _forum/karma-gains:

Karma Gains
~~~~~~~~~~~

Karma points are given to your participants when they are active on your forum, to keep them
involved and give them access to new functionalities like vote, comment, and edit when they reach a
certain Karma level.

.. note::
   Points are set by default, but can be modified by clicking on them. Each new user is
   automatically granted 3 points when the user email is validated.

.. tip::
   If you have the **eLearning** app, completing quizzes can grant you points.

.. _forum/karma-related-rights:

Karma Related Rights
~~~~~~~~~~~~~~~~~~~~

Go to the :guilabel:`Karma Related Rights` tab to set up a moderation system with Karma points to
give your most active members access to more functionalities and to reduce spamming messages.

Points are set by default, but can be modified by clicking on them.

Click on the :guilabel:`Posts` smart button to get details on your forum's existing posts. Select a
post and click the :guilabel:`Action` button to :guilabel:`Export`, :guilabel:`Publish`,
:guilabel:`Unpublish`, :guilabel:`Archive`, :guilabel:`Unarchive` or :guilabel:`Delete` a specific
post.

.. image:: forum/forum-action-button.png
   :align: center
   :alt: Select the action button

Ranks
-----

You can manage :guilabel:`Ranks` by going to :menuselection:`Website --> Configuration --> Forum:
Ranks`. By-default ranks exist but can be updated as per your needs. You also have the possibilty to
create new ranks by clicking :guilabel:`New`. Fill in the :guilabel:`Rank Name`,
add the :guilabel:`Required Karma`, a :guilabel:`Description` and if you want, fill in the
:guilabel:`Motivational` tab to encourage your users.

Tags
----

:guilabel:`Tags` can be managed by going to :menuselection:`Website --> Configuration --> Forum:
Tags`. Click :guilabel:`New` to create a new tag, and select the :guilabel:`Forum` it is assigned
to.

Badges
------

Grant badges to your members for their questions, answers, shares, likes, and votes to reward the
most active ones. Badges appear on your profile page and your posts. You can manage badges by going
to :menuselection:`Website --> Configuration --> Forum: Badges`.

Close Reasons
-------------

By going to :menuselection:`Website --> Configuration --> Forum: Close Reasons`, you retrieve the
posts close reasons. A post can be closed from the question or discussion  by clicking on ⋮,
:guilabel:`Close` option.
