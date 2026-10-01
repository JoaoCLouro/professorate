# Collaborators guide

This is a guide for collaborators on this project. This include rules on [what to do as soon as you were added as a contributor](#what-to-do-first), [tips on how to commit properly](#tips-on-how-to-write-proper-commits) as well as how can contribute to the current state of this project.

## What to do first 

When you first join, **please create your own branch** (no caps).

```bash
git branch -b joaoclouro
```

### Guide Lines

You should **always pull** your code from the branch you work on before doing anything on your branch

```bash
git checkout origin frontend
git pull origin frontend
git checkout origin <your_branch>
git pull origin <your_branch> && git merge frontend
# Resolve any merge conflicts always
```

### Never push to master

## Tips on how to write proper commits

See the [Conventional Commits summary guidelines](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#summary) for tips on how to commit!
Please try to follow it as close as possible.

## External contributions

<mark>**In the current state of the project, the team is not open to unknown contributors**</mark>

In the future, if you are part of the `FCUL community`, if you find something you can improve on this project:

* **first open an Issue** disclosing what problem/feature you are fixing;
* **secondly make a PR** to be evaluated.

This project will be as much as possible built with frameworks and languages taught at FCUL with this spirit of open contribution by FCUL members in mind.


## AI rules
This project is intended to be used as a learning project. In this way, **NO AI IS ALLOWED** for majo features.

You can use it to search markdown syntax or even specific framework explanations, but **NO AI GENERATED CODE CAN BE SHIPPED**
