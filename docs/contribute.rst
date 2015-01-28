.. _contribute:

Technical hints for contributors
===================================



How to contribute
---------------------------


1. Fork the repository
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`Forking <https://help.github.com/articles/fork-a-repo/>`_ a repository on github means creating a clone of a repository on github. Simply
click on "Fork" in the TRAL repos `TRAL repository <https://github.com/elkeschaper/TandemRepeats/>`_
once you have a Github account.


2. Clone the repository from your fork
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

From the command line, create a clone of your fork:

::

    git clone https://github.com/<YOUR_USER_NAME>/TandemRepeats


3. Create your feature branch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If you use git-flow, start a new feature:
::

    git-flow start feature <YOUR_FEATURE>


Otherwise, create a new branch as follows:
::

    git checkout -b feature/<YOUR_FEATURE>

Next, add the necessary changes and commit them:
::

    git add <CHANGED_FILE>
    git commit -m 'CHANGED_FILE: DESCRIPTION OF YOUR CHANGES’


4. Push your feature branch to your github fork
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

::

    git push origin feature/<FEATURE_NAME>


5. Create a pull request.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Create the `pull request <https://help.github.com/articles/using-pull-requests/>`_ online on github.
For this, go to your github page and click on "Pull Request".
::

    https://github.com/<YOUR_USER_NAME>/TandemRepeats


Do a pull request on the develop branch of  elkeschaper/Tandemrepeats.

::

    base fork: elkeschaper/Tandemrepeats
    base: develop





How to help on the homepage
---------------------------

Check out the current version of the TRAL homepage as follows:

::

    git clone --single-branch -b gh-pages https://<your_git_name>@github.com/elkeschaper/TandemRepeats.git





