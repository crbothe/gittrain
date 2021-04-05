# Minimum/basic steps for using _git_
First make sure you have _git_ install on your machine.

## Create your repository on GitHub.com 
Navigate to "Repositories" and click "New"

Enter "Repository name" and click "Create repository" withoud clicking on any other options.
You will see some information provided to get started with your first commit. 

Pay close attection to "Quick setup..." instructions. 


## Get repository on machine:

Clone your repository : 

```git clone https://github.com/crbothe/gittrain.git```

## Pull or update your git repository according to cloud repo
If you already have a local rpository on your machine and you made changes in cloud perhaps via another machine: 

```git pull```



## Pushing files to the cloud:

Before you _push_, always check _status_:

```git status```

If you added new files:

For all files to be added:
```git add . ```

only one specific file:
```git add <file_name> ```

Commit the changes:

```git commit -m "msg" ```

Now time to _push_:

```git push```

