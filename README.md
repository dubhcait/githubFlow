# :ocean: git flow :ocean: 

###### tags: `CF`

1. `git pull origin master` or `git clone [repo-url]`

2. `git checkout -b my-new-branch`
     - simultaneously create a new branch and checkout to it :nail_care: 

**work on branch and make changes**

3. `git add [filename(s)]`
    - eg. `git add index.html styles.css`
    - or `git add .` to add all modified files!

4. `git commit -m "a descriptive commit message"`
     - eg. `git commit -m "add label elements and give styling"`

5. `git checkout master`

6. `git pull origin master`
    - get the most recent version of the master branch, as it may well have changed since you last pulled it down!

7. `git checkout my-new-branch`

8. `git merge master`
    - this is where you check that your local branch is up to date with the master
    - there may well be conflicts between the two branches, in which case you can resolve them locally in your editor
    - once conflicts resolved, repeat steps 3-4!

9. `git push origin my-new-branch`

10. Now go and make a pull request! :muscle: 
    - head to the repo on Github
    - make a pull request, comparing `my-new-branch` with base `master`

p.s don't forget to hit `git status` to see which files you've modified, which are staged for committing, and to see which branch you're on! `git branch` will also show you your current branch, as well as any others that are available to you :sunflower: 
