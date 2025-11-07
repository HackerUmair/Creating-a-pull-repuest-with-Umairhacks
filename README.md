# Creating-a-pull-repuest-with-Umairhacks

Creating a pull request
Create a pull request to propose and collaborate on changes to a repository. These changes are proposed in a branch, which ensures that the default branch only contains finished and approved work.

Who can use this feature?
Anyone with read access to a repository can create a pull request.

Platform navigation
Mac
Windows
Tool navigation
GitHub CLI
Codespaces
Desktop
Web browser
In this article
If you want to create a new branch for your pull request and do not have write permissions to the repository, you can fork the repository first. For more information, see Creating a pull request from a fork and About forks.

You can specify which branch you'd like to merge your changes into when you create your pull request. Pull requests can only be opened between two branches that are different.

Note

To open a pull request in a public repository, you must have write access to the head or the source branch or, for organization-owned repositories, you must be a member of the organization that owns the repository to open a pull request.

You can link a pull request to an issue to show that a fix is in progress and to automatically close the issue when someone merges the pull request. For more information, see Linking a pull request to an issue.

Changing the branch range and destination repository
By default, pull requests are based on the parent repository's default branch. For more information, see About branches.

If the default parent repository isn't correct, you can change both the parent repository and the branch with the drop-down lists. You can also swap your head and base branches with the drop-down lists to establish diffs between reference points. References here must be branch names in your GitHub repository.

Screenshot of a pull request. The dropdown to edit the compare branch is expanded.

When thinking about branches, remember that the base branch is where changes should be applied, the head branch contains what you would like to be applied.

When you change the base repository, you also change notifications for the pull request. Everyone that can push to the base repository will receive an email notification and see the new pull request in their dashboard the next time they sign in.

When you change any of the information in the branch range, the Commit and Files changed preview areas will update to show your new range.

Tip

Using the compare view, you can set up comparisons across any timeframe. For more information, see Comparing commits.
Project maintainers can add a pull request template for a repository. Templates include prompts for information in the body of a pull request. For more information, see About issue and pull request templates.
Creating the pull request
On GitHub, navigate to the main page of the repository.

In the "Branch" menu, choose the branch that contains your commits.

Screenshot of the branch dropdown menu on the main page of a repository.
Above the list of files, in the yellow banner, click Compare & pull request to create a pull request for the associated branch.

Screenshot of the banner above the list of files.
Use the base branch dropdown menu to select the branch you'd like to merge your changes into, then use the compare branch drop-down menu to choose the topic branch you made your changes in.

Type a title and description for your pull request.

To create a pull request that is ready for review, click Create Pull Request. To create a draft pull request, use the drop-down and select Create Draft Pull Request, then click Draft Pull Request. If you are the member of an organization, you may need to request access to draft pull requests from an organization owner. See About pull requests.

Tip

After you create a pull request, you can ask a specific person to review your proposed changes. For more information, see Requesting a pull request review.

After your pull request has been reviewed, it can be merged into the repository.

Making changes to files in your pull request
After you have opened your pull request, you can continue making changes to the files by adding new commits to your head branch.

You can also make changes to files on the GitHub website.

On GitHub, navigate to a pull request in a repository.

On the pull request, click  Files changed.

Screenshot of the tabs for a pull request. The "Files changed" tab is outlined in dark orange.
Scroll down to the file you want to make changes to.

If the pull request has a lot of files, you can use the filter to locate the file. See Filtering files in a pull request.
Above the file you want to change, click .

Screenshot of the options above a file on the "File changed" tab. The "Show options" button is highlighted with an orange rectangle.
In the menu, click Edit file.

Make your changes in the editor and when committing your change, choose to commit directly back to your head branch.

Further reading
Creating a pull request from a fork
Keeping your pull request in sync with the base branch
Changing the base branch of a pull request
Creating an issue
Assigning issues and pull requests to other GitHub users
Writing on GitHub
Help and support
