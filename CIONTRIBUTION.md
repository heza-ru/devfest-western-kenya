# Contributing to devfest-western-kenya

We are happy you want to contribute to the devfest-western-kenya codebase.Your ideas and help are very much welcome.

## Getting Started

This describes how to contribute to devfest-western-kenya:  the tools we use to track and
coordinate the work that is happening and that needs to happen. This also describes the
*workflow* -- the processes and sequences for getting contributions merged into the project in an organized and coherent way.

We keep our code on [GitHub](http://github.com) and use [git](https://git-scm.com) for version control.


## General Steps


### 1. Cloning the application

Fork the application from [devfest-western-kenya](https://github.com/GDG-Kisii/devfest-western-kenya).Then clone  your forked repository.

### 2. Look at what needs to be done on:

* [Pick an Issue](https://github.com/orgs/GDG-Kisii/projects/1) - On the TO DO column pick an issue and start working on it

* Review [open PRs](https://github.com/GDG-Kisii/devfest-western-kenya/pulls) on GitHub - leave comments or collaborate if interested.

## GitHub and git

Our **default working branch is `main`**.  We do work by creating branches off `main` for new features and bugfixes.

Any *feature* should include appropriate  tests.

A *bugfix* may include a unit test depending on where the bug occurred, but fixing a bug should start with the creation of a test that replicates the bug, so that any bugfix submission will include an appropriate test as well as the fix itself.

You should  work with a fork that is:

clone from your forked repository like so:

 ```bash
 git clone https://github.com/your_username/devfest-western-kenya.git
 ```  

or

```bash
git clone git@github.com:your_username/devfest-western-kenya.git
```

Ensure you have two remotes that is `upstream` for the main repo  and  `origin`for your forked repo(you can name the way you wish) like so:

```bash
git remote add upstream git@github.com:GDG-Kisii/devfest-western-kenya.git
```

 or

```bash
git remote add upstream https://github.com/GDG-Kisii/devfest-western-kenya.git
```

You can check that you have the two remotes like so:

```bash
git remote -v
```

Before starting work on a new feature or bugfix, please ensure you have [synced your fork to upstream/main](https://help.github.com/articles/syncing-a-fork/):

```bash
 git pull upstream main
```

Note that you should be re-syncing as frequently as possible on your
feature/bugfix branch to ensure that you are always building on top of very latest main code.

### Pull Requests, committing and branch naming

When creating a branch, ensure it has an issue number, this number should the issue id assigned to the issue you are working on

```bash
git checkout -b 1-add-contributing_md
```

Please ensure that each commit in your pull request makes a single coherent change and that the overall pull request only includes commits related to the specific GitHub issue that the pull request is addressing.  This helps the project managers understand the PRs and merge them more quickly.

```bash
This add contribution.md to the project
fixes #1
```

Your PR can either be a [draft](https://github.blog/2019-02-14-introducing-draft-pull-requests/) or [Ready for Review](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/changing-the-stage-of-a-pull-request).

Draft means you still work in progress and do not require merging. In other words, it can be reviewed to offer assistance or suggestion but not merged

Ready for Review means the PR should be reviewed with intent of merging therefore if finally approved by project manager it will be merged.

#### Pull Request Review

The contributors will review the pull request for coherence with the specified feature or bug fix, and give feedback on code quality, user experience, documentation and git style.  Please respond to comments from the project managers with explanation, or further commits to your pull request in order to get merged in as quickly as possible.
