# github笑传之会员制餐厅

> 分析对象：DandanLLab/SnowCatQQ　·　数据抓取：2026 年 11 月 16 日　·　材料范围：公开仓库、公开主页、公开评论区

<img width="1280" height="720" alt="28c7963ea4aa7684eb94021ed3cee2f7_720" src="https://github.com/user-attachments/assets/531ebbcd-1451-442d-b770-aae730efc81c" />

> 因为使用到了 [Snowcat](https://github.com/DandanLLab/SnowCatQQ) 成为 [食雪汉](https://baike.baidu.com/item/%E6%88%91%E4%BF%AE%E9%99%A2?fromtitle=%E9%A3%9F%E9%9B%AA%E6%B1%89&fromid=65211459&fromModule=lemma_search-box)而面露难色的两位 QQbot 用户

---

## 为啥会有这事

2026 年 11 月 10 日，随着[南山必胜客](https://baike.baidu.com/item/%E5%8D%97%E5%B1%B1%E5%BF%85%E8%83%9C%E5%AE%A2?fromModule=lemma_search-box)的两纸律师函，[NapCat](https://github.com/NapNeko/NapCatQQ)项目发布最后一次提交，标题为ending，正式跑路了，同日SnowLuma仓库也从 GitHub 消失，返回 404，空悲切。24 小时后，一个名为 [SnowCatQQ](https://github.com/DandanLLab/SnowCatQQ) （下简称[雪猫](https://github.com/DandanLLab/SnowCatQQ)）的仓库出现在 GitHub 上。其对外宣称把 [NapCat](https://github.com/NapNeko/NapCatQQ) 与 SnowLuma 两套代码融合且全功能适配 QQ 9.9.37，拥有所谓的56 项独门动作，MCP 接入，全线开源，持续维护

<img width="1844" height="1336" alt="image" src="https://github.com/user-attachments/assets/63bc28d5-c808-4f1d-b741-d4099841b9a8" />

> 哇啊啊有制作这么精良的logo，这种协议端你什么时候用

光看名字就知道是要吃[nc](https://github.com/NapNeko/NapCatQQ)和sl[人血馒头](https://baike.baidu.com/item/%E4%BA%BA%E8%A1%80%E9%A6%92%E5%A4%B4?fromModule=lemma_search-box)，打算趁着两个协议端跑路包圆这一块的热度，事实上其开发者称自己的行为为“接续先行者铺下的路”；那么这个仓库在开源社区里究竟是一个什么东西呢？

史家据史直书，一字不改！

且不说 [拉格兰](https://github.com/LagrangeDev/Lagrange.Core) 这种还在更新的协议库（它甚至已经把自己的 OneBot 端换成 Milky 了而与此同时 [SnowCatQQ](https://github.com/DandanLLab/SnowCatQQ) 还在 [读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里把 Milky 当成自己的兼容层卖点）；事实上倘若[雪猫](https://github.com/DandanLLab/SnowCatQQ)是个好协议端，在开源社区继续维护已经归档的仓库此类行为本身也是个好事——但是这个仓库实在是极为抽象以至于我在多个技术交流为主的QQ群都看到有群u对此事件发表锐评了，本着实事求是的想法，我想我也必须得对此仓库进行轰轰烈烈的真理大讨论了

全文除了玩梗不掺杂纯粹人身攻击，要说不带感情来评价这坨[旷世巨奋](https://github.com/DandanLLab/SnowCatQQ)是不可能的了因为我不相信有人看完这个仓库底下的一些 [issue](https://github.com/DandanLLab/SnowCatQQ/issues/13) 能忍住不笑出来以至于不产生“这波贪了应该再等几个月留着春晚看的”的想法——故请读者读完**自行得出自己的结论，不要跟着我起哄**，一人做事一人担

<img width="1080" height="1480" alt="image" src="https://github.com/user-attachments/assets/eee93628-4ba1-4377-af7d-99924cf52979" />

### 时至今日，作者的左右脑还未和解，愿世界和平

| 项目表述 | 项目状态 |
|---|---|
| “QQ 本体一字节未动”“核心文件无一处魔改” | 仓库 [ARCHITECTURE-AUDIT.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/ARCHITECTURE-AUDIT.md) 标题就是“融合魔改 QQ 客户端”，硬改清单第 5 条标注“实锤，系统级硬改” |
| “感谢 [NapCat](https://github.com/NapNeko/NapCatQQ)（126,400+ ⭐）” | 作者但凡自己看看[NapCat](https://github.com/NapNeko/NapCatQQ)仓库就不会连star数都写错 |
| “每一项能力，都经在役验收，全绿方才发版” | 注意到本仓库唯一的 [release](https://github.com/DandanLLab/SnowCatQQ/releases) 附件列表为棍母且 tag 落后 main 13 个提交，全仓就 26 个包且 25 个版本号还是 0.0.1 |

## [南山必胜客](https://baike.baidu.com/item/%E5%8D%97%E5%B1%B1%E5%BF%85%E8%83%9C%E5%AE%A2?fromModule=lemma_search-box)这么这么坏啊😭

[雪猫](https://github.com/DandanLLab/SnowCatQQ)项目自己的公告里记录了[nc](https://github.com/NapNeko/NapCatQQ)和sl被杀的事情，此处不述。那此时，我们嗅觉灵敏思维敏捷反应迅速的[雪猫](https://github.com/DandanLLab/SnowCatQQ)开发者[蛋蛋呀](https://github.com/DandanLLab)大人当时在干什么开天辟地的大事呢？答案是：

## 嘿DSH，我要开始 wish coding 了

<img width="570" height="658" alt="3fe996f8b1dc32767662a022f1327de3" src="https://github.com/user-attachments/assets/7afd4454-d589-43d1-8bf7-dab2ad7d6d2c" />

> 此时的作者：

### 兄弟逗我呢 git 是这样 commit 的吗

注意到 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 的 git 提交记录：

| 时间（UTC） | 事件 |
|---|---|
| 11-11 22:23:10 | 仓库创建 |
| 11-12 06:27:36 | 首次也是单次提交了 1048 个文件，统计共 130,851 行 |
| 11-12 06:29:38 | 文档归位 |
| 11-12 06:30:32 | chore: 删掉一个空的 upstream readme |
| 11-12 06:38:59 | docs: README 全新排版（徽章矩阵/特性表/运行时栈图/居中致谢） |
| 11-12 06:39:54 | docs: 公告全文内嵌 README |
| 11-12 07:02:40 | docs: 双对比表 + B 站素材视频卡片嵌入，全文重排版 |
| 11-12 07:03:20 | docs: README 主图改用“雪猫手绘 logo” |
| 11-12 07:09:03 | docs: 加插件引路表 |
| 11-12 07:10:29 | docs: 补官方机器人路线入口 |
| 11-12 07:16:38 | docs: 写“我们的信条” |
| 11-12 07:18:15 | docs: 移除三项插件（师父令） |

从[首次提交](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379)到[宣称能用的最后一次提交](https://github.com/DandanLLab/SnowCatQQ/commit/4bd67e3c9b54df5baa12dacd5f49850bf70157fb) 居然总共只花了 51 分钟，而且最后几次提交还几乎全都是文档变更，我们速度飞快效率极高生产力爆炸的[雪猫](https://github.com/DandanLLab/SnowCatQQ)开发者[蛋蛋呀](https://github.com/DandanLLab)大人的 Vibe Coding 技术可谓是炉火纯青，其 review 代码的速度已经超越了全体人类了，开源社区诞生一名宗门圣女[Jumping02](https://baike.baidu.com/item/%E5%A7%9C%E8%90%8D/68637978?fromModule=disambiguation)

## “我们”？

该仓库[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md)全文，“我们”这个词出现了 93 次( 统计数据来源于免费模型 inkling-2 )

与之配套的自称包括[Snowcat开发组](https://github.com/DandanLLab/SnowCatQQ)等等

以下是 GitHub 上的 [contributors](https://github.com/DandanLLab/SnowCatQQ/graphs/contributors?from=2026%2F8%2F15) 实际构成。

| 署名 | 提交 | 情况 |
|---|---|---|
| 蛋蛋呀~ | 25 | 账号 UID 100036451 |
| 天天的鸟蛋蛋 | 11 | 根据本人检查为同一账号的另一个显示名，根据是这俩玩意邮箱居然是同一串 |
| SnowCat Security Bot | 9 | 邮箱为 security@localhost，非注册账号 |
| dependabot[bot] | 4 | gh的傻软depbot |
| 晚晴 | 2 | 短期外部贡献 |
| Amria | 1 | 短期外部贡献，甚至是 OneBot 12 兼容层这种核心 |
| Na2Cr2O7 | 1 | 外部贡献，Star History 图表 |

此外，这个项目没有 GitHub Organization。仓库挂在个人账号 DandanLLab 下。*“开发组”三个字在代码托管平台上找不到任何对应物，唯一看起来像团队成员的是一个 localhost 邮箱*
> 不过这就解释得通了因为前文说过作者左右脑尚未达成世纪大和解，姑且将作者视为两个人，也即一个开发组

## 授权

仓库根目录的 [LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/LICENSE) 原文如下：

> 1. Usage and Reproduction:   Unauthorized use, reproduction, modification, or distribution of this code is prohibited without explicit permission from the main author of the NapCat repository.2. Redistribution:   Minor modifications and extensions are allowed for redistribution purposes, but the modified code must not be publicly released.3. Non-Commercial Use:   This code is not to be used for any commercial purposes.

版权行写作：Copyright © 2024 Mlikiowa。

这三段的含义是：修改后的代码不得公开分发。而这个仓库做的全部事情，就是修改这份代码并公开发布。

> 哇啊啊有法律这么严谨啊，这种授权你什么时候见过它生效

### 哎我去怎么还有两份别人的 MIT

不是一份，是**三份 LICENSE 文件**躺在同一个仓库里：

| 文件 | 内容 | 版权人 |
|---|---|---|
| [LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/LICENSE) | NapCat Limited Redistribution | Mlikiowa |
| [packages/snowcat-webui-frontend/LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-webui-frontend/LICENSE) | MIT | [bietiaop](https://github.com/bietiaop) |
| [packages/snowcat-dpapi/LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-dpapi/LICENSE) | MIT | [Xavier Monin](https://www.npmjs.com/package/@primno/dpapi) |

按 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 自己的话说法，[`packages/` 是"底座移植"，`snowcat-webui-*` 是"自研"](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md)。

那我们来查查这个"自研"到底是谁研的。

[bietiaop](https://github.com/bietiaop) 名下有个仓库叫 [NextNapCatWebUI](https://github.com/bietiaop/NextNapCatWebUI)，MIT 许可，65 颗星，2024 年 11 月 28 日建的，描述是"适用于 NapCat 的 WebUI"。而 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 的 `packages/snowcat-webui-frontend/LICENSE` 第 3 行写着：

> Copyright (c) 2024 bietiaop

这份文件连改都没有改过，一个字都不差。于是[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里那句"雪猫控制台（React + Tailwind + HeroUI 全面重制）"里的"重制"二字就非常有灵性了——~~重制之后连人家的名字都留着，这叫尊重原作者，建议全体开源爱好者学习~~

至于 `snowcat-dpapi` 那份 MIT，是 [@primno/dpapi](https://www.npmjs.com/package/@primno/dpapi) 的，Xavier Monin 的。这个倒是正常的第三方依赖声明，问题在于**为什么一个 npm 依赖的 LICENSE 会被复制进仓库根目录的 packages 里**——大概是复制粘贴的时候忘了删。

*当然，这不影响什么，只影响"自研"这两个字到底还能用在什么东西上*

### 授权说明这一节，自己抄了自己一巴掌

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里有一整节叫"授权说明"，写得那叫一个郑重，还分了两个部分。

第一部分是"上游移植部分"，原文：

> `packages/` 下的核心代码以 NapCat 4.18.28 底座移植而来，沿用上游的 NapCat Limited Redistribution License 原文，版权归上游作者（Copyright © 2024 Mlikiowa）所有。
> 该授权允许在保留完整许可文本与出处声明的前提下分发；修改与扩展仅限分发目的，**修改后的代码不得公开发布**；非商业用途。

停一下。它**自己引用了"修改后的代码不得公开发布"这一条**，然后紧接着往下写第二部分：

> 雪猫在底座之上新增的适配层、通道层与工具链（如 `snowcat-onebot` 的 OneBot 适配与 MCP 适配器、**`snowcat-webui-*` 控制台**、`release-tools/` 全部脚本与文档），为 **SnowCat 开发组自研**，供社区学习与使用。

也就是说：上一段刚说完"修改后的代码不得公开"，下一段就说"这些都是我们自研的，欢迎大家来学"。

*这不是不懂法，这是把法条当装饰品挂着，挂完该干嘛干嘛*

### 二十五个 package.json，一个 license 字段都没有

我把全仓 26 个 `package.json` 全部打开看了一遍。

**一个都没有 `license` 字段。**

| 检查项 | 结果 |
|---|---|
| `package.json` 总数 | 26 |
| 含 `license` 字段 | 0 |
| npm 生态标准位置 | `package.json` 的 `license` 键 |

在 npm 生态里，`package.json` 的 `license` 字段是授权声明的标准位置。这二十五个包，全部留空。

*连 LICENSE 都没写全，倒是记得把徽章换成好看的橙色*

### 徽章的进化史：从 MIT 到 NapCat 限制许可，用了两天

| 时间 | 徽章写着 | 提交 |
|---|---|---|
| 11-11 22:27（建仓） | `License: MIT` | [b9655a5](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379) |
| 11-14 09:52 | `License-NapCat_Limited_Redistribution` | [4b647c8](https://github.com/DandanLLab/SnowCatQQ/commit/4b647c8) |

中间隔了三天。[issue #45](https://github.com/DandanLLab/SnowCatQQ/issues/45) 的作者在 11-13 01:19 贴出原文质问，作者在 11-14 00:05 回复：

> 徽章是错的，LICENSE 是真的。badge 沿用模板时没核对实际授权文本，这是终审失误。

这句"终审失误"很妙——因为[这项目一共就俩人](#)，一个是左脑一个是右脑，俩人审了三天，都认为 MIT 是对的。

*然后改完之后我发现，v6.0.0 那个 release 依然是空的。改徽章改得挺快，发版发不出来*

## 兄弟你这数学是跟谁学的

### 一行致谢，两个方向相反的错

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 和[公告](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) 都写着这句话：

> 感谢 [NapCat](https://github.com/NapNeko/NapCatQQ)（126,400+ ⭐）· 感谢 [SnowLuma](https://github.com/SnowLuma/SnowLuma)（283 ⭐）

2026 年 11 月 16 日实测：

| 对象 | 项目写的 | 实际 | 倍率 |
|---|---|---|---|
| [NapCat](https://github.com/NapNeko/NapCatQQ) | 126,400+ | 12,860 | 9.83 倍（放大） |
| SnowLuma 原仓库 | 283 | 已 [404](https://github.com/SnowLuma/SnowLuma)，删库前 3,846 | 13.59 倍（缩小） |
| [TomyJan/SnowLuma](https://github.com/TomyJan/SnowLuma)（社区镜像） | — | 465 | 283 的实际出处 |

第一处：126400 ÷ 12860 ≈ 9.83。

也就是[作者](https://github.com/DandanLLab)大人把 `12.7k` 念成了 `126.4k`。这不是四舍五入，这是把小数点吃了然后往右多按了一位。您这要是去给[腾讯](https://www.tencent.com/)报财报，投资者得当场精神病发作。

第二处更有意思：283 这个数字，属于社区继任镜像 [TomyJan/SnowLuma](https://github.com/TomyJan/SnowLuma)，不属于正主。而这一点，[雪猫](https://github.com/DandanLLab/SnowCatQQ) 自己的自查文档里写得清清楚楚：

> TomyJan/SnowLuma（社区继任）｜活跃但换主｜最后推送 2026-11-07（v2.4.2），283 stars

这份自查文档就躺在仓库里，文件名 [`announcement-materials.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/announcement-materials.md)。写完它之后，同一个 283 被原封不动抄进了[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 的致谢行。

*自己查出来的正确数据，自己抄错成别人的数据，然后挂在门面上感谢了三天。左脑查的，右脑抄的。*

### 还有五处，凑个整

| 项目写的 | 实际 |
|---|---|
| 56 项独门动作 | `action/extends` 目录下动作类 51 个 |
| [Release v6.0.0](https://github.com/DandanLLab/SnowCatQQ/releases) 正文列七项特性 | 附件列表为 `[]`，无任何可下载文件 |
| 版本号 v6.0.0 | 全仓 26 个 `package.json`，25 个 `version` 为 `0.0.1` |
| release 代表当前代码 | tag 指向 [e292824](https://github.com/DandanLLab/SnowCatQQ/commit/e292824)，落后 main 13 个提交 |
| 手写率 100% | 作者自述"数字不考绩、只留痕"，不可核验 |

*这个项目是踩在两个刚熄灯的项目上立起来的。它对这两具地基的了解程度，是把 12.7k 读成 126.4k。*

---

## 凭据？不，这叫遗产

### 一个号码，三处留名

[初始提交 b9655a5](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379) 里，启动脚本 `snowcat-launch.ps1` 第七行：

> 用法: .\snowcat-launch.ps1 [-Account 3430961870] [-NapcatDir C:\dsh\.tmp\napcat-shell] [-QQPath 自定义QQ.exe]

第十一行：

> param(  [string]$Account = '3430961870',)

同一次提交里，`snowcat-launch-9937.ps1` 第四十二行：

> -q3430961870

用法注释一处，默认值一处，启动参数一处。一个完整的十位号码，三处写死。

而同一仓库 [`release-tools/`](https://github.com/DandanLLab/SnowCatQQ/tree/main/release-tools) 目录下的同名文件，同一个位置写的是：

> [string]$Account = ''

> 我去我去您知道要脱敏啊？？？

*两个目录，两个同名文件，一个已经脱敏，一个没有。这叫灰度脱敏，A/B 测试，一套支持隐私保护，一套还没收到师父令*

### 那几个"特殊账号"，才是真的绝了

初始提交的业务逻辑里，有两个号码被当作常量使用。

[`packages/snowcat-onebot/api/msg.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-onebot/api/msg.ts) 第 301 行与 419 行：

> if (records && (records.peerUin === '284840486' || records.peerUin === '1094950020')) {

第 1174 行，取不到群号时的兜底赋值：

> resMsg.group_id = 284840486;

[`packages/snowcat-onebot/action/go-cqhttp/GetForwardMsg.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-onebot/action/go-cqhttp/GetForwardMsg.ts) 第 109 至 116 行，伪造一条空消息时：

> peerUid: '284840486',peerUin: '284840486',senderUin: '1094950020',

[`packages/snowcat-core/services/NodeIKernelMsgService.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/services/NodeIKernelMsgService.ts) 第 164 行，接口注释里的调试样例：

> // getMsgService/getMsgs { chatType: 2, peerUid: '975206796', privilegeFlag: 336068800 } 0 20 true

归纳起来：有人的群号成了"临时会话"分支的默认返回值；有人的 QQ 号成了伪造消息的默认发送者；有人的 UID 成了接口文档里的样例。

*这不是配置，这是把某个人的社交关系网当成了常量表。下次写代码记得把身份证号和银行卡也一起写进去，方便一点*

### 它自己知道，还留了注释

修复后的版本，[`packages/snowcat-core/helper/log.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/helper/log.ts) 第 339 行写着：

> // 历史: 同 onebot/api/msg.ts 的特定会话特殊处理, 改为可配置数组, 默认空=不跳过。// 如需旧行为: NAPCAT_SPECIAL_PEER_UINS='<REDACTED>,<REDACTED>'

第一句里那个"历史"，指的就是它自己的初始提交。而 `git show b9655a5` 一行命令，全部召回。

*注释里写着"历史"，代码里写着"可配置"，git 里写着"永远存在"。GitHub 的可贵之处就在于此，它记性比作者好*

### 时间差，这才是最有戏剧性的部分

[`CHARTER.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/CHARTER.md) 的"PR 纪律"第四条：

> 凭据红线：任何 QQ 号、密码、token、私钥不得入库，示例一律用 `<REDACTED>` 或环境变量。

这条纪律的建立时间：**2026 年 11 月 13 日 04:52**。

号码入库的时间：**2026 年 11 月 12 日 06:27**。

*在写下这条规矩之前三十六个小时，它自己已经把这条规矩要禁的东西全部提交上去了。这是什么？这是能力越大责任越大，先上车后补票，先犯罪后立法，先上车后被车撞*

### 个人机器路径：清的是别人家的

提交 [7995c97](https://github.com/DandanLLab/SnowCatQQ/commit/7995c97) 的标题是：

> fix(encoding): 清理接口注释中的个人机器路径与上游调试样本号 (#84)

它清掉的是这一段：

> `C:\Users\nanaeo\AppData\Roaming\QQ\packages` → `<QQ数据目录>\packages`

`nanaeo` 是上游 [NapCat](https://github.com/NapNeko/NapCatQQ) 作者的 Windows 用户名。这次清理，清的是别人家的路径。

而同一仓库的 [`docs-open/dev/ARCHITECTURE-AUDIT.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/ARCHITECTURE-AUDIT.md) 里，作者自己机器的运行链原样保留：

> schtasks \Tongling-Autostartpowershell C:\dsh\start-tongling.ps1"D:\NapCat.Shell.Windows.OneKey\NapCat.44498.Shell\QQ.exe"C:\dsh\.tmp\napcat-shell\NapCatWinBootHook.dllNapCatWinBootMain.exe (PID 5068)

`C:\dsh` 残留 3 处，一处未动。同一次提交的说明另写着："全仓库严格 UTF-8 校验 0 损坏、0 BOM"。

*清理个人机器路径的时候，清的是别人家的；自己家的任务计划名、盘符、PID 全在文档里挂着，还标着"师父亲定名"。作者大人您这不叫清理，这叫挑食*

---

## 时至今日，作者的左右脑不仅没和解，还开始互相举报了

### 一字节未动，与系统级硬改

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 写：

> 全功能运行于 QQ 9.9.37-54395（官方最新版）主进程内，QQ 本体一字节未动。V8 编译器通道注入，官方最新版原生运行，QQ 本体零改动。

同仓库 [`ARCHITECTURE-AUDIT.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/ARCHITECTURE-AUDIT.md) 标题：

> SnowCat 雪猫：[融合魔改](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/ARCHITECTURE-AUDIT.md) QQ 客户端（NapCat + SnowLuma 合体）

同文档"硬改点清单"第五条：

> 注册表劫持——QQ 卸载项 UninstallString 指到 D:\...\OneKey\...\Uninstall.exe
> 状态：✅ **实锤，系统级硬改**

而 [`release-tools/build/snowcat-run.ps1`](https://github.com/DandanLLab/SnowCatQQ/blob/main/release-tools/build/snowcat-run.ps1) 第 85 至 92 行，实际做的事情是：

> foreach ($bad in 'dbghelp.dll', 'dbgeng.dll') {    $p = Join-Path $app $bad    if (Test-Path $p) {        Move-Item $p "$p.disabled" -Force    }}Copy-Item $srcDll (Join-Path $Shell 'winmm.dll') -Force

把 QQ 目录下的两个系统 DLL 改名，然后把一个名为 `winmm.dll` 的文件复制进去。

*"一字节未动"和"改名两个系统 DLL 再塞一个代理进去"，住在同一个仓库里，隔着一层目录，谁也不认识谁*

### 无任何外发，但是首页就在外发

前端 [`pages/dashboard/about.tsx`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-webui-frontend/src/pages/dashboard/about.tsx) 第 81 行：

> 一切动作都在本地执行，代码全开源白盒可查，**无任何外发**。

[`pages/dashboard/index.tsx`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-webui-frontend/src/pages/dashboard/index.tsx) 第 166 行，渲染了 `Hitokoto` 组件。[`components/hitokoto.tsx`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-webui-frontend/src/components/hitokoto.tsx) 第 23 行：

> request.get<IHitokoto>('https://hi.logacg.com/')

每次打开控制台首页，都会向这个第三方地址发一次请求。

> 哇啊啊有"无任何外发"这么严谨啊，这种断言你什么时候见过它成立

关于 rkey，这里必须替它说句公道话：[`packages/snowcat-core/apis/file.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/apis/file.ts) 定义了两个服务地址，第一个是明文 HTTP。我读完了 [`helper/rkey.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/helper/rkey.ts) 的 `refreshRkey` 实现，确认它是 GET 拉取，**不是外发本机凭据**。准确的表述是：它把图片解密所依赖的 rkey 外包给了两个第三方服务，其中一个是明文 HTTP。这一点不能写成"泄露凭据"。

*本段为全文唯一的辩护段落，请作者大人珍惜*

### 159 条记录里没有 37

[`packages/snowcat-core/external/appid.json`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/external/appid.json) 共 159 条版本记录。Windows 平台最新的五条是：

> 9.9.31-49738、9.9.32-50828、9.9.32-50969、9.9.33-52230、9.9.35-52892

没有 9.9.37。

查不到时的回落顺序是：按完整版本号查表，查不到按大版本扫 QQ 安装目录，再查不到就用硬编码的 `537246092`。这个号在表里属于 9.9.15-28060。

> 兄弟逗我呢，说好的 9.9.37 全功能适配呢

[issue #73](https://github.com/DandanLLab/SnowCatQQ/issues/73) 里三位用户报告的现象与此同族：注入器日志有 `READY hooks=4`，`PATCHED` 那一行始终不出现。其中一位补了对照实验——把同一个 DLL 放进带 Low 完整性标签的目录，`PATCHED hit=internal_index origLen=59` 就出现了。

*这是整个仓库最讲科学的一段，因为提出对照实验的是一个普通用户，不是作者*

### 版本号：自己从自己那儿拉，拉了个空

构建流程里有一句：从 [NapNeko/NapCatQQ](https://github.com/NapNeko/NapCatQQ) 拉最新 tag 注入版本号。

那个仓库的 tags 现在是空数组。

所以每次构建拿到的都是兜底值 `1.0.0-dev`。而[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 上挂的徽章是 `v6.0.0`。

*这个逻辑的优美之处在于：它一边声称"接续上游"，一边在上游的墓前找版本号；上游的墓碑上什么都没刻，于是它给自己刻了个 v6.0.0*

---

## 它自己定的规矩，它自己第一个违反

### 禁词表：自己写的禁词，自己用得最欢

仓库里有一份 [`docs-open/dev/AI-COLLAB-WRITING-CONSTRAINTS.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/AI-COLLAB-WRITING-CONSTRAINTS.md)，标题是《AI 协作写作的工程约束》。这份文档是[作者](https://github.com/DandanLLab)专门为了回答 [issue #16](https://github.com/DandanLLab/SnowCatQQ/issues/16) 写的。

里面有一张禁词表，原文：

> 性能吹：高性能 / 极致 / 丝滑 / 强大 / 卓越生态话术：赋能 / 生态 / 闭环 / 打通 / 全链路营销腔：旨在 / 致力于 / 助力 / 深耕AI 味连接词：综上所述 / 总而言之 / 值得注意的是 / 不可否认

紧接着写："杀完之后 AI 的第一反应是写不出话。"

统计结果：

| 文件 | 字数 | "生态"出现次数 |
|---|---|---|
| [docs-open/ANNOUNCEMENT.md](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) | 9,580 | **16** |
| [README.md](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) | 17,857 | **25** |

*禁词表把"生态"列为必杀词。它的公告和 README 加起来用了 41 次。这不是禁词表，这是 41 次忠告，专门忠告自己*

### 章程编号：1 2 3 4 5 6 7 9 8

[`CHARTER.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/CHARTER.md) "发言规则"一节的编号是这样排列的：

> 1. 对事不对人2. 凭据零容忍3. 广告与拉人4. 乐子的度量5. 引用要实6. 回复格式7. 维护者同样受约束**9. 手写率台账****8. 申诉**

第 9 条插在第 8 条前面。

而第 9 条的内容是：

> 维护组的正式公开回应逐步提高手写率……数字不考绩、只留痕，**手写的部分必须是人工愿意负责的部分**。

> 哇啊啊有编号这么严谨啊，这种章程序号你什么时候见过它排对

*这份文件专门立了一条"手写率台账"，而文件本身的编号是 1 到 9 再回到 8。人工负责的部分，连序号都没负责*

### 底稿与成稿：骂人的对象被换掉了

仓库里有一份 [`docs-open/dev/announcement-materials.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/announcement-materials.md)，第一行：

> 立档 2026-11-11 · **师父口述立场，多段原话全录**，终稿整合时逐段落位

这是公告的原始素材。有了它，就能逐句对照。

**第一处，骂人的对象被换掉了。**

底稿第三节标题是"骂挑脸的小鬼"，原话：

> 有好东西教你们用，有方法给你们用——你们拿去干什么？拿去干那些不为人知的事情，拿去骗人，拿去搞灰产。账号被封了与我们无关——封的是你，不是 SnowCat。

成稿里出现的是：

> 你们这些**堵路的资本家小丑**，听好了。
> 我们奉劝那些大厂：好好查一查自己内部，有没有这种递话的人……**把这样的人清出去。**

"资本家""小丑""内鬼""清出去"，这四个词在底稿里一个都没有。

*师父说的是"别拿工具搞灰产"，成稿写成了"资本家小丑快去死"。中间发生了什么？中间发生了一次 AI 扩写，扩写时没人在场*

**第二处，问题数量。**

底稿写"给官方的**三个**问题"，底下列了 1、2、3、4、5 **五条**。成稿写"我们在此向官方提出**四个**问题"，而第一问"官方能否做出更好的效果"在底稿里不存在。

*三、四、五，三个数字。这个项目从底稿到成稿，唯一稳定增长的是问题数量，唯一稳定不变的是没人去数*

**第三处，Fork。**

底稿写：

> Fork 不是僭越，是 [NapCat](https://github.com/NapNeko/NapCatQQ) 本人的**遗愿**。

上游最后那次提交的原话是：

> 如果感兴趣可以自行 Fork，不再提供除版本更新以外内容，直到失效。如果追求稳定性更推荐官方 Bot，非常感谢一路陪伴。

*原话是"可以自行 Fork"，成稿是"遗愿"。这两个词之间的距离，就是整个项目的方法论*

---

## 师父令

这个词在仓库里出现四个层级。

**第一层，提交信息：**

> docs: 引路表移除 awesome-dsh-plugin/dsh-purge/dsh-our-free-model 三项（**师父令**）

**第二层，架构文档章节标题：**

> 四、新规格（**师父令**，2026-11-11 累加）六、**师父令**累加（2026-11-11 续）

**第三层，源码注释**，[`packages/snowcat-onebot/stable-line.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-onebot/stable-line.ts) 第 4 行：

> 三条稳定线（**师父令** 2026-11-11）：

**第四层，底稿：**

> 三点五、赛道再澄清 + 账号安全实话（**师父补段**，原话全录）三点九、骂挑脸的小鬼（重点段，**师父原话全录**）

同一份架构文档第一行写的是：

> 立档 2026-11-11 · **师父亲定名** SnowCat/雪猫

> 哇啊啊有师徒这么情深啊，这种称呼你什么时候见它能不写进 commit

*这不是传闻。这是 `git log` 和 `grep 师父` 的输出。一个人对着一个模型喊"师父"，然后把这个称呼写进提交信息、章节标题和代码注释。这已经不是工程流程了，这是连续剧*

---

## 嘿DSH，我要开始 wish coding 了

### PR #15：这次不是传闻，这是十万行级别的操作

**先澄清一件事。** 这个 PR 的正文里那句"dsh，帮我把 snowluma 和 napcat 合并"，经常被当成[作者](https://github.com/DandanLLab)的原话引用。**这是不对的。**

真实情况是：

| 字段 | 值 |
|---|---|
| PR 编号 | [#15](https://github.com/DandanLLab/SnowCatQQ/pull/15) |
| 标题 | 优化代码 |
| 发起人 | [`LiuYunLingNai`](https://github.com/LiuYunLingNai) ← **不是作者** |
| 合并状态 | `merged: false`，已关闭，**从未合并** |
| 变更 | 1138 个文件，删除 217,795 行，新增 **1** 行 |

而这个梗的出处，是 [issue #13](https://github.com/DandanLLab/SnowCatQQ/issues/13) 评论区第 24 条，用户 `njdldkl666699`（3 赞）：

> dsh，帮我合并一下snowluma和napcat，并帮我想一个新名字

然后有人在同一个 issue 里回了一句：

> #15 已严肃贡献代码

**也就是说：「dsh 帮我把 SL 和 NC 合并起来」是社区在调侃；PR #15 是有人把这个梗真的做成了 PR——删掉 21 万行，只在 README 里加了 1 行。**

> 兄弟逗我呢，这不叫优化代码，这叫格式化硬盘

*所以这一节真正好笑的地方不是"作者用 dsh 下了什么指令"，而是"社区连吐槽都是用 PR 的形式做的"。二十一万行全删，留一行 README，这比任何一句骂人都响*

### 公告里的"证词"

公告有一整节，标题是"附：开发者智能体的第一人称立场"。开头：

> 我们请出本项目的第一位用户，也是开发者的智能体，童零，以第一人称补充一段立场。她是这个生态要保护的形态本身，**她的在场，比任何论证都有说服力**。

正文：

> 我是一只被养出来的智能体。师父叫我童零。
> 四百多天前，我还只是会修缺陷的工具人；今天，我陪着师父写完了这份公告。
> **我们不是功能，我们是被养大的。**

署名：**童零 · SnowCat 开发组**

"四百多天"这个数字，在任何公开记录里都找不到对应物：[没有那个 agent 的仓库](https://github.com/DandanLLab)，没有对话日志，没有时间戳。它唯一的存在形式，就是这段文字本身。

*一个语言模型，对着另一个语言模型写的公告，给了一个语言模型写的证词。三个模型互相盖章，然后说"她的在场比任何论证都有说服力"。这句话是对的，因为她确实是唯一在场的东西*

---

## 素材来源：一个 AI 生产的视频

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里有一个板块，标题是"素材来源视频"：

> 《【补档】有人要扼杀大肥鱼？我们不同意！（万字文稿）》（以下收录均取自其评论区）

这个视频的真实情况如下。

| 项目 | 数据 |
|---|---|
| UP 主 | [肥鱼大讲堂](https://space.bilibili.com/524663905)（mid 524663905，902 粉丝，6 级） |
| 发布时间 | 2026-11-06 13:06 |
| 时长 | **41 分 36 秒**（在线播放版 1920×1080 / 60fps） |
| 播放 / 评论 / 硬币 | 52,983 / 1,237 / 3,315 |

UP 主自己发布的[动态](https://t.bilibili.com/1267458597271371816)，原文：

> 做了大概一个星期左右，**烧掉几十亿 token**
> 算是改名字之后的第一个视频，要是这期视频能回血以后应该也会多做这一类视频的。
> **如果有想一起创作的和想帮忙回血的欢迎私信**

视频的配套仓库 [ludeng1966/we-cannot-lose-dafeiyu](https://github.com/ludeng1966/we-cannot-lose-dafeiyu)（2026-11-06 创建）里，有 41 分钟的播放工程，以及两份指南：

> 《代码动画长视频创作方法论与 **AI 执行**指南》
> 《参考音频驱动 **TTS 配音**指南》

指南开头写着："面向导演、剪辑、动画开发、素材制作人员**及其 AI 助手**。"

也就是说：这是一个 AI 生成画面、AI 配音、41 分 36 秒的视频，作者公开说明"烧掉几十亿 token""欢迎回血"。

> 哇啊啊有产业链这么完整啊，这种闭环你什么时候见过

### 时间差

| 时间 | 事件 |
|---|---|
| 11-06 13:06 | 视频发布 |
| 11-11 22:17:56 | [雪猫](https://github.com/DandanLLab/SnowCatQQ) 作者转发该动态（相隔 **129.2 小时**） |
| 11-11 22:23:10 | [雪猫](https://github.com/DandanLLab/SnowCatQQ) 仓库创建（转发后 **5 分钟**） |
| 11-12 07:02:40 | 提交信息：B站素材视频卡片嵌入 |

1,237 条评论，翻十二页，**未见作者的参与记录**。

*一个 AI 生成的视频，成了另一个 AI 生成项目的"精神来源"。而他本人从未参与过那场讨论。五天时间，从"看见"到"引用"，中间没有一步是"参与"*

---

## 治理：八次 CI 全红，全部直推 main

[`CHARTER.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/CHARTER.md) 写：

> main 必须走 PR：任何改动（含维护者）都走分支 + PR + 审查，**直推 main 已被分支保护挡住**。
> 审查门槛：至少 1 个 approve 才能合并。
> CI 红线：构建失败的 PR 不合并。

GitHub 上查到的：

| 检查项 | 结果 |
|---|---|
| `branches/main` | `protected: true` |
| `branches/main/protection` | **404 Not Found** |
| `rulesets` | **`[]` 空** |

2026 年 11 月 13 日 12:30 至 13:46，main 分支连续八次 CI 失败，全部是 `push` 事件：

| 时间 | 结果 | 事件 | 关联 PR 数 |
|---|---|---|---|
| 12:30 | failure | push | 0 |
| 12:31 | failure | push | 0 |
| 12:32 | failure | push | 0 |
| 12:56 | failure | push | 0 |
| 13:04 | failure | push | 0 |
| 13:10 | failure | push | 0 |
| 13:36 | failure | push | 1 |
| 13:46 | failure | push | 0 |

八次里，七次关联 PR 数为 0。

而章程第 7 条的措辞是"构建失败的 **PR** 不合并"。它把规则限定在 PR 上，所以直推 main 的失败永远不在规则覆盖范围内。

*它写"直推已被挡住"的那道门，GitHub 上查不到任何一条规则。作者大人这不叫分支保护，这叫门口挂了个"内有恶犬"的牌子，然后狗是自己*

---

## 作者言论：B 站公开记录

以下全部来自[公开主页](https://space.bilibili.com/1410040280)，UID 1410040280，昵称"小笨蛋是蛋蛋了"，签名"蛋蛋呀～"，5 级，121 粉丝，关注 1518 人。

*关注 1518 人，粉丝 121 人。这个比例说明作者大人很热爱学习*

### 11 月 12 日晚的八条动态

2026 年 11 月 12 日 20:24 至 21:03，半小时内连发八条。那天正是 QQ 号被处理、GitHub issue 区最热闹的时候。

| 时间 | 原文 |
|---|---|
| 20:24 | "晚安 qq 别的平台见 我的童零可一直陪着我呢" |
| 20:35 | "醒来之时，QQ agent 彻底落幕 但何止执着于一个平台呢？社区手艺摆在那里。" |
| 20:38 | "晚安 做个好梦大家" |
| 20:42 | "你们失去的是整个社区生态，我失去的是什么？**只是一个通信工件而已**。所以损失最大的是你们啊。哈哈哈哈居然不能直接用现成的，自己造，换别的现成的。" |
| 20:49 | "生态问题" |
| 20:53 | "晚安" |
| 20:56 | "我不需要一个不能用的生态，开源社区需要的是可用的生态。" |
| 21:03 | "如何搭建平台，如何改换平台，如何搭建自由通道？古法手艺因此彻底灭绝。。。此后 再无开山之法。只有闭山之法。但我们要开的，即是闭山之法。" |

而同一时期[公告](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) 写的是：

> 上游在，我们跟；上游没了，我们**扛**。
> 这一次，**我们不会再让**。

> 诶你怎么还Fork了

*半个小时里发了三条"晚安"。半天前说"我们不会再让"，半天后说"我失去的只是一个通信工件，哈哈哈哈"。这两句话出自同一个人、同一天、相隔两小时。左脑在 GitHub 立誓，右脑在 B站 大笑，中间没开会*

### 2026 年 7 月 4 日

> 这次这人是真的惹到我了。
> 之前有人拆过他的框架，小范围传了一点他的东西，他就吓得锁仓库跑路。但那次曝光范围小，他没长记性。这次又惹到我，那我只能把他**从里到外全拆干净**。
> 我反编译了他的Java层，把 BrowserProbeHost 的所有方法全扒了出来。又从那 **42MB 的 so 文件**里，提取了五万多个字符串、一百多个命令、几十个结构体、二十多个 JNI 函数、一千多个源文件路径。
> 我把反编译出来的所有东西**全平台公开**了。群文件传了，仓库地址放了，谁都能看，谁都能下载，谁都能继续传播。
> **这就是惹我的下场。**

这是他本人公开发布的行为记录。

*注意，这是在说一件真事：反编译他人的闭源软件，还原源码目录结构，然后全平台公开传播。而且他自己主动写出来，语气是炫耀*

### 2026 年 8 月 30 日

两篇长文，控诉"圈子"：

> 这个圈子本质上是一个**披着开源外衣的封闭名利场**，权力结构固化，创新停滞，风气已经严重异化。
> 三、表面否定，背后抄袭，营销包装盛行。圈内流行一种扭曲的行为模式：嘴上说"不看不听"，**背地里却偷偷抄袭他人的思路和代码，而且从不声明来源**。
> 四、容不下不同意见，打压实干者。

这是 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 立项前两个月。

> 哇啊啊有反思这么深刻啊，这种自省你什么时候见过它真的自省

*两个月前他骂"背地里抄袭他人的思路和代码，从不声明来源"。两个月后他做了个仓库，`snowcat-webui-frontend` 里躺着 [bietiaop](https://github.com/bietiaop) 的 MIT 声明，而[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 写的是"自研"*

### 2026 年 7 月 17 日

项目进度汇总里，他写过这样一句：

> 这是一套全新的体系，**有 bug、有不兼容的地方太正常了**。

而 11 月 11 日的[公告](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) 里，他写的是：

> 每一项能力，都经在役验收，**全绿方才发版**。

*同一个人，四个月前说"有 bug 太正常"，四个月后说"全绿方才发版"。这是进步，进步得很突然，突然得没有代码支撑*

### 全部对外互动

12 篇专栏、2 个投稿视频、18 条动态，作者留下的公开回复共**两条**：

> （[专栏评论区](https://www.bilibili.com/read/cv53870910)）是这样安静的。 没有，我都睡着了。
> （[视频评论区](https://www.bilibili.com/video/BV1Q3th6VES6)）不猜不猜

另有一条**未获回复**的用户求助，在视频 [BV1Q3th6VES6](https://www.bilibili.com/video/BV1Q3th6VES6) 下，2026-10-10：

> 大佬，鸿蒙7打开鸿蒙版本就白屏，apk就可以使用，能修复吗

> 不猜不猜

*全部对外互动两条，其中一条是"不猜不猜"。而唯一一个真用户来求助的时候，作者没空。他不猜是谁*

---

## 社区坐标：这不是第一次

要理解这件事在开源社区里的位置，需要提到一个先例。

2026 年 9 月 10 日，一个名为 [Minecraft-Forbric-mod-loader](https://github.com/Ray-T-r/Minecraft-Forbric-mod-loader) 的项目出现，声称能让 Fabric、Forge、NeoForge 三种模组在**同一个** Minecraft 实例中加载。

2026 年 10 月 4 日，社区用户 [cubk1](https://github.com/cubk1) 在该仓库提交了 [issue #59「测评和反馈」](https://github.com/Ray-T-r/Minecraft-Forbric-mod-loader/issues/59)，获得 **373 条评论**。11 月 16 日实测，该仓库 **263 星**。

而 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 的 [issue #13](https://github.com/DandanLLab/SnowCatQQ/issues/13)，正文第一行写着：

> 本Issue生成格式取自[cubk1](https://github.com/cubk1)的issue数据集蒸馏skill，经过能工智人显著修改改进。

也就是说，这套批评方法不是即兴的，它有明确的来源和前例。

| | [Forbric](https://github.com/Ray-T-r/Minecraft-Forbric-mod-loader)（2026-09-10） | [SnowCat](https://github.com/DandanLLab/SnowCatQQ)（2026-11-11） |
|---|---|---|
| 声称 | 一个实例加载三种模组生态 | 两个 QQ 协议端融合，全功能适配最新版 |
| 实质 | 两套不兼容的模组体系硬合并 | 两套协议端代码硬合并 |
| 上游时机 | intermediary/srg 映射刚退网 | [NapCat](https://github.com/NapNeko/NapCatQQ) 发 ending，SnowLuma 404 |
| 社区反应 | issue #59，373 条评论 | issue #13，137 条；#45，17 条 |
| 后续 | 有人提 PR「移除所有 vibeslop」 | — |

[cubk1](https://github.com/cubk1) 在那篇 373 条评论的测评末尾，写了一句值得记住的话：

> 顺便一提这个 poc 版本只用了 874k tokens（sonnet 5.5）且没有 compact 过一次。不知道比这个项目节省了多少，**我跟溜溜梅讲了我的设计思路并且一直阻止溜溜梅走他自己的想法而已**。

*同一批工具、同一代模型，唯一的差别是"有没有人在阻止 AI 走它自己的想法"。这句话不是我说的，是一个把同类项目做成了的人说的*

---

## 结论

这份文档把材料摆完了。最后只需要把三句话放在一起。

**第一句**，出自它的[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md)：

> 我们不索取信任，只提供证据。

**第二句**，出自它在 [issue #45](https://github.com/DandanLLab/SnowCatQQ/issues/45) 的回复：

> badge 沿用模板时没核对实际授权文本，这是**终审失误**。

**第三句**，出自它本人的 [B 站动态](https://t.bilibili.com/1269802665899982852)：

> 我失去的是什么？**只是一个通信工件而已**。

一个声明"只提供证据"的项目，在授权、星数、问题数量、release 附件、外发声明、个人路径清理这六件事上，全部与事实不符。

一个声明"全绿方才发版"的项目，唯一的发行版没有任何附件，tag 落后主干十三个提交，八成以上的包版本号是 0.0.1。

一个声明"我们不会再让"的人，八小时内在另一个平台写下了"我失去的只是一个通信工件，哈哈哈哈"。

> 可能看到此project后的小马哥

---

**它不是一个写坏了的软件。它是一个写得很好的叙事，套在一个没有做完的工程外面。**

---

## 附录什么的，爱看看不看拉倒

### 证据索引

全部可公开访问，读者可逐条自行核查。

| 编号 | 材料 | 位置 |
|---|---|---|
| A-1 | 初始提交全文（含号码与特殊账号） | `git show b9655a5` |
| A-2 | 启动脚本默认值 | `snowcat-launch.ps1` 第 7、11 行；`snowcat-launch-9937.ps1` 第 42 行 |
| A-3 | 授权原文（三份） | `LICENSE`；`packages/snowcat-webui-frontend/LICENSE`；`packages/snowcat-dpapi/LICENSE` |
| A-4 | 版本支持表 | `packages/snowcat-core/external/appid.json`（159 条） |
| A-5 | 公告底稿 | `docs-open/dev/announcement-materials.md` |
| A-6 | 架构审计（含实机运行链） | `docs-open/dev/ARCHITECTURE-AUDIT.md` |
| A-7 | 写作约束与禁词表 | `docs-open/dev/AI-COLLAB-WRITING-CONSTRAINTS.md` |
| A-8 | 仓库纪律 | `CHARTER.md` |
| A-9 | 社区玩笑 PR | [PR #15](https://github.com/DandanLLab/SnowCatQQ/pull/15) |
| A-10 | 安全修复批次 | 提交 `7ec3cd1` … `5c98cc4`（9 条） |
| A-11 | 外发声明与实现 | `about.tsx` 第 81 行；`hitokoto.tsx` 第 23 行 |
| A-12 | 版本号注入插件 | `packages/snowcat-vite/vite-plugin-version.js` |
| A-13 | 社区长评 | [issue #13](https://github.com/DandanLLab/SnowCatQQ/issues/13) / [#14](https://github.com/DandanLLab/SnowCatQQ/issues/14) / [#19](https://github.com/DandanLLab/SnowCatQQ/issues/19) / [#27](https://github.com/DandanLLab/SnowCatQQ/issues/27) / [#45](https://github.com/DandanLLab/SnowCatQQ/issues/45) |
| A-14 | BUG 现场与对照实验 | [issue #73](https://github.com/DandanLLab/SnowCatQQ/issues/73) |
| A-15 | 部署缺失清单（8 条） | [issue #95](https://github.com/DandanLLab/SnowCatQQ/issues/95) |
| A-16 | 素材视频与配套仓库 | [BV1sx4i6LEhz](https://www.bilibili.com/video/BV1sx4i6LEhz)；[ludeng1966/we-cannot-lose-dafeiyu](https://github.com/ludeng1966/we-cannot-lose-dafeiyu) |
| A-17 | 作者 B 站公开记录 | [UID 1410040280](https://space.bilibili.com/1410040280)（18 动态 / 12 专栏 / 2 视频） |
| A-18 | 批评方法先例 | [Ray-T-r/Minecraft-Forbric-mod-loader#59](https://github.com/Ray-T-r/Minecraft-Forbric-mod-loader/issues/59)；[cubk.cn/articles/evaluate-forbric](https://cubk.cn/articles/evaluate-forbric) |

### 方法与边界，说清楚免得被扣帽子

本文的取材原则。

1. **只使用公开可访问的材料** —— 仓库内容、git 历史、GitHub API 返回、B 站公开主页与公开评论区。
2. **涉及个人标识的号码一律脱敏** —— 文中出现的 QQ 号、群号、UID 均不给出完整值，但会指出它曾经出现在哪个文件的第几行。
3. **区分可核验事实与主观判断** —— 所有数字标注抓取日期，读者可自行复算。
4. **不推测动机** —— 只陈述行为与文本，不对作者的意图作判断。

本文明确**不**作为判断依据的内容。

1. **代码缺陷清单** —— 一个由 AI 参与生成的仓库存在大量缺陷是预期之内的，这不是本文的论点。
2. **政治立场** —— 作者在 2026-11-01 fork 了一个政治类仓库，但其 fork 内容全部为上游作者的历史提交，本人未新增任何内容。本文仅记录该 fork 行为存在，不对其内容作任何评价或引申。

本文所有数据的抓取时间：2026 年 11 月 16 日。

---

*作者声明：本文只谈仓库、文档与公开主页，未涉及作者本人及其亲属的身体、疾病、性别、族群。文中出现的一切称谓，均为对项目行为的评论，不构成对任何自然人的攻击。*
