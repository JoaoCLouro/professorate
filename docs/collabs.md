# Collaborators guide

This is a guide for collaborators on this project. This includes rules on [what to do as soon as you were added as a contributor](#what-to-do-first), [tips on how to commit properly](#write-proper-commits) as well as how you can contribute to the this project in its current state.

## What to do first 

0. Clone this repository.

```bash
git clone https://github.com/JoaoCLouro/professorate.git
cd professorate
```

1. **Create and switch to your own branch** (no caps).

```bash
git checkout -b joaoclouro
```

2. Make sure **you are always working in your branch**. Finally, push it to remote!
It will contain your personal contributions.

```bash
git push -u origin joaoclouro
```

3. Read the [Guidelines](#guidelines).

## Guidelines

You should **always pull** the code from the branch you are working on before doing anything on your branch.

```bash
git checkout frontend
git pull origin frontend
git checkout <your_branch>
git pull origin <your_branch> && git merge frontend
# Resolve any merge conflicts always
```

### Never push to master

### Write proper commits

See the [Conventional Commits summary guidelines](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#summary) for tips on how to commit!

Please try to follow it as close as possible.

You can also read [this Medium article](https://medium.com/@jafmmd/the-art-of-git-commits-a-developers-guide-to-clear-version-control-4ec638f1d48e) for a concise summary on why and how to commit well.

### Staging changes and committing them

1. Stage your changes by specific files or in general.

```bash
git add <file> # stage only a specific file
git add . # stage everything you added
```
2. Commit them **(make sure you are in your branch!)**

```bash
git commit -m "fix: login for fcul domains working"
```
3. Push to remote

```bash
git push
```

## External contributions

<mark>**In the current state of the project, the team is not open to unknown contributors**</mark>

In the future, if you are part of the `FCUL community`, and you find something you can improve on this project:

* **first open an issue** disclosing what problem/feature you are fixing;
* **secondly make a PR** to be evaluated.

This project will be as much as possible built with frameworks and languages taught at FCUL with this spirit of open contribution by FCUL members in mind.

## AI rules

This project is intended to be used as a learning project. As such, **AI use is extremely limited**.

**ALLOWED**: Looking up documentation, framework and syntax explanations, general questions.
**NOT ALLOWED**: Using AI to write major features, change organization, copy-paste code without understanding it.

**NO AI GENERATED CODE CAN BE SHIPPED**
