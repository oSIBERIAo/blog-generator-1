---
title: 《git入门》
date: 2018-04-06 18:34:36
tags: git 的基本操作
---
使用Git前，需要先建立一个仓库(repository)。您可以使用一个已经存在的目录作为Git仓库或创建一个空目录。
使用您当前目录作为Git仓库，我们只需使它初始化。
git init
使用我们指定目录作为Git仓库。
git init newrepo
从现在开始，我们将假设您在Git仓库根目录下，除非另有说明。
1.添加新文件
我们有一个仓库，但什么也没有，可以使用add命令添加文件。
git add filename
可以使用add... 继续添加任务文件。
2.提交版本
现在我们已经添加了这些文件，我们希望它们能够真正被保存在Git仓库。
为此，我们将它们提交到仓库。
git commit -m "Adding files"
如果您不使用-m，会出现编辑器来让你写自己的注释信息。
当我们修改了很多文件，而不想每一个都add，想commit自动来提交本地修改，我们可以使用-a标识。
git commit -a -m "Changed some files"
git commit 命令的-a选项可将所有被修改或者已删除的且已经被git管理的文档提交到仓库中。
千万注意，-a不会造成新文件被提交，只能修改。