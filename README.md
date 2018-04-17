# Merging/Pulling Exercise

## Prerequisites

- You have a GitHub account and you know your username and password. If you
  don't have one, create one now.
- You have Git 2+ installed and configured.
- You know how to open a terminal and generally work from the command-line.
- You know enough of vi or vim to edit, move around in, save, and quit files.

## Learning Objectives

- Clone a repository you would like to contribute
- Create a new branch
- Make a pull request
- Resolve merge conflicts

## Instructor:

- Creates a (public) repository
- Add an initial README
- Add an initial rainbow.md file containing color names
- Share the github repo URL with the students

## Students: 

- Clone the instructor's repo to your local hard drive using
`git clone `
- Create a new branch to make a change. Call your branch: <color-your_first_name>.
- Add your name to the list: list your first name underneath your favorite color. If you select "Other", use the following format: Color (Your name).
- Add your changes using `git add`.

At this point, we need to figure out how to do the merging. The idea here is to have students to pull-in changes in order to keep their document up-to-date as others are adding their changes. Potentially, we could have the following:

- Select a volunteer who will be the first to commit their change. ​They c​reate a pull request (PR) to merge the​ir​ change into master.
- In the main repo, ​the instructor ​merge​s​ the new change into master by approving the PR.
- Everyone should now sync their repo via `git pull`. Note that people who selected the same color should/might(?) now get a merge conflict...
<how to solve the merge conflict>
- Someone with the same color else can now commit their branch and submit a PR for their change.
- Repeat the above steps to integrate the new change.
- Two new volunteers with two different colors should now submit their changes.
