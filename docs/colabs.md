# Colaborators guide

This is a guide for colaborators on this project. This include rules on [what to do as soon as you were added as a contributer](#What-to-do-when-first), [tips on how to commit properly](#Tips-on-how-to-write-proper-commits) and more.

## What to do when first 

When you first join, **please create your own branch** (no caps).

```bash
git branch -b joaoclouro
```

You should **always pull** your code from the branch you work on before doing anything on your branch
```bash
git checkout frontend
git pull
git checkout <your_branch>
git pull && git merge frontend
# Resolve any merge conflicts always
```

**NEVER PUSH TO MAIN**

## Tips on how to write proper commits

This is a [link](https://www.conventionalcommits.org/en/v1.0.0-beta.2/#summary) for tips on how to commit!
Please try to follow it as close as possible.
