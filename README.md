[](public/git-release-branch.drawio.png)
### Working GitHub Flow 
Using Git Flow for better code versioning

## Using git flow

### Creating branches with git flow

    > git flow init
        which branch should be used for bringing forth production realeases?
            - develop
            - master
        Branch name for production release: [master]

        witch brach should be used integration of the "next release"?
           - develop
        Branch name for "next release" development: [develop]
        How to name your supporting branch prefixes?
        Feature branches? [feature/]
        Bugfix branches? [bugfix/]
        Hotfix branches? [hotfix/]
        Support branches? [support/]
        Version tag prefix? []
        Hooks and filters directory? [c:/diretory]

### Check existing branches

    > git branch -a
        develop
        * master

### Starting feature branch

    > git flow feature start feature_branch
    Switched to a new branch 'feature/feature_branch'

    Summary of actions:
        - A new branch 'feature/feature_branch' was created, based on 'develop'
        - You are now on branch 'feature/feature_branch'

    Now, start committing on your feature. When done, use:

    git flow feature finish feature_branch

## Recheck branches

    > git branch -a
        develop
        * feature/feature_branch
        master