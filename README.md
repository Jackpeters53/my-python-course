# Python Course

## Installation:
1) Anaconda with Python 3.7 (64 bit) (https://www.anaconda.com/)
2) Git (for Windows: https://gitforwindows.org/)

## First steps with Git:
1) Go to github.com and register. Send an email with your username to *maxhantke@gmail.com*.
2) Open *Git BASH*
3) Tell Git who you are by calling: ``git config —-global user.name “Max Hantke”`` and ``git config —-global user.email “max.hantke@gmail.com”``
4) Navigate (basic commands: ``ls``, ``cd``, ``pwd``) to the directory where you like to keep your python code
5) Make a clone of this repository by calling: ``git clone https://github.com/mhantke/python-course.git``
6) Check whether the repository was generated (call ``ls``)
7) Open your file explorer, navigate to the cloned repository, and make a copy of *session1.ipynb*. This copy is your personal notebook therefore append an underscore followed by your last name to the name of the new file (for example: *session1_hantke.ipynb*).
8) Go back to Git BASH and add the new file to the repository. For the example this can be done by calling: ``git add session1_hantke.ipynb``.
9) Commit your change to the repository by calling: ``git commit -a -m "added a new file"``.
10) Push your changes to the *Github* server by calling: ``git push``. You will be asked to enter your Github account credentials.
11) Check under the tab **<> Code** (here on this webpage) whether your file has been synched to the online repository.
