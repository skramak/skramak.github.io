
# Git Crash Course: Setting up Git and Github (Desktop)

***

While using the command is the standard method for interacting with Git and Github, Github Desktop makes tracking changes and updating your files even easier by providing a desktop application and graphic user interface (no command line coding necessary!).

## 1. Download and Install Github Desktop

If you've already gone through the steps from [Part 1](https://github.com/lukemich47/big-data-spring2017/blob/master/week1/Part1_IntroGitAndGithub.ipynb), then you've already set up a Github account. So we'll jump to installing Github Desktop.

Navigate to the [Github Desktop homepage](https://desktop.github.com/) and download the client.

![Github Desktop Homepage](images/homepage.png "Github Desktop Homepage")

## 2. Using the Application

Once you start the application, you'll be prompted to authenticate to Github using your login information. Next, a series of information windows will open to step you through an entry tutorial.

![Github Desktop Start Screen](images/startscreen.png "Github Desktop Start Screen")

While you should definitely take some time to walk through this built-in tutorial, we'll skip this for now to show you the basics.

***

### Adding a Repo

Click on the plus sign in the upper left corner of the Github Desktop start screen to add a repo.

![Adding a Repo](images/addrepo.png "Adding a Repo")

From here, we can create a new Git repository, clone a repo from a remote location, or add an existing repo. Since we created a repo in Part 1, let's select the "Add" tab. Then click "Browse" to navigate through our local file structure. Select the folder that contains our root working directory. In my case, I'll be adding the repo that contains this tutorial.

***

### Viewing Changes

Now that we've added our local repo to the desktop app, we can view, commit, and push any changes that we make locally. With the recently-added repo selected in the left panel, select the "Changes" tab at the top of the screen, which will let you view your recent changes.

![Viewing Changes](images/changes.png "Viewing Changes")

If you don't see any changes here, navigate to your repo location on your local machine and make a change (create a blank text file, for example).

***

### Committing Changes

To commit our new changes, first give your commit a comment and, if you'd like, a more specific description. Then click "Commit to master."

![Commit Changes](images/commit.png "Committing Changes")

***

### Working with Branches

To create a branch, simply click the branch button at the top of the application, and name the branch.

![Creating a Branch](images/newbranch.png "Creating a Branch")

You can publish this branch to your remote repo (the existence of the branch, not the changes on it) with the "Publish" button in the upper right.

To delete a branch, select the gear symbol in the upper right corner and select "Delete branch_name."

![Deleting a Branch](images/deletebranch.png "Deleting a Branch")

***

### The Branch Diagram

Across the top of the application's layout, we see the branch diagram. This shows us how our project has evolved and let's us quickly see the various branching steps and committed changes that have occured. Your diagram will be a bit simpler than the one shown here, but you should see the commit we just completed in the previous step (committed changes show as open circles; synced changes show as filled dots).

![Branch Diagram](images/branchdiagram.png "Branch Diagram")

***

### Viewing History

If we click on the "History" tab at the top of the application, we can see a list of our previous commits. Select one of your commits on the left to view the list of changes. We can then click the small arrow next to each change to view the specific lines of text that have been changed.

![Viewing History](images/history.png "Viewing History")

If we want to return to a state of our code prior to a given commit, we can click the "Revert button."

***

### Syncing Changes

To sync our changes, simply click the Sync button in the top right corner. This pushes our commit to our remote repo on the Github site. You'll see the open circle(s) in the branch diagram turn into closed dots.

***

## 3. Additional Resources

Feel free to read more about [Getting Started](https://help.github.com/desktop/guides/getting-started/) and [Contributing to Projects](https://help.github.com/desktop/guides/contributing/) with Github Desktop.
