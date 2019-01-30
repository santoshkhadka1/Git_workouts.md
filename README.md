#### Create a repo mysource, add some files, clone it locally and then push it to  new repo called mytarget
  * Create a new repo at github.
  * Clone the repo to your local machine.
  * git remote rename origin upstream
  * git remote add origin URL_TO_GITHUB_REPO
  * git push origin master
  * Now you can work with it just like any other github repo. To pull in patches from upstream, simply run git pull upstream master && git push origin master.
