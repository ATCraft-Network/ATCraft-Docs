# 常见问题

文：土拨鼠，GrassBlock2022

-----
<!-- TOC -->
* [常见问题](#常见问题)
    * [登录](#登录)
    * [服内](#服内)
    * [皮肤站相关](#皮肤站相关)
    * [服务相关](#服务相关)
    * [查找资料/帮助](#查找资料帮助)
    * [服务器提示](#服务器提示)
<!-- TOC -->

### 登录
**(1) 我离线怎么上不去服务器？&#x20;**

请配置[外置登录](course/auth/launcher-config.md)或使用正版账户（服务器支持双登录）

**(2) 登录服务器显示 “登录失败:无效会话…”_ &#x20;**

未正确配置外置登录（注意！_我们**不支持 Littleskin，仅支持**_ 
[_**StarfishSkin**_](https://skin.tbstmc.xyz)_）_，
登录服务器请请前往[外置登录配置教程](course/auth/launcher-config.md)

**(3) 登录服务器显示“登录失败：暂时无法连接到身份脸证服务器，请稍后再试。**

请检查您的网络，确保可以正常访问[皮肤站](https://skin.tbstmc.xyz)后重试。
若一直不行，尝试重启启动器（实在不行更换启动器）或网络。（试试，也许魔法可以）<br/>
也可能是服务器网络抽了，这种情况下我们也没办法，耐心等吧。

**(4) 登录服务器显示 “Outdated client!Please use 1.18.2”**

您所在的版本服务器暂时不支持，请更换版本（服务器介绍里有写）并且重新尝试。
若仍然进不去，可能是服务器正在重启，请等待重启完毕。

**(5)Q:服务器支持手机版上服吗？**

仅支持手机版BE和Java（[HMCLPE](https://github.com/huanghongxun/HMCL-PE)），网易和愚人节版就别想了！

**(6) 服务器支不支持mod？**

不支持！服务器是插件服，而且未来也不会考虑支持mod。

### 服内

**(1) 为什么我的小木斧无法创建选区且受到了警告?**

你圈的太大了，试着缩小选区。一般情况下，如果你的选区可以正常的被粒子围住，那你的大小是正确的。

**(2) 破坏了他人的建筑怎么办**
* 如果只是破坏了几个方块，补回去即可。
* 如果是什么复杂的红石机器，那就别动了。保护好现场，去群里@FrsFallingSand，只有他会修
* 可以留个告示牌说明原因（可选）
* 如果修复不了，立刻去群里摇人，我们会进行区域回滚
* 如果回滚数据异常，那你只能和建筑所有者进行和解了

**(3) 被神权了怎么办**

一般群里谁被踢了草方块都会问两句，实在不行你就加土拨鼠QQ申诉吧。
如果情况属实的话，我们会给你一个公道的结果。

**(4)我被禁言/移出群聊了，怎么办？**

可能是你违反了[群规](server/rule/server-rules.md)不满意请找群内管理申诉。

### 皮肤站相关

**(1) 苹果设备无法上传皮肤/披风**

已经确认为bug，等待官方修复！[Github issues](https://github.com/bs-community/blessing-skin-server/issues/509)

——2024.2.2: 刚去看了一眼，官方确认不在修复计划中了

**(2) 皮肤站签到获得的积分有什么用？**

请看皮肤站原文。

> 为了防止用户滥用材质上传功能导致占用过多的存储空间，本站已启用积分系统。\
> 添加角色、上传材质，以及添加皮肤库里的材质到衣柜等操作均会消耗积分。\
> 删除已经添加的角色、已上传的材质、衣柜中的收藏物品时将会返还相应积分。\
> \
> 本站用户初始积分为 500，每日签到可以随机获得 0 \~ 2023 积分。
>
> * 100 积分 = 1 KB 存储空间
> * 250 积分 = 1 个角色
> * 150 积分 = 1 个衣柜收藏

### 服务相关

**(1) 访问文档出错？**

重载一下，当然你现在遇到这问题的几率不大了。

**(2) 访问官网发现样式全乱了，怎么办？**

鬼知道草方块又在干啥……重载网页或者等一下

**(3) 为啥我去不了服务大厅？**

你进去了才有鬼呢，还没上线

### 查找资料/帮助

首先您可以访问我们的文档

其次您可以前往[搜索引擎](https://baidu.com)查找答案

如果以上问题均未得到解决，请尝试进入[QQ群](https://jq.qq.com/?\_wv=1027\&k=ToOzeOPU)内询问！

本界面持续更新，若您的问题并不包含在内或信息未能得到及时更新，您可以前往[QQ群](https://jq.qq.com/?\_wv=1027\&k=ToOzeOPU)反馈！

### 服务器提示
**(1)TBSTQuark 插件的提示**
当您首次登录到 ATCraft Network 集群的时候，您可能会看到一条来自 TBSTQuark 插件的提示信息。
这些信息默认被存储在服务器的数据库中（已进行脱敏处理），您无需担心出现的任何警告。
当您使用异地登录时，TBSTQuark 插件会提醒您：“您的 IP 地址变动为 xxxx，已被系统记录。”
如果您确认是您本人的操作，完全可以忽略此条信息。

**(2)LiteSignIn 插件的提示**
如果您尚且了解一些 Minecraft 圈的大事，您就可以知道国内最大中文 Minecraft 论坛 MCBBS 彻底关站。
因为这个原因，LiteSignIn 插件会在每个玩家登录到集群的时候发送一条提示信息。您可以直接忽略。

**(3)MultiLogin 插件的提示**
当然，相较于前两个提示来说，这是个较为重要的提示。因为 MultiLogin 的插件包含了您当前使用的登录方式，
您当前的 ID 等重要信息。如您无法连接到一个官方集群内的服务器，请将此截图发送到 ATCraft 生存服的官方群中。