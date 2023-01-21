<h1 align="center"><code>sn-ru-2/l1/r1</code></h1>
<h2 align="center"><i> Rust Working branch to be merged with sniffo </i></h2>

----
1. [What ?](#what-)
2. [`g.sh` is `glq` - Auto Push](#gsh-is-glq---auto-push)
3. [Tags](#tags)
   1. [Show All Tags](#show-all-tags)
   2. [Add Tag](#add-tag)
   3. [See One specific tag](#see-one-specific-tag)
   4. [Push Tag](#push-tag)

----

# What ?

1. This is the branch where you will do all your actual work 
2. Make sure to use some different file names to avoid merge conflicts later one 

# `g.sh` is `glq` - Auto Push

1. This is going to be the name of this orphan branch 

New auto push file

```sh 
#!/bin/bash 
git add .
git commit -m "🃏🦀 - lq/r1(orphan) work"
git push 
git branch -a 
```

# Tags 

1. This is the shit you use for setting up releases 
2. Commands are like this 


## Show All Tags

Show all tags 
```sh 
git tag 
```
## Add Tag 

add tag to the current branch 
```sh 
git tag int.int.int 
```
## See One specific tag
- This will show you the contents 

see one tag 
```sh
git show int.int.int
```

## Push Tag 

type to push tag 
```sh 
git push origin <tag>
```


