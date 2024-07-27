# 安全
文：GrassBlock2022

-----
为服务器提供基本的安全功能，包括防爆，防盗号，反假人等

- 包/组id: quark_security
- jar位置: 核心内置

### ExplosionDefender | 爆炸保护

提供可配置的防爆功能。

**模块id:**
```
quark_security:explosion_defender
```

配置文件:

```yaml
  explosion_defender:
    override_explosion: true #是否重新覆盖生成一个假爆炸（不破坏方块）
    record: true #是否记录爆炸事件在文件中
    broadcast: false #是否广播爆炸事件给管理员
```

### IPDefender | IP属地检测

监测玩家的IP属地，并在检测到变化的时候自动记录并做出操作。

**模块id:**
```
quark_security:ip_defender
```

**配置文件:**

```yaml
  ip_defender:
    record: true #是否记录IP属地变化
    auto_ban: false #是否自动封禁
    auto_ban_day_time: 0 #封禁的时间，往下为天，时，分，秒
    auto_ban_hour_time: 0
    auto_ban_minute_time: 10
    auto_ban_second_time: 0
```

**API:**

通知ID: ```ip_change```

参数: ```player``` IP属地变化的玩家名称

### ItemDefender | 物品黑名单

你可以ban掉一些物品，或者是在玩家使用一些物品时给出警告。
同样的，我们提供了信息记录和广播。

**模块id:**
```
quark_security:item_defender
```

**配置文件:**

```yaml
  item_defender:
    record: true #是否记录
    broadcast: false #是否广播给管理员
    op_ignore: true #OP是否可以豁免
    illegal_list: #没收的列表(注: 其中填写 Minecraft ID)
      - "__placeholder__"
    warning_list: #发出警告的列表
      - "tnt"
      - "flint_and_steel"
      - "lava_bucket"
```

### PermissionManager | 权限管理器

提供类似PermissionEx的权限组和单独覆盖一位玩家的权限的功能
(注: 通配符*可以引用该节点下所有子权限)

**模块id:**
```
quark_security:permission_manager
```

**配置文件**
```yaml
#(为避免阅读不变，这里略去了一些基础权限组)
  permission_manager:
    default_group: player #设置默认权限组id
    groups:
      operator: #创建一个组，可以在下面继续填写（赋予操作先允许再去除不允许）
        disallow: #不允许执行的权限
          - minecraft.command.stop
          - minecraft.command.reload
        allow: #允许执行的权限
          - minecraft.command.*
          - worldedit.command.*
```

**命令**
- ```/permission group [name] [group]``` 设定一个玩家的权限组(仅OP可用)
- ```/permission set [name] [node] [true/false/unset]``` 设定一个玩家的覆盖权限组(仅OP可用)

### AccountActivation | 账户激活
不稳定模块，行为未知，故不提供文档、不建议启用。

### ProtectionArea | 保护区域
文档等待补全...

### LimitedArea | 交互区域限制
文档等待补全...

