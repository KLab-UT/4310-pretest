# 4310-pretest
# Introduction

The aim of this pretest is simply to see where you are in your bioinformatics journey. Don't be stressed by it! Your grade for this pretest is based solely on completion.

# Contents

-   [Getting set up](#getting-set-up)
-   [Running the test](#running-test)
-   [License](#license)


# Getting set up

At this point, you should have
(1) an account on [Github](https://github.com/) and
(2) been introduced to the very basics of [Git](https://git-scm.com/).

1.  Login to your [Github](https://github.com/) account.

1.  Fork [this repository](https://github.com/KLab-UT/4310-pretest) by
    clicking the 'Fork' button on the upper right of the page.

    After a few seconds, you should be looking at *your* 
    copy of the repo in your own Github account.

1.  Click the 'Clone or download' button, and copy the URL of the repo via the
    'copy to clipboard' button.

1.  In your terminal, navigate to where you want to keep this repo (you can
    always move it later, so just your home directory is fine). Then type:

        $ git clone the-url-you-just-copied

    and hit enter to clone the repository. Make sure you are cloning **your**
    fork of this repo.

1.  Next, `cd` into the directory:

        $ cd the-name-of-directory-you-just-cloned

1.  At this point, you should be in your own local copy of the repository.

1.  As you work on the exercise below, be sure to frequently `add` and `commit`
    your work and `push` changes to the *remote* copy of the repo hosted on
    GitHub. Don't enter these commands now; this is just to jog your memory:

        $ # Do some work
        $ git add file-you-worked-on.py
        $ git commit
        $ git push origin master

---

# Running the test

Once you have cloned the repository, move into the directory

$ cd path/to/repository/4310-pretest

Begin the pretest by running the script

$ python3 pretest.py

Answer the questions by typing a response and hitting enter. Your output will be written to test_results.txt.

Once you have finished, make sure to add, commit, and push.
