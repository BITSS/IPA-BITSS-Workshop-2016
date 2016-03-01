Outline of GitHub Desktop Demo
==============================
BITSS-IPA Workshop, March 2016
------------------------------

###To get started:

1. Download and install the GitHub Desktop app.
2. Download and install MarkdownPad.
3. Setup the app by telling it your GitHub user name (which you need to create if you haven't already).

###Creating and Changing:

1. Create a new repository. *What files are in it?*
1. Add a README.md
1. Commit the changes.
1. Make some more changes, and also add a .do file. *What do changes look like? History?*
1. Commit the changes separately.
1. Undo a commit with Revert. *Does it work if you try to revert a commit that adds a file?*
2. Undo a commit with the undo menu option. *What's the difference?*
3. Discard uncommitted changes.

###Publishing (pushing and pulling):

You can store stuff online at GitHub.com (or any server with Git installed), which will enable you to work on multiple computers.

1. Just click the Publish button.
2. Make changes online via GitHub.com.
3. Sync with the sync button.

Go back and forth between local and remote (online) changes, being sure to sync between each commit. Eventually you'll screw up and not sync enough. (That is, change a file online and commit it. Don't sync. Make a contradictory change locally and commit it. Try and sync. *What happens?*)

<!--This is the branch where I do crazy stuff like adding an HTML comment.--> 

###Branching:
Git uses branches to let you experiment on new ideas or bug fixes.

1. Create, name, and sync a new 'experimental' branch with the 'fork' button.
2. Make changes, save, and commit them to 'experimental.'
3. Oh wait, no. Emergency, you have to go back to the main (master) branch.
	1. Change a different file or a different part of the same file. Save and commit to master.
	2. Merge the experimental and master branches.
4. I can't quite remember where I was headed with this.











Most experienced users will use Git via the command line. (Terminal on a Mac, the Git Shell that came with the Desktop app, Windows PowerShell, there are a lot of options. They're all where you type commands for your computer to execute.) You can read why [here](http://programmers.stackexchange.com/questions/173297/why-learn-git-when-there-are-gui-apps-for-github). Basically, it's more powerful.
