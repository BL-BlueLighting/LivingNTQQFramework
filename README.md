<div align="center">
  <h1>Living NTQQ Framework</h1>
  <i>The list of frameworks for NTQQ.</i>
</div>

## 0. 前言
自 NTQQ (即基于 Electron 的 QQ) 发布起，基于 NTQQ 的 QQ Bot 库层出不穷.

NTQQ 的底层协议库名为 `wrapper.node`，在 QQ 目录 `resources/` 下方.

主流为 `NapCatQQ`，原仓库链接： [Click me](https://github.com/NapNeko/NapCatQQ).

后起之秀：`SnowLuma`，原仓库链接：[Click me](http://github.com/SnowLuma/SnowLuma).

但 2026 年 11 月 12 日，`NapCatQQ` 由其 Maintainer @MliKiowa 自行删库.

`SnowLuma` 项目因腾讯律师函，已转 Private.

那么，在现如今，我们还有哪些框架，哪些库可以依赖、使用呢？

## 1. NapCatQQ Forks & Dumps
这里列出 NapCat 还未 Sync 的 Forks 和 Dumps.

- XingYunStar/NapCatQQ 链接：[Click me](https://github.com/XingYunStar/NapCatQQ).
- su2569/NapCat 链接：[Click me](https://github.com/su2569/NapCat).
- ZoeRift805/NapCatQQ 链接：[Click me](https://github.com/ZoeRift805/NapCatQQ).
- VanillaNahida/NapCatQQ 链接：[Click me](https://github.com/VanillaNahida/NapCatQQ).
- (... 可自行补充 ...)

NapCatQQ 的正确最后提交 Commit 应为 `72912f293924f43463b5976b01fc094a8ae11481` 该 Commit.

## 2. SnowLuma Dumps
这里列出 SnowLuma 的 Dumps.

- https://github.com/TomyJan/SnowLuma
- https://github.com/XingYunStar/snowluma
- https://github.com/xyy0411/SnowLuma
- https://github.com/zhx57/SnowLuma
- https://github.com/venti1112/snowluma
- https://github.com/airline233/SnowLuma
- https://github.com/baixiangyuan/SnowLuma
- https://github.com/wess09/SnowLuma
- (... 可自行补充 ...)

SnowLuma 的正确最后提交 Commit 应为 `f2ea3354f8bbe8672cbb4ae6a2b4e1fbeff44faf` 该 Commit.

## 3. 框架 / 库 实现
### 3.1 Lagrange
链接：[Click me](https://github.com/LagrangeDev/Lagrange.Core)

Lagrange 为 .NET 库，如果需要使用，需要将其内嵌进 Bot 项目（完全转 .NET）或者将其编译为动态库，交由其他编程语言使用.

### 3.2 Chronocat
链接：[Click me](https://github.com/chrononeko/chronocat)

Chronocat 为 Satori，同时基于 LiteLoaderQQNT。而 LLQQNT 本身早已 Archived，同时还有缺少的 API.

如果你的项目不能使用 Lagrange，不想增加一层技术栈负担，或者又不想要 LuckyLilliaBot，Chronocat 可能会是你不完美的最佳选择.

### 3.3 OpenShamrock
链接：滚木

WhiteChi 应该被请去喝茶了，OpenShamrock 的不完整存档：[Click me](https://github.com/TimeRainStarSky/OpenShamrock)，也许可以使用.

### 3.4 LuckyLilliaBot / LLOneBot
链接：[Click me](https://github.com/LuckyLilliaDev/LuckyLilliaBot)

目前当下最优秀的解决方案.

LuckyLilliaBot 前身为 LiteLoaderQQNT 的插件：LLOneBot，但由于 LiteLoaderQQNT 本身的 Archived，导致其迁移自立门户.

~~主播就是因为之前用 LLOneBot 才记住它的~~.

如果你想得到最接近 NapCatQQ 的体验，LuckyLilliaBot 是你的不二之选.

### 3.5 (仍待补充)
...

## 4. 结语
腾讯应该是在最近大肥鱼浪潮后开始整治 Bot 社区了，推荐各位给以上项目进行 Fork 和本地 Clone。

~~腾讯，我日你仙人，给句痛快话，投降不投降！~~
