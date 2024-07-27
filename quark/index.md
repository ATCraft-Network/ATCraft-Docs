# Quark插件

文: GrassBlock2022

-----

### 简介
Quark(中文名: 夸克)是我服自主研发的综合管理型插件，目前已应用于TBSTCraft服务器。
由于服务器公益化运营模式带来的长期支出可能导致腐竹无法负担，故我们将此插件以商业化形式对外出售。
所得资金的大部分将用于服务器的运营支出。

### 兼容性
#### Paper和上游服务端
从3.54.13开始，Quark的开发中心从Spigot/Bukkit移向Paper。
这将提供全新的功能，API和文本引擎。新的功能将仍然适配Paper上游平台，
但是文本引擎的文字互动功能将会无法使用。我们仍然建议您使用Paper及其下游服务端，
因为其拥有更完善的API和更好的性能。

#### 关于Folia适配
在Folia服务端上，Quark将会自动开启专用的FoliaTaskManager后端。
同时，您会收到一条关于Folia兼容性问题的警告。请不要反馈任何有关API兼容性的问题。
其利用Folia新增的Scheduler，可以优化Quark的性能。
由于Folia的API不完善，我们不建议您在FoliaAPI完善之前使用Quark。

### 特性
#### 优势
- 高性能: i7-12700平台实测paper1.18.2实测启动时间不足200ms。
- 模块化: 功能拆分细致，且每个模块均可单独启停。
- 健壮性: 各个模块之间完全独立，核心正常加载则整个插件将不被任何模块/子包影响。
- 简单: 配置文件一键自动刷新，支持开箱即用，无需复杂的准备配置工作。
- 低侵入: 不会注入服务器后端/原版数据，卸载无任何影响。

#### 不足
- 并发弱: 受限于Bukkit线程调度和插件逻辑设计，在稳定的前提下无法实现完全异步。
- IO要求高: 受分离式文件后端影响，IO性能远不及数据库，但目前IO并未成为瓶颈。

### Q&A:
#### 为什么不用中文配置？
```yaml
为什么我不支持其他语言的配置:
  一来是这样写要切换输入法: 会导致编码效率下降
  二来是这玩意解析来太慢: 并且解析器会时不时崩溃
  而且老有傻逼:
    - 在这里装个GBK问我为啥乱码
  所以我是不可能用中文的: [日文,韩语]
  之类的小语种也: 不行
```

### 开始
* [基本介绍](quark/index.md)
* [配置文件](quark/configuration.md)
* [模板引擎](quark/template-engine.md)
* [模块](quark/modules.md)