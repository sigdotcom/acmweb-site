# ACM Web Site

## Getting Started

Open a terminal and run the following commands.

```
git clone https://github.com/sigdotcom/acmweb-site
cd acmweb-site
npm i
```

These will make a local copy of this repository on your machine and install all of its dependencies. You can now open up the `acmweb-site` folder in your favorite code editor. This folder is where you'll run all of the following commands.

Next, run the command `npm start`. This will start up a preview website that refreshes any time you make changes. Do this any time you want to start working on this project.

## Git Basics

Git is a version control system that allows you to work on an individual feature without affecting the main codebase. It does this through branches.

To create and switch to a new branch, run the following commands.

```
git checkout -b my-branch
git push -u origin my-branch
```

You are now working off of the branch `my-branch`. This is where you'll work on your feature until it's finished.

To send your changes back to this remote repository for others to see, run the following commands.

```
git add .
git commit -m "My changes"
git push
```

These will add and commit your changes locally, then send those changes to the corresponding branch here.

For more practice, a git tutorial is located [here](https://learngitbranching.js.org/?locale=en_US).
