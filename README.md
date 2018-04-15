# Merging/Pulling Exercise
Merge conflict, pull request, and how to resolve the conflict

Instructor creates a repository, which is set up such that changes to the master branch have to be approved before being merged.
<setup instructions>

## Instruct the students to: 
- Clone the repo.
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
