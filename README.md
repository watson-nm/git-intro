


# UVA workshop!

```diff
-Last updated 11-Feb-2021
```

> <em>Fork edits</em>

# git-intro


> <em>Changes made here. More changes.</em>

UVA Library Workshop on Introduction to Version Control and Git/Github


## About Me
* Erich Purpur: I am a Research Librarian for Science & Engineering in the Brown Science & Engineering Library. I've been at UVA for about 3.5 years

## Data Resources in the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)

## First, our goals

1. Learn the background of version control
2. Everyone has a GitHub account
3. Create and fork a repository
4. Feel comfortable with git/github workflows
5. Know how to get help

## Second, some terms

* git - version control software installed on your local machine
* GitHub - a for profit company owned by Microsoft. It provides cloud-based hosting of repositories.
* GitLab - an alternative to GitHub, not owned by Microsoft ([why you might want to switch](https://about.gitlab.com/2017/07/19/git-wars-switching-to-gitlab/)). "Free software deserves free tools."
* repository (repo) - Basic unit in git: a record of all changes to specified files.
* fork - personal copy of another users repo.
* branch - a parallel version of a repo (main branch is called "main", formerly "master").

[Git Glossary](https://help.github.com/en/articles/github-glossary)

You can look at GitHub's [Git Handbook](https://guides.github.com/introduction/git-handbook/)

## Outline

0. Some background
1. Work on the GitHub browser interface
2. Look at the GitHub Desktop interface
3. Tips on getting help

## Reference for Git

The book <em>Computing Skills for Biologists: A Toolbox</em> contains a useful introduction to Git with practice data and code. Members of the UVA community can access the book [online](http://proxy01.its.virginia.edu/login?url=http://www.degruyter.com/isbn/9780691183961). 
The examples, data, code, and solutions are hosted on a [github repo](https://github.com/CSB-book/CSB]https://github.com/CSB-book/CSB).

### A brief history of Version Control

* SVN (2000s) Centralized (client-server)
![Central Version Control](data:image/png;base64,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)


* git (2005) Distributed. Developed by [Linus Torvalds](https://en.wikipedia.org/wiki/Linus_Torvalds) for Linux development.


## Things to have before we begin

* Github account: https://github.com/
   -Create a free account if you don't have one yet
* A text editor or IDE. If you don't already have one, you can use something very simple like Notepad++: https://notepad-plus-plus.org/
   -R studio
   -Anaconda/Spyder
   -Visual Studio Code
   -Any plain text editor
* Git
  -For Windows: https://www.youtube.com/watch?v=albr1o7Z1nw (watch first 2:45)
  -For Mac: Git is usually installed by default but just in case: https://www.youtube.com/watch?v=sJ4zr0a4GAs


# Let's Get Started!

We will be using the git command line tool for this workshop. There are also GUI (graphical user interface) tools available, but version control is generally done at the command line. There is a limit to what the GUI tools can do and eventually you'll run into those barriers. Once you get used to it, the command line is the way to go.

If you are using Windows, open the git client. If you are on a Mac, open the terminal.

```
test
```
test















### Using Github
### Step 0 - Inspect this Current Repo
* In a web browser, visit this repo: [https://github.com/rjp0i/git-intro](https://github.com/rjp0i/git-intro)
* We are in the github interface:
  1. upper left corner: notebook icon next to rjp0i/git-intro  (a repo)
  2. big green button on the right hand side (down a little) says "Clone or Download" (how to get the files)
  3. list of files (how to browse the files)
  4. readme.md is rendered as Markdown (github automatically shows the readme file, very handy)
  
### Step 1 - Create your own Repo 
[https://guides.github.com/activities/hello-world/#repository](https://guides.github.com/activities/hello-world/#repository)
* Not so obvious, but in the upper right hand corner, click the '+' button, pull down: select 'new repository'
  1. name (this will be the address of the repo...)
  2. description
  3. public v private
  4. initialize with readme (alway say yes)
  5. license
  
### Step 2 - Create a Branch (for Direct Collaborators)
[https://guides.github.com/activities/hello-world/#branch](https://guides.github.com/activities/hello-world/#branch)
* Let's leave the master branch alone and create a new branch
 1. Click the drop down at the top of the file list that says branch: master.
 2. Type a branch name, readme-edits, into the new branch text box.
 3. Select the blue Create branch box or just hit “Enter” on your keyboard.

Now we have two branches: master and readme-edits

### Step 3 - Edit a File and Commit Changes
[https://guides.github.com/activities/hello-world/#commit](https://guides.github.com/activities/hello-world/#commit)
* You should now be in the readme-edits branch.
* Click on README.md in the list and then click the pencil to edit the file
  1. now type in the editor
  2. when done click green button at bottom 'commit changes'
    * commits can/should(?) be done early and often
    * no change is too small to commit, but you'll get a feel for how often you should commit after some time
    * but always write a commit message that describes your changes
    
* Now the master and readme-edits branches differ
    
### Step 4 - Making Pull Requests
[https://guides.github.com/activities/hello-world/#pr](https://guides.github.com/activities/hello-world/#pr)
* Indirect Collaboration - pull requests
  1. Click the "Pull Request" tab, then "New pull request" ![alt text](https://guides.github.com/activities/hello-world/pr-tab.gif "Pull Step 1")
  2. In the Example Comparisons box, select the branch you made, readme-edits, to compare with master (the original).![alt text](https://guides.github.com/activities/hello-world/pick-branch.png "Pull Step 2")
  3. Proofread your changes in the diffs on the Compare page ![alt text](https://guides.github.com/activities/hello-world/diff.png "Pull Step 3")
  4. When ready to submit, click the Create Pull Request Button ![alt text](https://guides.github.com/activities/hello-world/create-pr.png "Pull Step 4")
  5. Write a title and a brief description of your changes ![alt text](https://guides.github.com/activities/hello-world/pr-form.png "Pull Step 5")
  6. Click Create Pull Request
  
  ### Step 5 - Merging Pull Requests
  [https://guides.github.com/activities/hello-world/#merge](https://guides.github.com/activities/hello-world/#merge)
  * Now, let's merge the Pull Request, to bring the changes from readme-edits into the master branch.
  1. Click the green Merge pull request button to merge the changes into master.
    ![alt text](https://guides.github.com/activities/hello-world/merge-button.png "Merge Step 1")
  2. Click Confirm merge.
  3. Now we can delete the readme-edits branch, since its changes have been incorporated into master. You'll be prompted to do so inside the purple box. 
  ![alt text](https://guides.github.com/activities/hello-world/delete-button.png "Merge Step 2")
  
  ### Step 5.1 - Resolving Conflicts when Merging Pull Requests
  [https://help.github.com/en/articles/resolving-a-merge-conflict-on-github](https://help.github.com/en/articles/resolving-a-merge-conflict-on-github)
  * Any time a merge is attempted when changes have been made to both versions of the same line of a file (in the master and in a fork, say), then you will have to resolve the conflicts in the merge.
  * Often, you can just use the github interface to do this. If this is the case (i.e., the conflict isn't too complex), a Resolve Conflicts button will appear (and not be greyed-out). 
  ![alt text](https://help.github.com/assets/images/help/pull_requests/resolve-merge-conflicts-button.png "Conflicts Step 1")
  * Clicking on "Resolve Conflicts" will show you the conflict and use symbols to indicate the location of the conflict (`<<<<<<<branch1-name`, `=======`, `>>>>>>>branch2-name`), and the two versions of the conflicting line. 
  ![alt_text](https://help.github.com/assets/images/help/pull_requests/view-merge-conflict-with-markers.png "Conflicts Step 2")
  * Choose the correct version of the line (or edit one version), then remove the other version and remove the symbols and the branch/fork names, <em>leaving only the text you want in the final version</em>.
  * Resolve any other marked conflicts in the file.
  * Click on Mark as Resolved.
  ![alt_text](https://help.github.com/assets/images/help/pull_requests/mark-as-resolved-button.png "Conflicts Step 3")
  * Resolve conflicts in any other files.
  * Click on Commit Merge (and click on the I understand pop-up).
  ![alt_text](https://help.github.com/assets/images/help/pull_requests/merge-conflict-commit-changes.png "Conflicts Step 4")
  * Finally, click on Merge Pull Request, and then confirm the merge.



### GitHub Flow
[https://guides.github.com/introduction/flow/](https://guides.github.com/introduction/flow/)


### Forks - Indirect Collaboration
  If you are not a collaborator in a repo, you can't branch that repo. However, you can "fork" it, which is just creates a clone of the repo on the GitHub server.
  1. You can't push changes directly back to the original repo.
  2. You'll want to work on keeping your fork in sync with the project
      * add it to the original project as a remote, or
      * fetching regularly from the original repo
    
  Try forking from my repo, and make changes to the resulting fork, and then submit a pull request to me!
  
 
### Additional Items
  * Command Line Interface (CLI) [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)
  * [Create your own Webpage](https://pages.github.com/) (such as https://rjp0i.github.io/intro.html)


## Getting Help

* Please, feel free to email me: ricky@virginia.edu
* The book <em>Computing Skills for Biologists: A Toolbox</em> contains a very useful introduction to Git, with practice data and code. Members of the UVA community can access the book [online](http://proxy01.its.virginia.edu/login?url=http://www.degruyter.com/isbn/9780691183961)
  * The examples, data, code and solutions are hosted on a [github repo](https://github.com/CSB-book/CSB](https://github.com)/CSB-book/CSB)
* Lots of [git](https://git-scm.com/)/[GitHub](https://guides.github.com/)/[GitLab](https://gitlab.com/help?nav_source=navbar) resources from the source, as well as free training through a number of github sites
* StackOverflow is another good resource (e.g., for questions concerning git (or GitHub/GitLab): [https://stackoverflow.com/questions/tagged/git](https://stackoverflow.com/questions/tagged/git)

## How to compare revisions
* use the following style of URL with two commit hashes (Rev A and Rev B)
  * of the form: github.com/$USER/$REPO/compare/$REV_A...$REV_B
* $REV_A and B are the commit hashes for the versions you want to compare. You can get these by examining the Commit history of a file on Github

# Ways to Practice
1. Write some code, or some text
2. Do the version control in github
3. Edit it yourself
4. Have a friend do some edits as well

> <em># This is an additional edit for practice.
Hopefully this works </em>
