[](public/git-release-branch.drawio.png)
### Working GitHub Flow 
Using Git Flow for better code versioning

## Using git flow

### Creating branches with git flow

> git flow init
>> which branch should be used for bringing forth production realeases?
<br/>    - develop
<br/>    - master
<br/> Branch name for production release: [master]
<br/>
<br/> witch brach should be used integration of the "next release"?
<br/>    - develop
<br/> Branch name for "next release" development: [develop]
<br/> How to name your supporting branch prefixes?
<br/> Feature branches? [feature/]
<br/> Bugfix branches? [bugfix/]
<br/> Hotfix branches? [hotfix/]
<br/> Support branches? [support/]
<br/> Version tag prefix? []
<br/> Hooks and filters directory? [c:/diretory]

### Check existing branches

> git branch -a
>> develop
<br/> * master

### Starting feature branch

> git flow feature start feature_branch
>> Switched to a new branch 'feature/feature_branch'
<br/>
<br/> Summary of actions:
<br/> - A new branch 'feature/feature_branch' was created, based on 'develop'
<br/> - You are now on branch 'feature/feature_branch'
<br/>
<br/> Now, start committing on your feature. When done, use:
<br/>
<br/>git flow feature finish feature_branch

## Recheck branches

> git branch -a
>> develop
<br/>* feature/feature_branch
<br/> master