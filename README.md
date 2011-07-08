## Introduction
It's a script I use to manage my moodle git repository

## Convention
Branch name must match this pattern $sprint_$issueid_$shortname_$upstreambranch
- $sprint is current sprint version, for example s11 means sprint 11
- $issueid is moodle tracker issue key, for instance: MDL-20000
- $shortname is shortname :-) it indicates the topic of this branch
- $upstreambranch is the start point of the branch, it can be master, 20 or 21

## Useage
- gm info -- this will list your git repo, branch name, related branch names and github diff url
- gm update -- update all remote repo, and local branches of upstream, pushing updated branch to github
- gm issue -- print tracker issue url
- gm top -- last commit id
- gm credit -- list all moodle contributors
