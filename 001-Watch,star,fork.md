# watch star fork 的简单使用

Day 1,首先学习这三个按钮的使用方法，以及其包含的意思。

watch和star的含义有些接近,基本上都是关注特定的 repo,并获得对象的动态信息。

## watch

> When you watch a repository, you get notifications for any new pull requests and issues that are created, including those not mentioning you.
Tip: You will automatically watch any repositories you create or that are created by your team in an organization.

这是官方的解释。大意是被“watch”的项目，其任何改动都会通知到你。

## Star

>Starring a repository allows you to keep track of projects that you find interesting, even if you aren't associated with the project.

When you star a repository, you're actually performing two distinct actions:

Creating a bookmark for easier access
Showing appreciation to the repository maintainer for their work
Many of GitHub's repository rankings depend on the number of stars a repository has.

即使没有参加这个项目，只要 star了，也会随时获取这些项目的紧张信息。【同watch功能相同】

不过，这些项目的关注度和排行等，也是靠被 star 的数量。

## fork

> A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

Any user or organization on GitHub can fork a repository. Forking a repository is similar to copying another repository, with two major differences:

You can use a pull request to suggest changes from your fork to the original repository, also known as the upstream repository.
You can bring changes from the upstream repository to your local fork by synchronizing your fork with the upstream repository.
Deleting a fork does not delete the original upstream repository. In fact, you can make any changes you want to your fork--add collaborators, rename files, generate GitHub Pages--with no effect on the original.

这个功能就是把你看中的 repo 复制一份。原作的改动和更新也会通知到你，但你对复制份的改动，不会影响到原作。
可以使用 pull requests 功能与原作者商量，是否能接受你的更改。

## Tips

写完这个简单的文本后，发现竟然在 Preview changes 里面还是显示代码形态。

仔细检查后发现，原来是文件的名称格式不对。

加上.md后，终于可以预览了
