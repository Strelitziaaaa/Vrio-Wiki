在文章开始之前，**Vrio Wiki**项目组全体成员十分欢迎您为本项目贡献页面。正因为有了上百位像您一样的人，才有了**Vrio Wiki**的今天！

这篇文章主要叙述参与**Vrio Wiki**编写的写作过程。请您在撰稿或者修正 Wiki 页面之前，仔细阅读以下内容，以帮助您完成更高质量的内容。

## 贡献指南

请您在编辑前查看[ Vrio Wiki 贡献指南]以更好地和社区贡献者进行合作、交流。

##参与协作

???+ warning
    在开始编写一段内容之前，请查阅[Issues]，确认没有别人在做相同的工作后，开个[新 issue]记录编写的内容。

???+ tip
    在 Issue 中也有很多待修复/解决的问题，尤其是我们的迭代计划(Iteration Plan)。从这里获取任务是一个很好的开始！

为保证条目内容的专业性和准确性，我们建议您在编辑前先考虑以下几点：

1. **选择您熟悉的领域**：请优先编辑那些与您的专业知识、学习背景或兴趣爱好相关的条目。这有助于您创作出高质量的内容。
2. **谨慎对待新领域**:如果您对某个主题还处于初学阶段或不太了解，建议您先通过阅读、学习加深理解，待有一定把握后再动手编辑。
3. **查阅相关资料**:为条目添加内容或进行修订时，建议您先查阅权威文献和资料，共同呵护这个知识乐园，用准确、专业的内容去帮助更多读者。期待您的贡献！在这里引用维基百科的一句话：

> 不要害怕编辑，勇于更新页面！[^ref1]

### 在GitHub上编辑

参与**Vrio Wiki**的编写**需要**一个GitHub账号（可以前往[GitHub的账号页面注册](https://github.com/signup)页面注册），无需高超的GitHub技巧，即使你是一名新手，只要按照下面的步骤操作，也能够**非常出色**地完成编辑。

???+ tip
    在你的更改被合并到**Vrio Wiki**的主仓库之前，你对**Vrio Wiki**的内容所作出的修改均不会出现在**Vrio Wiki**的主站上，所以无需担心你的修改会破坏**Vrio Wiki**上正在显示的内容。

    如果需要技巧，可查看[GitHub的官方教程](https://skills.github.com/)。

#### 编辑单个页面内的内容

1.  在 **Vrio Wiki** 上找到对应页面；
2.  点击正文右上方（目录左侧）的 **「编辑此页」**（<i class="md-icon">edit</i>）按钮，在确认您已经阅读了本页面和 [格式手册]后点击按钮根据提示跳转到 GitHub 进行编辑；
3.  在编辑框内编写你想修改的内容。请注意，在修改和接下来的提交过程中，请 **关闭您的自动翻译软件**，因为它可能产生不必要的麻烦（例如您修改的文件有时会被其错误改名，从而影响目录结构）；
4.  编写完成后滚动到页面下方，按照本文中 [commit 信息格式规范](#commit-信息格式规范) 填写 commit 信息，之后点击 **Propose changes** 按钮提交修改。点击按钮后，GitHub 会自动帮你创建一份 **OI Wiki** 仓库的分支，并将你的提交添加到这个分支仓库。
5.  GitHub 会自动跳转到你的分支仓库的页面，此时页面上方会显示一个绿色的 **Create pull request** 按钮，点击后 GitHub 会跳转到一个创建 Pull Request 页面。向下滚动检查自己所作出的修改没有错误后，按照本文中 [Pull Request 信息格式规范](#pull-request-信息格式规范) 一节中的规范书写 Pull Request 信息，然后点击页面上的绿色的 **Create pull request** 按钮创建 Pull Request。
6.  不出意外的话，你的 Pull Request 就顺利提交到仓库，等待管理员审核并合并到主仓库中即可。

在等待合并的时间里，你可以给他人的 Pull Request 提意见、点赞或者点踩。如果有新消息，会在网页右上角出现提示，并附有邮件提醒（取决于个人设置中配置的通知方式）。

#### 编辑多个页面内的内容

如果你需要同时编辑互相无关联的多个页面的内容，请按照上方的 [编辑单个页面内的内容](#编辑单个页面内的内容) 一节一次修改所有页面。

1.  打开 [Vrio-Wiki/Vrio-Wiki](https://github.com/Vrio-Wiki/Vrio-Wiki) 仓库，点击键盘上的<kbd>.</kbd>按钮（或者将 URL 中的 `github.com` 更改为 `github.dev`）[^ref2]，进入 GitHub 的网页版 VS Code 编辑器；
2.  在编辑器中作出对页面源文件的更改，可以使用页面右上方的预览按钮（或按下<kbd>Ctrl+K</kbd><kbd>V</kbd>快捷键）在右侧打开预览界面；
3.  修改完成后使用左侧的 Source Control 选项卡，并按照本文中 [commit 信息格式规范](#commit-信息格式规范) 填写 commit 信息并提交，提交时会提示是否创建此仓库的分支，点击绿色的 **Fork Repository** 按钮即可。
4.  提交后会在网页上方的中央弹出一个提示框，在第一次的提示框内填写标题，第二次的提示框内填写此提交要提交到的仓库内分支名称，之后右下角会弹出一个提示框，内容类似于 `Created Pull Request #1 for Vrio-Wiki/Vrio-Wiki.`，点击蓝字链接即可查看该 Pull Request。

#### 向 Pull Request 追加更改

1.  打开 [Vrio-Wiki 的 Pull Request 列表](https://github.com/Vrio-wiki/Vrio-wiki/pulls)，找到您提交的 Pull Request 并点击。
2.  Pull Request 页面的标题下方将会有一段例如 `<您的ID> wants to merge x commits into Vrio-wiki:master from <您的ID>:patch-1` 的文字，点击 `<您的ID>:patch-1` 部分。
3.  您应该会被重定向到您的分支仓库中，而且文件列表左上角的分支名称是你提交 Pull Request 的分支名称（在本示例中应为 `patch-1`）。
4.  进行您需要的更改。
    -   如果您需要编辑单个文件或多个互相无关联的页面的内容，请直接找到你要的文件并进行更改，更改完成后滚动到页面下方，按照本文中 [commit 信息格式规范](#commit-信息格式规范) 填写 commit 信息，之后点击 **Commit changes** 按钮提交修改。
    -   如果您需要编辑多个文件，点击键盘上的<kbd>.</kbd>按钮（或者将 URL 中的 `github.com` 更改为 `github.dev`）[^ref2]，进入 GitHub 的网页版 VS Code 编辑器并作出更改。然后使用左侧的 Source Control 选项卡，并按照本文中 [commit 信息格式规范](#commit-信息格式规范) 填写 commit 信息并提交修改。
5.  这时你的更改会被自动追加在您的 Pull Request 中。

### 使用 Git 在本地进行编辑

???+ warning
    对于一般用户，我们更推荐使用上方所述的 GitHub 的 Web 编辑器进行编辑。

虽然大多数情况下您可以直接在 GitHub 上进行编辑，但对于一些较为特殊的情况（如需要使用 GPG 签名），我们更推荐使用 Git 在本地进行编辑。

大致流程如下：

1.  将主仓库 Fork 到自己的仓库中；
2.  将 Fork 后的分支仓库克隆（clone）到本地；
3.  在本地进行修改后提交（commit）这些更改；
4.  将这些更改推送（push）到你克隆的分支仓库；
5.  提交 Pull Request 至主仓库。

详细的操作方式可以参考 页面。

### 协作流程

1.  在收到一个新的 Pull Request 之后，GitHub 会给 reviewer 发送邮件；
2.  与此同时，在 [GitHub Actions](https://github.com/Vrio-wiki/Vrio-wiki/actions) 和 [Netlify](https://app.netlify.com/sites/vrio-wiki) 上会运行两组测试，它们会把进度同步在 PR 页面的下方。GitHub Actions 主要用来确认 PR 中内容的修改不会影响到网站构建的进程；Netlify 用来把 PR 中的更新构建出来，方便 reviewer 审核（在测试完成后点击 Details 可以了解更多）；
3.  reviewer 可能会发现问题，并提出 `review` 或 `suggested changes`（建议更改，显示为灰色图标）/`requested changes`（强制更改，显示为红色图标，只会在 reviewer 拥有 repo 写权限时出现）。一般来说，reviewer 也会附上建议和需要进行的更改，在这时，您将会需要继续向 Pull Request 追加其他更改。更改的方法可以参考 `在 GitHub 上编辑` 或者 `使用 Git 在本地进行编辑` 部分的 `向 Pull Request 追加更改` 部分。
4.  在足够多 reviewer 投票通过一个 PR 之后，这个 PR 才可以合并到 master 分支中；
5.  在合并到 master 分支之后，GitHub Actions 会重新构建一遍网站内容，并更新到 gh-pages 分支；
6.  这时服务器才会拉取 gh-pages 分支的更新，并重新部署最新版本的内容。

## 参考资料与注释

[^ref1]: [维基百科：新手入门/编辑](https://zh.wikipedia.org/wiki/Wikipedia:%E6%96%B0%E6%89%8B%E5%85%A5%E9%96%80/%E7%B7%A8%E8%BC%AF)

[^ref2]: [Web-based editor - GitHub Codespaces - GitHub Docs](https://docs.github.com/en/codespaces/developing-in-codespaces/web-based-editor)