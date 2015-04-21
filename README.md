WiAuth-Windows
=====

概述
-----

主项目：[WiAuth](https://github.com/WiAuth/WiAuth)

在日常生活中，互联网用户需要面对大量授权登录场景，已有的方式大多需要用户交互验证或者额外的硬件。眼下，国家网络实名制进程正在逐步推进，找到一种廉价而有效的方式迫在眉睫。因此，我们提出了一种既快速又安全，同时可以解决实名制的身份认证算法。本算法依靠局域网通信，以手机作为硬件令牌，使用token传递机制，使用户只需点击按钮即可完成授权操作。此外，其利用滚动密钥机制和DES加密算法，及配对口令体系，保障了较高的安全性。同时利用手机号开户时录入的实名信息，通过SIM卡ICCID查询，实现实名验证和登录保护。本算法实现了较好的用户体验、安全保障以及实名制解决方案。当下，智能手机与家庭局域网络已经十分普及，此算法的推广容易被用户接受。同时，算法提供了API接口以及SDK，为第三方软件使用此算法提供了可行的方案，具有较好的普适性和可移植性。本算法可应用在网络登陆、实名安全支付和网吧实名登记等场景中。

作者
-----

- [@coderfox](https://github.com/coderfox) (Yuze Fu,傅禹泽)<coderfox.fu@gmail.com>

复制
-----

### 发布版本

本程序每一个发布版本会提交一个release，同时开启对应的`version/`分支。

程序采用`major.minor.patch.build`版本号命名格式。

### 源代码

我们在开发过程中使用了[BuildTool](https://github.com/coderfox/BuildTool)作为版本号的自动维护工具。

因此，如果你只是想自己编译一份代码，请在启动编译之前删除各项目的后期生成事件。

如果你想对本项目贡献代码，请在[BuildTool](https://github.com/coderfox/BuildTool)中找到最新release的`BuildTool.exe`并复制到解决方案的目录下。
