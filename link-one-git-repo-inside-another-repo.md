# Link one git repo inside another git repo! 
## The Solution is ```submodules``` 

Submodule are different git repositories under the same root. This way you can manage 2 different project at folder level inside the root repository. Submodules allow foreign repositories to be embedded within a dedicated subdirectory of the source tree, always pointed at a particular commit.

```git submodule```
Break your big project to sub projects as you did so far.

Now add each sub project to you main project using :
```git submodule add <url>```

Once the project is added to your repo, you have to init and update it.
```git submodule init```
```git submodule update```

As of Git 1.8.2 new option --remote was added

```git submodule update --remote --merge```
will fetch the latest changes from upstream in each submodule, merge them in, and check out the latest revision of the submodule.

As the docs describe it:
```--remote```

This option is only valid for the update command. Instead of using the superproject’s recorded SHA-1 to update the submodule, use the status of the submodule’s remote-tracking branch.
This is equivalent to running git pull in each submodule.
However, how would I push a commit in the scenario of bug fix in C which affects the code shared with the parent layers?
Again: using submodule will place your code inside your main project as part of its content. The difference between having it locally inside the folder or having it as part of a submodule is that in submodule the content is managed (commited) to a different standalone repository.

** git subtree **
Git subtree allows you to insert any repository as a sub-directory of another one
Very similar to submodule but the main difference is where your code is managed. In submodules the content is placed inside a separate repo and is managed there which allow you to clone it to many other repos as well.
subtree is managing the content as part of the root project and not in a separate project.
Instead of writing down how to set it up and to understand how to use it you can simply read this excellent post which will explain it all.
https://developer.atlassian.com/blog/2015/05/the-power-of-git-subtree/
