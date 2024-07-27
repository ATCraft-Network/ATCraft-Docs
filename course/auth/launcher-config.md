# 启动器配置方法

文: 土拨鼠, GrassBlock2022, CubeVlmu

-----

## 目录

<!-- TOC -->
* [启动器配置方法](#启动器配置方法)
  * [目录](#目录)
  * [引言](#引言)
  * [HMCL启动器](#hmcl启动器)
    * [1.添加验证服务器](#1添加验证服务器)
    * [2.添加账户](#2添加账户)
  * [PCL（PlainCraftLauncher）启动器](#pclplaincraftlauncher启动器)
    * [1.选择登录方式](#1选择登录方式)
    * [2.设置验证服务器](#2设置验证服务器)
  * [BakaXL启动器](#bakaxl启动器)
<!-- TOC -->

## 引言

一般地，启动器不会携带已经第三方验证服务器，而不少服务器（例如我们）都有自己的验证服务器。
因此，本教程将详细解释启动器的验证服务器配置方法。这里以StarfishSkin为例。
当然，通过相同的方式，您也可以添加其他的验证服务器。（只不过它们无法通过TBSTCraft验证系统。）

> 验证服务器地址：[`https://skin.tbstmc.xyz/api/yggdrasil`](https://skin.tbstmc.xyz/api/yggdrasil)
>
> _在Starfish Skin个人主页的下方即可查看_

-----

## HMCL启动器

### 1.添加验证服务器

打开HMCL启动器，点击 "**添加账户**";

![](https://picss.sunbangyan.cn/2023/12/02/2e337cbb5b891756dd331e6bd78b8037.jpeg)

点击界面左下角的 "**添加认证服务器**" 选项;

![](https://pic.imgdb.cn/item/656ac8aec458853aef500733.webp)

设置为Starfish Skin皮肤站的服务器的认证地址。

![](https://pic.imgdb.cn/item/656ac8ccc458853aef507c4d.webp)

### 2.添加账户

在"**添加账户**"栏，点击配置好的登录服务器（如果没看到"Starfish Skin"则返回第一步检查错误）

![](https://picst.sunbangyan.cn/2023/12/16/250a0f4282639f84a2d404aac98f5d87.jpeg)

点击后会出现一个弹窗，输入你的角色名（用户名）和密码

![](https://picst.sunbangyan.cn/2023/12/16/28ea1024915267f9d4495edf8d5b6e40.jpeg)

接下来不出意外的话你的角色栏应该会多一个选项，就像这样。

![](https://picst.sunbangyan.cn/2023/12/16/5aa73e9bab827828c98cbdfc9625f7d4.jpeg)

选中它，然后接下来启动游戏就完成了。

-----

## PCL（PlainCraftLauncher）启动器

### 1.选择登录方式

打开PCL启动器，选择你要配置的游戏版本，并点击设置;

![](https://picdl.sunbangyan.cn/2023/12/02/1f75431a89792dce4f0f3cb0d14b7b9f.jpeg)

选择游戏的详细设置;

![](https://picss.sunbangyan.cn/2023/12/02/4a7eac64774425e708fe4a5260c7319f.jpeg)

拉到界面底部，在登陆服务器这里选择_第三方登录：Authlib Injector或 LittleSkin**这一个选项**
*（记住这里不是让你注册Littleskin!!）*

*![](https://picss.sunbangyan.cn/2023/12/02/df5369c5841a62fb822171bd387c030f.jpeg)

### 2.设置验证服务器

选中 **"登录服务器"** ，设置为Starfish Skin皮肤站的认证地址（在皮肤站的个人中心会显示）：
[`https://skin.tbstmc.xyz/api/yggdrasil`](https://skin.tbstmc.xyz/api/yggdrasil)
(注意：**千万**<mark style="color:red;">**不要**</mark>**点底下的** _设置为 LittleSkin_ **按钮，直接返回即可保存**)

![](https://picdm.sunbangyan.cn/2023/12/02/fbd27adec1169c92f058c7f20297de85.jpeg)

返回主页，在弹出的登陆位置输入你的皮肤站账号（邮箱）和密码。
输入完信息后，点击启动游戏，如果**账户密码正确**，则启动器会自动帮你登陆完成并且启动游戏。
进入游戏后，你的身份验证就生效了。

-----

## BakaXL启动器

打开BakaXL，登录自己的BakaXL账户后进入主界面，找到 _本体设置_

![](https://picdl.sunbangyan.cn/2023/12/02/92262facd02bcfba7bd23093fd882283.jpeg)

找到设置里侧边栏的 _账户与档案_

![](https://picdm.sunbangyan.cn/2023/12/02/f8cc31db4cfdcf09f089a5fd0e92fab2.jpeg)

拉到底部，点击 _新增一个档案_

![](https://picss.sunbangyan.cn/2023/12/02/5adc8954d57fc45b30fa757c05f8ab65.jpeg)

找到游戏启动模式 分别点击三次 _离线模式 位置的文字_ 来切换到外置登录

![](https://picdm.sunbangyan.cn/2023/12/02/d4eb02c8add751e4865f2374b49f6ca5.jpeg)

在 _账户信息_ 里填写认证服务器地址

![](https://picst.sunbangyan.cn/2023/12/02/e86b29cb9292e94649439b0daf7bfec2.jpeg)

输入完毕后，Bakaxl会校验验证服务器地址，

![](https://picdm.sunbangyan.cn/2023/12/02/cc1bded7df441d1afc89b9004bd3eefc.jpeg)

验证完毕后，即可输入账户密码，输入完毕后，点击左下角的 _验证并返回_

![](https://picss.sunbangyan.cn/2023/12/02/4f4a5df78b7e2b7d00b9e3ee15bd94a7.jpeg)

返回到主界面，点击启动游戏，启动器会自动帮你登陆完成。
至此，外置登陆配置就好了！
