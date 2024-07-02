# Exercice_CI_Git
#### For use Branch, Rebase, Tickets, Protection branche, and confidential Information

## For use git rebase :

Rebase takes a set of commits, "copy" them, and adds them at the end of the chain in another place.
Exemple : if you have two branches -Main -Dev and you would like to copy Dev on Main. you do to use 

`git checkout dev`

`git rebase main`

and after for update -Main 
when you are on the branche -Main 

`git checkout main`

`git rebase main`


## For use tickets with collaborateur :

### Create Issues

For start creat an Issues on GitHub With title, description, labels, 
and assign the issue to a collaborateur and add to the project the issue.

### Make reference issues in commits and pull requests

For the commit for example : 

`git commit -m "Fixes #123: Fix fix the fix"`

For the Pull Requests :

When creating a Pull Request, reference the issues in the PR description. For example :

`Closes #123: Adds Fix fix feature`

### Validation and merge process

Creat a new branch :

Work on a specific branch for each new feature or bug. For example :

`git checkout -b feature/fix`

Make regular commits with clear messages that reference the corresponding issues.

Open a pull request :

Once your work is complete, push your branch to GitHub and open a Pull Request.

Code Review and Approval :

Other developers can now review the code. Once approved, the PR can be merged.

Close Issues :

Issues referenced in commits or PR descriptions will automatically be closed once the PR is merged.

## For protect the branch :

## for protect the confidential information in th ci/cd :