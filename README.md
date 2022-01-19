# postgresql

### This repository was created with the aim of facilitating work and better understanding a phenomenon called postgress.

# Related repositories

[Global application front-end](https://github.com/markot/postgresql)


# Contributing

When contributing to this repository, please first discuss the change you wish to make via issue with the owners and maintainers of this repository before making a change. 

Please note we have a code of conduct, please follow it in all your interactions with the project.

## Pull Request Process

So you want to submit some changes to the project, awsome! The AGSP project welcomes new contributors. This section will guide you through the contribution process.

### Step 1: Clone

Clone benu-data-sharing-portal-api [from GitHub](https://github.com/edejasoftware/benu-data-sharing-portal-api.git) and checkout your local copy

```
> git clone https://github.com/markot/postgresql/benu-data-sharing-portal-api.git
> cd 
```

### Step 2: Branch

Create a feature branch for your code and start hacking away.

```
> git checkout -b jira-id-my-new-feature -t upstream/dev
```

### Step 3: Commit

**Writing good commit messages is important.** A commit message should describe what changed, why, and reference issues closed (if any).  Follow these guidelines when writing one:

1. The first line should be around 50 characters or less and contain a short description of the change (i.e AGSP-1 Implement user save)
2. Keep the second line blank.
3. Wrap all other lines at 72 columns.

The first line must be meaningful as it's what people see when they run `git shortlog` or `git log --oneline`.

### Step 4: Stay Up To Date

Periodically, you'll want to pull in the latest committed changes. Merge commits and clean-up commits from merges lowers the signal-to-noise ratio of your Pull Request. Rebase helps keep the commits on the branch about just your feature.

```
> git fetch upstream
> git pull --rebase
```

**note**: If a conflict comes up during a rebase, because of the way rebase works your changes will be on the *remote* side of the conflict while the pulled-in commits are the *local* side. This is probably opposite of how you are thinking about it but makes sense since rebase essentially stashes your branch commits, pulls in the new commits from the source, and finally re-applies your commits.  So your commits are now the "new" ones, hence the *remote* side.

### Step 5: Push

You're almost done!  Push the entire branch to your clone

```
> git push origin my-new-feature
```

Go to https://github.com/markot/postgresql , press *Pull Request*, and fill out the form.

Congratulations!

### Other Items of Note

1. Update the README.md with details of changes to the interface, this includes new environment variables, exposed ports, useful file locations.
2. Please submit all pull-requests to the dev branch unless you are working on a formal project, in which case you should submit the pull-request to that project-specific branch.
3. Project maintainers may merge the Pull Request.

## Resources

>Add resources to JIRA, Confluence and specific tickets if needed.

### Prerequisites
    
> Add development prerequisites (.net standard, tools)

## Technology stack

> Describe technology stack

## Folder structure

> Describe folder structure 
