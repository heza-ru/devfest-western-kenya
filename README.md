# DevfestWesternKenya
This is a repo for the website of Devfest Western Kenya which is collaboration between GDG Kisii and GDG Kisumu

## To contribute

Fork the this repo then clone from forked repo from your github account 

```bash
$ git clone https://github.com/your_username/devfest-western-kenya.git

```  

or   
```bash
git clone git@github.com:your_username/devfest-western-kenya.git
```



Create a remote repo with name upstream, i.e 

```bash
git remote add upstream https://github.com/GDG-Kisii/devfest-western-kenya.git
```

 or

```bash
$ git remote add upstream git@github.com:GDG-Kisii/devfest-western-kenya.git
```

Before working on an issue, ensure your local repo is up-to-date, by running:

```bash

$ git checkout develop
$ git pull upstream develop
```

When creating a branch, ensure it has an issue number.

For example, issue `#1 create contribution readme` should be in the branch name:

`1-create-contribution-readme`



Then solve any arising issues before pushing up.

Upon making changes push to the `upstream` remote 

```bash
$ git push upstream branchname
```

Your last commit message should be in the form `create contribution readme#fixes1`

Then create a pull request if you feel the issue is completed.
