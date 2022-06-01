# psm-doc
psm git playground


*Welcome PSMs*
#let's do some basic git things

- create an account at http://www.github.com
- go to http://github.com/pljakobs/psm-doc (that's what you're looking at)
- you can use the built in github text editor, to edit textfile.md
	- check out the icon liste above the file box. On the very left, you see a button labeled "main" - that's the branch you're currently viewing.
	- if you click it, you can enter a name into the text field and thereby create a new branch. Do that
	- now, using the same button, you can switch between the existing branches (they might be yours or those created by others)
	- in your newly created branch, select the textfile.txt and click the edit button on the bottom right. Modify the file, enter your commit comment and press "commit" - you've just committed to your branch.
	- if you switch between "main" and your new branch, you will see that textfile.txt is unchanged in "main" but has your new changes in your branch. That's how branches are used: you work on your own change set until you're happy with it, then you bring it back to the main branch. 
	- you will also have noted that there now is a yellow box on top of the github buttons saying that "< your branch > had recent pushes x minutes ago and a big green button [Compare & pull request]" - if you click that button, you're preparing your changes for integratin into the main branch (or any branch you want to configure)
	- when you create a pull request, there's a few things to do:
		- first you will have to decide what to merge with what. That's what you do with the two drop down lists on top of the pull request.
			- "base" is what you have originally branched off of or, more specifically, what you want to integrate with. It could be another intermediate branch, but for our case, it's just main.
			- "compare" should be the branch that you were working on. You want your most recent changes to be reflected in the main branch.
			- github (but not necessarily git, the tool, itself) will be helpful and tell you ahead of time if those two branches can be merged. If you have merge conflicts or for some other reason a merge is not possible, you'll get a warning
		-  next, you're asked for a message, hopefully explaining what you are updating and why. Be specific about your changes, if you're contributing code to a project, make sure that you limit the pull request to what is really important for the specific thing you're doing( for example: if you're adding a feature but, while you're at it, also fix an unrelated bug, do the bugfix in an extra branch with an extra pull request)
	- below your comment field, you'll see the actual diff(s) for the files you've changed with any number of commits. 
		- not every change is automatically reflected in your repository, only those that you commit (either by the commit function in github when editing a text file or using the "git commit" command on your local repo)
	- if you're happy with the changes, go ahead and create the pull request.

