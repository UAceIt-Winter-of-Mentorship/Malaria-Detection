# Contributing Guidelines
This documentation contains a set of guidelines to help you during the contribution process. This will guide you through making a pull request to this Git repository through the command line so that you can contribute to Malaria Detection project. 


## Step 1 : Find an issue

* Take a look at the Existing Issues and comment on it.
* Wait for the Issue to be assigned to you after which you can start working on it.
![issue](https://user-images.githubusercontent.com/53971925/107752938-6d5e4e00-6d45-11eb-8110-f02cc838cf84.png)


## Step 2: Fork the repository

When you’re on the main page for the repository, you’ll see a “Fork” button on your upper right-hand side of the page. With the repository forked, you’re ready to clone it so that you have a local working copy of the code base.
![fork](https://user-images.githubusercontent.com/53971925/107753007-8109b480-6d45-11eb-9273-3442249e0fff.png)

* Clone the repository and add the upstream
```
$ git clone https://github.com/<your-username>/Malaria-Detection

$ cd  Malaria-Detection

$ git remote add upstream https://github.com/UAceIt-Winter-of-Mentorship/Malaria-Detection
```

* If you have already forked the project, update your copy.
```
$ cd Malaria-Detection

$ git remote update

$ git checkout <branch-name>

$ git rebase upstream/<branch-name>

```
## Step 3: Create a new branch
```
$ git checkout-b new-branch
```

## Step 4: Add the files
After adding the all the files/folders in the project folder 
```
$ git add .
```
To check the status
```
$ git status
```

## Step 5 : Commit The changes
```
$ git commit -m "commit msg"
```


## Step 6: Working Remotely
* Now you are ready to your work to the remote repository.
* When your work is ready and complies with the project conventions, upload your changes to your fork:
```
# To push your work to your remote repository
$ git push -u origin Branch_Name
```
This is how your branch looks like:
![branch](https://user-images.githubusercontent.com/53971925/107753062-9383ee00-6d45-11eb-863b-7ea3ce284fda.png)


## Step 7 : Create Pull Request
* Go to your repository and click on compare and pull requests. Then add a title and description to your pull request that explains your contribution.
![pull](https://user-images.githubusercontent.com/53971925/107753096-a7c7eb00-6d45-11eb-9d17-12774ed360a1.png)
![pullrequest](https://user-images.githubusercontent.com/53971925/107753111-ab5b7200-6d45-11eb-8713-c27ee90c7ec9.png)

And your pull request is ready to merge 🥳


# Github Tutorials
* [Git Tutorial](http://think-like-a-git.net/)
* [Git Cheat Sheet](https://sethrobertson.github.io/GitBestPractices/)
* [Create A Pull Request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github)
