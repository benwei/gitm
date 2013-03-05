## Abstract
This is a simple script to archive less keyboard input while using git and git flow.

## Install
* Preparation

```
 git clone git@github.com:benwei/gitm.git
 cd gitm
```

* Method 1 -- using setup script

```
 sh git-macro-setup
```

* Method 2 -- install manually

```
 cp git-m /usr/local/bin/
 chmod +x /usr/local/bin/git-m
```

## guide
* syntax:

```
git m version | <command> [args]

option:
 co <order>   if order is the following one
  default: list branch order 
  0: checkout next release branch 
  n: checkout specific order branch 
```
