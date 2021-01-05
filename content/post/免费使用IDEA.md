---
title: 免费获取 JetBrains 全系产品正版 License
date: 2019-10-06
tags: ["jetbrains", "goland", "pycharm", "ops"]
slug: free-use-jetbrains-ide
keywords: ["jetbrains", "goland", "pycharm", "IDE", "免费"]
gitcomment: true
bigimg: [{src: "https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/pexels-photo-2071518.jpeg", desc: "Ship Sailing"}]
category: "ops"
---

要说现在最好用的 IDE 工具，可能除了微软系列的就得算 jetbrains 系列了，几乎支持所有主流的编程语言，可以说是目前最好用的 IDE 工具，比如 IntelliJ IDEA、PyCharm、GoLand、WebStorm，这些 IDE 工具其实平时我都有使用，但是我们也知道这些工具都属于商业产品，价格是非常昂贵的，虽然说这些工具给我们带来的便利远远不是金钱能来衡量的，但是毕竟对于我们大部分个人用户来说还是一笔不小的开支。

<!--more-->

![jetbrains ide price](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-ide-price.png)

不过现在我们完全有机会可以免费获取 jetbrains 的全系产品的正版 License 了，所以不用担心自己越来越扁的钱包💰~~~。

## 申请
要申请获取免费的正版 License，只有一个前提条件，那就是你需要**有自己的开源项目**，不过大家也不用太担心，因为对于项目的内容、star 之类的目前并没有什么硬性要求，比如我就使用的是 《从 Docker 到 Kubernetes 进阶文档》这个开源项目，地址是：[https://github.com/cnych/kubernetes-learning](https://github.com/cnych/kubernetes-learning)，该项目只是 Kubernetes 学习的开源文档手册，并不是什么高深的项目，不过最终我也还是申请到了 License。

### 给项目添加 License
首先在申请之前，我们需要给自己的开源项目添加 License，后面在申请的时候会使用到。在我们的项目 GitHub 页面上点击"Create new file"，然后输入 LICENSE， GitHub 会给我们提供一些 LICENSE 的模板，我们可以根据模板来选择合适的开源 LICENSE，比如我这里就选择的是"Apache License 2.0"协议

![github license](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/github-license.png)

### 填写申请表
直接打开申请地址： [https://www.jetbrains.com/shop/eform/opensource](https://www.jetbrains.com/shop/eform/opensource)，页面上的描述已经非常清楚了。

> jetBrains 可通过提供免费的所有产品 License 来支持您的开源项目，以用于项目的开发。如果您是项目负责人或核心贡献者，请填写以下表格以请求支持。

然后根据我们自己的开源项目填写申请表单即可：

![apply jentbrains license](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-opensource.jpg)

其中有需要注意的几点：

* `Project website`：如果你的开源项目有对应的项目地址，填写即可，如果没有，直接填写 GitHub 主页地址即可
* `License URL`：地址，就是上面我们添加的开源项目的 License 地址，填写上即可
* `No. of required licenses`：申请的 License 数量，基本上就是你的开源项目有效的代码提交人数
* 最后就是邮箱地址一定不要随便填写，因为在申请过程中和申请结束后都是通过邮箱和我们进行沟通的。

填写完成后，直接点击申请即可，一般在一天左右就会有反馈了。由于我的 GitHub 个人页面上面没有显示上面申请的时候填写的邮箱，所以最开始我收到了一封反馈邮件，大概意思就是需要我在 GitHub 页面上面显示我的个人邮箱地址，这样可以证明该仓库确实是和邮箱对应的。

![jentbrains apply feedback](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-apply-feedback.png)

然后我将我填写的邮箱在 GitHub 个人页面上配置显示后，直接回复该邮件即可。第二天就收到了 License 申请成功的邮件了。

![jentbrains get license](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-get-license.png)

邮件信息也很简单，大概意思如下：

> 已批准您的免费 JetBrains 开源许可证申请。**免费订阅有效期为一年**。许可证到期前不久，您将收到一封自动电子邮件提醒。如果您的项目当时仍符合我们的支持计划的要求，请随时申请续订。该 License 只能用于开发非商业性开源项目。请不要将它们用于任何商业目的。然后就是如果你觉得 JetBrains 给了你很大的帮助，希望你可以在你的开源项目上能够带上 JetBrains 的徽标。

## 获取 License
上面的邮件是说我们的申请已经通过了，但是还需要做一些配置才能获得具体的 License，点击邮件中的"Take me to my license(s)"链接即可前往处理，首先需要用我们申请的邮箱注册一个 JetBrains 的帐号：

![jetbrains sign](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/opensource-sign.png)

注册后会发送一封激活邮件，通过激活邮件中的链接可以进入 JetBrains 的个人中心，在个人中心我们就可以看到我们申请的开源项目的申请记录：

![jetbrains usercenter](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-usercenter.png)

点击激活 License，这个时候 License 已经可以使用了。但是还需要将该 License 分配给指定的帐号去使用，点击“Assign”，在弹出的页面中填写前面我们注册的 JetBrains 帐号邮箱，确定后这样 License 就被分配到该帐号下面去了，一封包含了激活码的邮件也会发送到邮件中。

![jetbrains license assign](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-license-assign.png)

现在我们就可以使用申请的免费 License 了，而且是全系的产品都支持的。

![jentbrains product pack](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-pack.png)

比如我们这里来使用 GoLand，在激活页面选择“JetBrains Account”，输入我们的帐号和密码，点击“Activate”激活即可：

![jentbrains license activate](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-license-activate.png)

激活成功就可以正常使用我们的 IDE 了，而且是正版授权的，当然我们还可以为其他的 IDE 进行授权，比如 PyCharm、WebStorm，都是可以激活的。

![jentbrains goland about](https://bxdc-static.oss-cn-beijing.aliyuncs.com/images/jetbrains-about-goland.png)

到这里，我们就完成了 JetBrains 全系产品正版 免费 License 的申请和使用。

<!--adsense-self-->
