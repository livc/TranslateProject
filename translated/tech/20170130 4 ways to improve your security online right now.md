立刻提高在线安全的四种方法
============================================================

 ![4 ways to improve your security online right now](https://opensource.com/sites/default/files/styles/image-full-size/public/images/business/rh_003601_05_mech_osyearbook2016_security_cc.png?itok=VNmpz6K- "4 ways to improve your security online right now") 
图片提供 : Opensource.com

过去几年来，关于数字安全漏洞和个人隐私问题的报告频繁出现，毫无疑问，这一趋势仍将继续。我们听说诈骗者转移到社交媒体，国家使用网络攻击作为协调进攻策略的一部分，以及追踪我们的在线行为的公司的兴起。

对这些事件冷漠对待非常容易，但是你可以做很多事情来提高你的在线安全，这样当你被安全事件所困扰时，你可以减少对自己的风险，并快速保护自己免受进一步的损失。安全意识非常容易学习，并且许多开源项目可以帮助你。

安全的重点不是将你的计算机变成一个虚拟的 Fort Knox，而是为了使别人访问你的数据足够困难，这样攻击者将转移到其他更容易的目标。

### 使用密码管理器

在一个几乎每个网站都要求用户名和密码的世界里，大多数人都因密码而疲惫不堪，并且开发了复杂的系统来创建和记住用户名和密码（或者已经完全放弃，只是使用相同的用户名和密码）。密码管理器是这个问题的解决方案，我还不知道不使用密码管理器的专业安全人员。此外，它们非常容易设置和使用。

对于以前没有使用过的人来说，密码管理器是一种软件，它就像一个数字保险库的信息，存储在加密的环境中。你创建的主密码是一个单一的强密码，用于保护用户名和密码集合的文件库。通常，当你连接到已知网站，密码管理器会自动输入存储的密码，生成强密码并允许你存储其他信息。

有大量的密码管理器可用，其中许多是自由及开源的解决方案。我在 Windows 上用过 [KeePass][4]，在 Linux 和 MacOS 上用过[KeePassX][5]，我推荐使用他们作为开始。（这里还有三个[开源密码管理器][6]，你可以尝试一下。）

然而，每个人应该选择他自己的最佳解决方案。某些密码管理器除了本地存储之外还具有云存储的功能，如果你使用多个设备，这将非常有用。更受欢迎的管理器更有可能被维护并接受定期的安全更新。一些密码管理器具有 2FA 集成，我强烈建议你启用它。

大多数密码管理器都没有恢复忘记的主密码的功能。所以要明智地选择并确保主密码是你可以记住的。

### 使用 VPN 提高共享网络的安全性

虚拟专用网络（VPN）允许计算机通过共享网络发送和接收数据，就像它通过端到端加密直接与专用网络上的服务器通信一样。

您可能熟悉从办公室工作时连接到公司内部网的过程。使用连接到咖啡馆或饭店的公共网络的 VPN 会保护你不被别人看到你的数据连接，但它不会阻止 VPN 供应商看到数据连接，并且存在违规 VPN 提供商收集和销售数据的现象。VPN提供商也可能收到来自政府或执法机构的压力，以传递有关您通过其网络发送的数据的信息。 因此，请记住，如果您正在进行非法活动，VPN 将不会保护你。

当选择 VPN 提供商时，请考虑运营所在的国家，因为这些是将受其约束的法律，甚至无害的活动都可能使您陷入困境。

[OpenVPN][7] 是一个免费和开源的 VPN 协议，可在大多数平台上使用，并已成为最广泛使用的 VPN 之一。 您甚至可以小心谨慎地托管您自己的 OpenVPN 服务器。如果您希望使用VPN服务，请记住许多声誉良好的提供商都想要您的业务。

有些是收费的，如[ExpressVPN][8]，[NordVPN][9]或[AirVPN][10]。一些提供商提供免费服务，但是，我强烈建议您不要使用它们。 请记住，当您使用免费服务时，您的数据就是产品。

### 浏览器扩展程序是您的朋友

虽然互联网浏览器有一些内置的安全工具，但是扩展仍然是增加您的隐私和安全的好方法。有很多种类的扩展，但哪些扩展是适合你的？ 这可能取决于你主要使用互联网的主要目的和你是对技术的掌握程度。作为基线，我使用以下扩展：

*   [Privacy Badger][1]：这个扩展，由 EFF 开发，阻止间谍广告和隐蔽的跟踪。它通过在流量请求中放置一个 Do Not Track头，然后评估流量仍被跟踪的可能性。如果这种可能性很高，它会阻止来自该域的进一步流量（除非你另有说明）。扩展在 GNU GPL v3 下获得许可。
*   [HTTPS Everywhere][2]：EFF 和 Tor 项目之间的联合协作，此扩展确保尽可能自动使用HTTPS。这很重要，因为它意味着您的网络流量与给定的域是加密的而不是纯文本、提供隐私和确保交换数据的完整性。扩展在 GNU GPL v3 下获得许可。

### 不要忘记旧帐户

你还记得 Bebo，iTunes Ping，Del.icio.us，Digg，MySpace 或 Friendster吗？你有帐户吗？你关闭了帐户还是刚停止使用帐户？你曾经停下来想一想什么信息可能在这些网站上吗？

旧的社交媒体帐户可以是那些收集数据的人的金矿，包括营销人员，欺诈者和黑客。他们可以使用这些信息来构建您的个人照片，这些信息通常可以显示密码重置中用于识别的重要事实，例如您的第一只宠物的名字或您的第一辆车。

某些网站可能会让删除帐户变得困难或实际上不可能。[Justdelete.me][11]是一个很好的资源去找到如何删除各种平台上的社交媒体帐户的说明。如果你正在寻找的网站不在那里，你可以将自己找到的信息贡献 GitHub 的项目。如果您不确定您可能已忘记的社交媒体帐户，[Knowem.com][12]允许您按用户名搜索大量的社交网络。搜索工具不能免疫误报，虽然你可能不是曾经使用过给定用户名的唯一的人，但它是一个很好的开始，尽管不是开源的。

如果您不确定您可能使用的旧用户名，Google 是一个很好的资源。尝试搜索旧昵称和电子邮件地址，你可能会对你发现的事感到惊讶。

### 总结

无论数字安全的任务如何巨大，你都可以在开始使用时打下坚实的基础。记住，安全是一个持续的过程，而不是一种存在的状态。保持您使用的工具最新，并定期检查您的习惯和工具，以确保您的安全是最好的。如果你每次一步一步的改变，安全就不会过于复杂。

--------------------------------------------------------------------------------

作者简介：

Tiberius Hefflin - Tibbs 最近毕业于苏格兰西部大学，获得计算机安全学位。她已搬迁到波特兰，在为波特兰通用电气公司做安全保证工作。 她热衷于鼓励小孩子踏上 STEM。

--------------------------------------------------------------------------------

via: https://opensource.com/article/17/1/4-ways-improve-your-online-security

作者：[Tiberius Hefflin][a]
译者：[livc](https://github.com/livc)
校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]:https://opensource.com/users/whatatiberius
[1]:https://www.eff.org/privacybadger
[2]:https://www.eff.org/Https-everywhere
[3]:https://opensource.com/article/17/1/4-ways-improve-your-online-security?rate=sa9kEW1QXWaWvvq4F5YWv2EhiAHVDoWOqzZS2a95Uas
[4]:http://keepass.info/
[5]:https://opensource.com/business/16/5/keepassx
[6]:https://opensource.com/article/16/12/password-managers
[7]:https://openvpn.net/
[8]:https://www.expressvpn.com/
[9]:https://nordvpn.com/
[10]:https://airvpn.org/
[11]:http://backgroundchecks.org/justdeleteme/
[12]:http://knowem.com/
[13]:https://opensource.com/user/108496/feed
[14]:https://opensource.com/article/17/1/4-ways-improve-your-online-security#comments
[15]:https://opensource.com/users/whatatiberius
