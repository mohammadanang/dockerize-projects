# Create a Dockerize Project

Create a project that have been dockerized. All programming language are welcome. See the example project inside **src** folder named `express-basic`.

## Contribution Rules

- Do `NOT` add any build steps e.g npm install (we want to keep this a simple static site).
- Do `NOT` remove other content.
- Styling/code should be pretty.
- Try to keep pull requests small to minimize merge conflicts.
- The workspace is inside **src** folder.

## Getting Started

- Fork this repo (button on top)
- Clone on your local machine

```shell
git clone https://github.com/<your-github-username>/dockerize-projects.git
```

- Navigate to project directory

```shell
cd dockerize-projects
```

- Add your projects directory into **src** directory
- Add all your file changes

```shell
git add .
```

- Commit your changes.

```shell
git commit -m "Relevant message"
```

- Then push

```shell
git push origin <your-branch>
```

- Create a new pull request from your forked repository

## Avoid Conflicts (Syncing your fork)

An easy way to avoid conflicts is to add an `upstream` for your git repo, as other PR's may be merged while you're working on your branch/fork.

```shell
git remote add upstream https://github.com/mohammadanang/dockerize-projects.git
```

You can verify that the new remote has been added by typing

```shell
git remote -v
```

To pull any new changes from your parent repo simply run

```shell
git merge upstream/master
```

or

```shell
git pull upstream master
```

This will give you any eventual conflicts and allow you to easily solve them in your repo. It is a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
