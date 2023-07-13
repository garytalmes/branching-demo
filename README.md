# Branching and Merging Demo 

Here's how to set up your repo for the group projects:

First:

- Go to Settings -> Collaborators
- Click the green `Add People` button 
- Type the Github username of the person you wish to add. When you find the right person, click the `Invite` button.

Next:

- Create your repo
- Go To Settings -> Branches
- Under Branch Protection Rules, click the `Add Rule` button.
- For Branch Name Pattern, type the name of your primary branch (either main or master).
- Check the box that reads "Require a pull request before merging"
- Click the `Create` button at the bottom.
- Each team member should do a git clone on the repo. Everyone will work from their own local copy, but will update the repo regularly.

Main Rules for Group Work:

- NO ONE pushes to the main branch. You create feature branches locally, push them to the repo, and then create a Pull Request.
- Pull requests are approved by the repo administrator. Once approved, the main branch is modified with the new code.
- The Administrator informs everyone that main has been updated.
- Everyone should:
  - Stops what you're doing in your current branch and do a `git add` and `git commit` of their work.
  - Check out the main branch and do a `git pull`
  - Go back to the branch you were working on, and do a `git merge`

