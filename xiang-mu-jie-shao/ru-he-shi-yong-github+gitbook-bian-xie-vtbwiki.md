# 如何使用GitHub+Gitbook编写Vtbwiki

### 目录

1. [注册Github](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#zhu-ce-github)
2. [从项目中fork分支](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#cong-xiang-mu-zhong-fork-yi-ge-fen-zhi)
3. [fork分支绑定gitbook](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#fork-fen-zhi-bang-ding-gitbook)
4. [编写文档](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#undefined)
5. [发布fork](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#fa-bu-fork)

#### 注册Github

在座的各位应该都会注册吧

#### 从项目中fork一个分支

在注册完毕GitHub后，在GitHub搜索栏搜索VtbWiki或直接点击[此处](https://github.com/VtbT-Project/VtbWiki)可以看到VtbWiki的源站项目。

![源站项目截图](https://file.pakbi.com/images/wiki/55\(S\_M\)6E1IJ\[\)RC8VLHWGP.png)

点击fork可以以源站当前更新作为模板复制到用户仓库中。

{% hint style="warning" %}
注意：每次更新前应当更新用户仓库的文档，更新方法为点击Fetch upstream即可更新最新版本。
{% endhint %}

至此，fork仓库内容已经结束。

#### fork分支绑定gitbook

* 注册gitbook(~~不写教程了~~)
* 登录gitbook后，我们新建一个文档。
* 新建文档后，我们需要将本文档绑定到我们fork的源站仓库

![新建项目](https://file.pakbi.com/images/wiki/2.png)

![新建项目后得到的项目](https://file.pakbi.com/images/wiki/3.png)

* 点击Sync with Git，绑定你的github账号和仓库并从仓库中获取最新版本wiki

![绑定Github](https://file.pakbi.com/images/wiki/4.png)

![绑定仓库](https://file.pakbi.com/images/wiki/5.png)

![绑定github](https://file.pakbi.com/images/wiki/6.png)

点击install，在github安装授权

![选择安装授权的仓库](https://file.pakbi.com/images/wiki/7.png)

在这里选择你要安装授权的仓库，选择你fork到的团队组织或自己就好。

安装好后会在选择仓库页面看到你的用户

![选择你绑定的账号](https://file.pakbi.com/images/wiki/8.png)

接下来绑定文档所在仓库即可

![绑定仓库](https://file.pakbi.com/images/wiki/9.png)

选择分支中选择mian即可

![绑定仓库分支](https://file.pakbi.com/images/wiki/10.png)

接下来会让你获取选择方式，我们选择默认即可。

![选择获取方式](https://file.pakbi.com/images/wiki/11.png)

点击Synchronize后，gitbook会自动从GitHub仓库中获取文档 ，我们耐心等待即可，大概1-5分钟。

![Gitbook获取文档中](https://file.pakbi.com/images/wiki/13.png)

![Gitbook成功获取文档](https://file.pakbi.com/images/wiki/14.png)

到此，稳定获取就已经完成了。

#### 如何编写文档

在你获取文档后，点击EDIT即可编辑

GItbook使用的是Markdown语法，也有npm版本（但年久失修不推荐使用）

我们强烈推荐你使用GitbookWeb进行编辑文档的操作，它更方便上手。

在你编写完毕后点击merge即可发布到你的github仓库内！

#### 发布fork

待定123123123123



#### 文档更新

在我们后期编辑文档时，文档版本不同步会导致我们无法获取最新的文档

我们在[fork](ru-he-shi-yong-github+gitbook-bian-xie-vtbwiki.md#cong-xiang-mu-zhong-fork-yi-ge-fen-zhi)中提到过，如果要获取最新文档我们需要更新我们的仓库

在更新好你的仓库后，我们回到gitbook更新我们gitbook文档

点击synced->congifuration后，点击Synchronize从仓库更新最新版本即可。

![更新Gitbook](https://file.pakbi.com/images/wiki/15.png)

![更新等待](https://file.pakbi.com/images/wiki/16.png)
