# Merging/Pulling Exercise

## Prerequisites 

(from https://github.com/StoneyJackson/github-workflow-activity/blob/rewrite/reference.md)

- You have a GitHub account and you know your username and password. If you
  don't have one, create one now.
- You have Git 2+ installed and configured.
- You know how to open a terminal and generally work from the command-line.
- You know enough of vi or vim to edit, move around in, save, and quit files.

## Learning Objectives
When you finish this exercise, you will be able to...
- Fork a repository you would like to contribute to
- Clone a forked repository to your local hard drive
- Create a new branch (via CLI and GitHub web interface)
- Make a pull request 
- Resolve merge conflicts

## Instructor:

- Creates a (public) repository
- Add an initial README.md
- Add an initial rainbow.md containing color names
- Share the github repo URL with the students

## Students: 
Note: lines starting with [GitHub] should be done through GitHub's web interface.

- [GitHub] Fork the instructor's repo to your GitHub account

- Clone the forked repository to your local hard drive:

`git clone <<forked github repo>>`

- Cd to the new directory you just cloned

- Create a new branch and check out the branch to make a change. Call your branch: <color-your_first_name-branch>, for example:

`git checkout -b red-firstname-branch`

(Specifying `-b` causes a new branch to be created as if git-branch were called and then checked out.)

Let's edit rainbow.md to add you color and name to it using your favorite text editor.

- Add your name to the list: list your first name underneath your favorite color, for example, under the Red section,

`red-firstname`

(Save and exit--you may now try `git status` to see the rainbow.md was modified but not added.)

- Add your changes to your local git repository:

`git add rainbow.md`

- Commit your change:

 `git commit -m "added my color and name"`

(The "added my color and name" part is a commit message. When you commit, you should always give a meaningful message showing what's done and changed.)

- Push your change to the forked repository

They create a pull request (PR) to merge their change into master.
- In the main repo, the instructor merges the new change into master by approving the PR.
- Everyone should now sync their repo via `git pull`. Note that people who selected the same color should/might(?) now get a merge conflict...
<how to solve the merge conflict>
- Someone with the same color else can now commit their branch and submit a PR for their change.
- Repeat the above steps to integrate the new change.
- Two new volunteers with two different colors should now submit their changes.
