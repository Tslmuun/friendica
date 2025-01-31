交友
==============

* [主页](help)

在 Friendica 中，友谊有时可能意味着不同的含义。但是让我们保持简单；你想和某个人成为朋友。你该怎么做？

目录
---
Friendica 有两种不同类型的“通讯录”。一个是你所注册的 Friendica 服务器的目录，另一个是全局目录，其中包括你和其他 Friendica 服务器提交的帐户信息。

你可以做的第一件事就是查看 **目录**。目录分为两部分。如果你点击目录按钮，你将看到你所在服务器上所有选择列出的成员列表。

你还将看到一个指向 **全局目录** 的链接。全球有几个全局目录定期互相交换信息。你所看到的特定全局目录通常取决于你的服务器所在位置。如果你点击全局目录，你会看到 Friendica 所有实例上选择列出的所有人的列表。你还将看到一个“显示社区论坛”的链接，它将引导你进入群组、论坛和粉丝页面。你可以用相同的方式连接到人、群组和论坛，但群组和论坛将自动接受你的介绍请求，而人类将手动批准你。

与其他 Friendica 用户连接
---

访问他们的个人资料。在他们的个人资料图片下面，将出现“连接”这个单词（我们假设这是一个英语语言个人资料）。点击那个“连接”按钮，它会带你进入一个“连接”表格。

表格将要求你提供你的身份地址。这是必要的，以便这个人的网站可以找到你的网站。

如果你的 Friendica 网站叫做“demo.friendica.com”，而你在该网站上的用户名/昵称是“bob”，那么你在这个表格中应该填写“bob@demo.friendica.com”。

请注意，这看起来就像一个电子邮件地址。它就是要那样的。这样人们就很容易记住了。

你还可以输入你的“主页”的 URL，例如“http://demo.friendica.com/profile/bob”，而不是电子邮件样式的地址。

当你提交连接页面后，它会带你回到你自己的网站，在那里你必须登录（如有必要）并验证 *你* 网站上的连接请求。一旦你完成了这个过程（在你的新朋友批准请求后），两个网站就可以相互通信以完成整个过程。

如果你已经知道某人的身份地址，你可以在你的“联系人”页面的“连接”框中输入它。这将带你进行类似的过程。

连接到其他网络的用户
---

### 联邦和 Fedivese 中的连接
你也可以使用你的身份地址或其他人的身份地址，在所谓的开源社交媒体联邦/Fedivese 中与朋友建立联系。目前，Friendica 支持与 diaspora*、Red、Hubzilla、GNU Social、StatusNet、Mastodon、Pleroma、socialhome 和 ganggo 平台上的人建立联系。

如果你在 gnusocial.net（一个 GNU Social 站点）认识“alice”，你可以将 alice@gnusocial.net 放入你的联系人页面并跨网络成为朋友。如果你愿意，你也可以把 Alice 的 gnusocial.net 页面的 URL 放进去。

注意：某些版本的 GNU Social 软件可能需要你的个人资料的完整 URL，并且可能无法使用身份地址。

这些网络上的人也可以通过知道你的联系方式与你联系。

### 其他社交媒体
如果您的服务器支持此功能，您还可以在Twitter或Tumblr、Wordpress等许多重要来源中连接其他人。

要进行连接，请在“联系人”页面的“连接”框中输入其联系方式。

### 电子邮件
如果您已在“设置”页面上提供了您的邮箱连接信息，您可以输入任何曾给您发送过邮件的人的电子邮件地址，并在您的社交流中显示他们的电子邮件消息。
您还可以在Friendica内回复他们。

创建一个与Alice的Gmail邮件联系人，将其电子邮件以以下格式输入“mailto:alice@gmail.no”。
为了避免滥用或垃圾邮件，您必须拥有来自Alice正确电子邮件地址的电子邮件在您的收件箱中。

订阅邮件列表的方法与此类似，但不使用“mailto:”前缀。
要订阅邮件列表，请以以下格式输入电子邮件“mailling-list@list-server.net”。

### 发布源
您可以“关注”几乎任何一个或任何一个产生发布源（RSS / Atom等）的网站。
如果我们能找到信息流和名称并将其附加到联系人上，我们将尝试与他们建立联系。

通知
---
当有人请求添加您为好友时，您将收到通知。
通常，您需要在批准好友请求之前进行同意。

批准
---
某些网络允许人们发送消息给您，而不需要成为好友或经过您的批准。
Friendica默认情况下不允许此操作，因为这将打开垃圾邮件的通道。

单向或双向好友关系
---
当您收到另一个Friendica成员的好友请求通知时，您可以选择将其作为“关注者”或“好友”添加。
如果他们是关注者，他们可以看到您发布的所有信息，包括您发送给他们的私人通信，但反之则不行。
如果是好友，则可以相互交流。

Diaspora*使用不同的术语，您可以选择允许他们“与您共享”或成为完整的好友。

忽略、阻止和删除联系人
---
一旦成为好友，如果您发现该人不断向您发送垃圾邮件或无用信息，您可以“忽略”他们——而不会断掉好友关系或告诉他们您对他们的言论不感兴趣。
在许多方面，他们就像“关注者”——但他们并不知道这一点。
他们认为自己是您的好友。

您还可以“阻止”某个人。
这将完全阻止与该人的通信。
他们仍然可能能够看到您的公共帖子，就像全世界的任何人一样，但他们无法直接与您沟通。

您还可以删除好友，无论好友关系的状态如何——这将完全从您的网站中删除与该人相关的所有内容。
