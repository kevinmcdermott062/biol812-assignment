## Welcome to my Biol 812 GitHub Pages Assignment 


### 1. When should you use Git for a project?
Anytime you want to ensure you have a back-up of the versions of your code/workand when you want to have multiple people collaborating on a project.

### 2. What kind of files/info should and should not be saved in a Git repository?

A Git repo is really useful to store code for coding projects. Data and any username/pw should never be stored in a Git repo as the repo is public.

### 3. What are the commands to undo a commit?
#### Undo a "public" change
Scenario: You just ran git push, sending your changes to GitHub, now you realize there's a problem with one of those            commits. You'd like to undo that commit.

** Undo with: git revert <SHA>

#### Fix the last commit message
Scenario: You just typo'd the last commit message, you did git commit -m "Fxies bug #42" but before git push you realize        that really should say "Fixes bug #42".

** Undo with: git commit --amend or git commit --amend -m "Fixes bug #42"

#### Undo "local" changes
Scenario: The cat walked across the keyboard and somehow saved the changes, then crashed the editor. You haven't committed those changes, though. You want to undo everything in that file—just go back to the way it looked in the last commit.

** Undo with: git checkout -- <bad filename>
   
### To review all the ways of undoing a commit, see this reference:
   
 [How to undo almost anything with git](https://github.com/blog/2019-how-to-undo-almost-anything-with-git)
 
### 4. One of your repositories is in a detached HEAD state. How do you fix this?

git reset --hard

### 5. Your boss has no idea what Git is or why you are using it. Explain the pros / cons of using Git for your research project. Explain the pros / cons of hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab/etc.
 
 
#### Pros for using Git

* Git is used for version control
* acts as a back up for all your work
* can revert to any previous version for my thesis/code/anaylsis.
* collaborators/PI can make traceable edits 
* edits can be accepted or ignored

#### Cons for Using Git

* all pages and information may be in the public realm
* all code is open to the public
* posting novel information here would be considered pubic disclosure which would void any IP claims.

### 3 - Submit a pull request

Add a link to this webpage by submitting a pull request to this repository [https://github.com/jstaf/biol812-assignment](https://github.com/jstaf/biol812-assignment).


## [This is the link to my Biol812 assignment's webpage on GitHub](https://kevinmcdermott062.github.io/bio812) 

Kevin McDermott
