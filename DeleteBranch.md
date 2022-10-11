Delete a branch with 

**git branch -d <branch>** 

The -d option will delete the branch only if it has already been pushed and merged with the remote branch. 
Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet. 
The branch is now deleted locally.

Remote branches are separate from local branches.#
The command to delete a remote branch is:

**git push remote_name -d remote_branch_name**
  
Example: git push origin -d dev-test
