# watch star fork 的简单使用

Day 1

首先学习这三个按钮的使用方法，以及其包含的意思。

watch和star的含义有些接近,基本上都是关注特定的 repo,并获得对象的动态信息。

## watch

> When you watch a repository, you get notifications for any new pull requests and issues that are created, including those not > mentioning you.
> Tip: You will automatically watch any repositories you create or that are created by your team in an organization.

这是官方的解释。大意是被“watch”的项目，其任何改动都会通知到你。

## Star

> Starring a repository allows you to keep track of projects that you find interesting, even if you aren't associated with the project.
> When you star a repository, you're actually performing two distinct actions:

> Creating a bookmark for easier access
> Showing appreciation to the repository maintainer for their work
> Many of GitHub's repository rankings depend on the number of stars a repository has.

相当于给你相中的 repo 添加了一个标签，为以后快速查看这个 repo 提供一个快捷入口。

不过，这些项目的关注度和排行等，也是靠被 star 的数量。

## fork

> A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

> Any user or organization on GitHub can fork a repository. Forking a repository is similar to copying another repository, with two major differences:

> You can use a pull request to suggest changes from your fork to the original repository, also known as the upstream repository.
> You can bring changes from the upstream repository to your local fork by synchronizing your fork with the upstream repository.
> Deleting a fork does not delete the original upstream repository. In fact, you can make any changes you want to your fork--add collaborators, rename files, generate GitHub Pages--with no effect on the original.

这个功能就是把你看中的 repo 复制一份。原作的改动和更新也会通知到你，但你对复制份的改动，不会影响到原作。
可以使用 pull requests 功能与原作者商量，是否能接受你的更改。

## watch和star的区别

Github其实是没有 star 功能的，为了便于大家收藏才在2012年新增了这个功能。

而watch的主要功能就是以一个观察员的身份得到 repo 的任何变动信息通知，若是设置了邮箱还会收到对应的邮件通知。

> Github 推出了新的 Notification 系统，更改了原有的 Watch 机制，为代码库增加了 Star 操作。
Notification 将接收 Watching 代码库的动态，包括：
> * Issues 以及它们的评论
> * Pull Requests 及评论
> * 对任何提交的评论
> 如果没有 Watch 代码库，只有在参与了讨论的情况下会接收到提醒：
> * 被 @ 提及
> * 被分配 Issues
> * 你作为 Author 的新的提交 (git commit --author)
> * 任何在你评论之后的新的讨论
> Notification 将以类似 Gmail 的会话 (Threading) 的形式展现，使用邮件接收会有很好的体验。

若仅仅是想像浏览器收藏夹似的观察别人的项目，star就够了。

对那些自己并不参与的 repo 还是不要轻易 watch ,搞不好会被不断的 notification 给骚扰得体无完肤。


---

## Tips :

1. 写完这个简单的文本后，发现竟然在 Preview changes 里面还是显示代码形态。仔细检查后发现，原来是文件的名称格式不对。加上.md后，终于可以正常预览了。

2. 下一步学习如何给单个文本添加颜色或字体

---
### 文中引用了如下文章的部分内容：

1. Github中Watch 和 Star 的区别 ，http://blog.csdn.net/esther_heesch/article/details/51511187
