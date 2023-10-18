
# A repository to play with branch protection rules 
 
To prevent a PR to a branch that contains commits not in the mainline using GitHub branch protection rules, you can use the following steps:

Go to your repository's Settings page.

If a pull request is submitted to the protected branch that does not have a linear history, the pull request will be rejected.

Here are some additional tips for using branch protection rules:

You can also use branch protection rules to require other things, such as a review from at least one other team member before the pull request can be merged.
You can also use branch protection rules to prevent certain people from pushing to the protected branch.
You can also use branch protection rules to require certain checks to pass before the pull request can be merged, such as a code review or a build check.
By using branch protection rules, you can help to ensure the quality and consistency of your code.

Note: If you are using a protected branch to maintain a release branch, you may need to disable the Require linear history rule temporarily in order to merge hotfixes or other urgent changes.
