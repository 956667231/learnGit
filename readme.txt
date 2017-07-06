Git is a distributed version control system.
Git is a free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

Creating a new branch is quick $ simple.
dong xuan 666 !!!
add deb

the seconde stash.

add file happy.py

add branch dev




出现错误：

fatal: git checkout: updating paths is incompatible with switching branches.
Did you intend to checkout 'origin/remote-name' which can not be resolved as commit?

解决办法：

git remote show origin

git remote update

git fetch

git checkout -b local-name origin/remote-name


啊啊啊

