# github笑传之会员制协议端

> 分析对象：DandanLLab/SnowCatQQ　·　数据抓取：2026 年 11 月 16 日　·　材料范围：公开仓库、公开主页、公开评论区

<img width="1280" height="720" alt="28c7963ea4aa7684eb94021ed3cee2f7_720" src="https://github.com/user-attachments/assets/531ebbcd-1451-442d-b770-aae730efc81c" />

> 因为使用到了[Snowcat](https://github.com/DandanLLab/SnowCatQQ)成为[食雪汉](https://baike.baidu.com/item/%E6%88%91%E4%BF%AE%E9%99%A2?fromtitle=%E9%A3%9F%E9%9B%AA%E6%B1%89&fromid=65211459&fromModule=lemma_search-box)而面露难色的两位 QQbot 用户

> [!IMPORTANT]
> *声明：本文底稿的大部分篇幅均由ai生成，考据方面均review完成，且经某碳基本地大模型修改后呈现效果显著提升*
> **值得注意的是**，snowcat已经归档了，本文仅供鞭尸。btw，幽默地来讲大家等sc头七的时间会比sc的寿命还长
---

## 为啥会有这事

2026 年 11 月 10 日，随着[南山必胜客](https://baike.baidu.com/item/%E5%8D%97%E5%B1%B1%E5%BF%85%E8%83%9C%E5%AE%A2?fromModule=lemma_search-box)的两纸律师函被祭出，[NapCat](https://github.com/NapNeko/NapCatQQ)项目发布最后一次提交，标题为ending，正式跑路了，同日SnowLuma仓库也从 GitHub 消失，返回 404，空悲切。不过人们发现在 24 小时后，一个名为[SnowCatQQ](https://github.com/DandanLLab/SnowCatQQ)（下简称[雪猫](https://github.com/DandanLLab/SnowCatQQ)）的仓库出现在 GitHub 上。其对外宣称把 [NapCat](https://github.com/NapNeko/NapCatQQ) 与 SnowLuma 两套代码融合且全功能适配 QQ 9.9.37，拥有所谓的56 项独门动作，MCP 接入，全线开源，持续维护

<img width="1844" height="1336" alt="image" src="https://github.com/user-attachments/assets/63bc28d5-c808-4f1d-b741-d4099841b9a8" />

> 哇啊啊有制作这么精良的logo，这种协议端你什么时候用

光看名字就知道是要吃[nc](https://github.com/NapNeko/NapCatQQ)和sl的[人血馒头](https://baike.baidu.com/item/%E4%BA%BA%E8%A1%80%E9%A6%92%E5%A4%B4?fromModule=lemma_search-box)，打算趁着两个协议端跑路包圆这一块的热度，[重大历史鲫鱼](https://zhuanlan.zhihu.com/p/590904864)这块。事实上其开发者称自己的行为为“接续先行者铺下的路”；那么这个仓库在开源社区里究竟是一个什么东西呢？


史家据史直书，一字不改！

且不说[拉格兰](https://github.com/LagrangeDev/Lagrange.Core)这种还在更新的协议库（它甚至已经把自己的 OneBot 端换成 Milky 了而与此同时[SnowCatQQ](https://github.com/DandanLLab/SnowCatQQ)还在 [读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里把 Milky 当成自己的兼容层卖点）；事实上倘若[雪猫](https://github.com/DandanLLab/SnowCatQQ)是个好协议端，在开源社区继续维护已经归档的仓库此类行为本身也是个好事——但是这个仓库实在是极为抽象以至于我在多个技术交流为主的QQ群都看到有群u对此事件发表锐评了，本着实事求是、真理越辩越明的想法，我想我也必须得加入对此仓库进行的轰轰烈烈的真理大讨论

全文除了玩梗不掺杂纯粹人身攻击，要说不带感情来评价这坨[旷世巨奋](https://github.com/DandanLLab/SnowCatQQ)是不可能的了因为我不相信有人看完这个仓库底下的一些 [issue](https://github.com/DandanLLab/SnowCatQQ/issues/13) 能忍住不笑出来以至于不产生“这波贪了应该再等几个月留着春晚看的”的想法——故请读者读完**自行得出自己的结论，不要跟着我起哄**，一人做事一人担

<img width="1080" height="1480" alt="image" src="https://github.com/user-attachments/assets/eee93628-4ba1-4377-af7d-99924cf52979" />

### 定论：彻彻底底的 [AI SLOP](https://baike.baidu.com/item/AI%E5%9E%83%E5%9C%BE/67311830?fromModule=search-result_lemma)
事先叠甲：[本人](https://github.com/Wojusensei)绝对尊重开源精神，支持且甚至于实践着使用 ai agent 进行辅助开发甚至于是承担 99% 的代码工作的开发行为，只要是认真写好任务规划做好人工测试和 review 过核心模块的项目，使用ai并不会降低其含金量（提高生产力的事情为什么不做）。本人只反对一味鼓吹 ai 可以完全替代程序员、幻想利用ai可以不用学习任何东西就驾驭软件开发的傻逼而已（至少我认为这句话在2027年之前都是生效的）

<img width="1080" height="869" alt="a5bf9db307c7dc40eae26478f531c48b_720" src="https://github.com/user-attachments/assets/8a7d2189-3afe-469a-9afd-61acfca2b29d" />

> 事实上我也完全支持 [linus](https://baike.baidu.com/item/%E6%9E%97%E7%BA%B3%E6%96%AF%C2%B7%E6%9C%AC%E7%BA%B3%E7%AC%AC%E5%85%8B%E7%89%B9%C2%B7%E6%89%98%E7%93%A6%E5%85%B9?fromtitle=linus&fromid=400810&fromModule=lemma_search-box) 的意见

我不知道这玩意是怎么让[作者](https://github.com/DandanLLab)有信心讲自己是“墨家开山授徒，将守城之法、造械之术倾囊相授”的，可能是这神秘开发者给dsh的prompt里面叫agent称呼自己为“师傅”而ai本身又只能遵从用户的命令所以只好捏着鼻子陪ta玩这种小孩子都觉得中二病的[RP](https://baike.baidu.com/item/%E8%A7%92%E8%89%B2%E6%89%AE%E6%BC%94/68462)；总而言之给我的第一印象又是那种觉得“所有人都不会用ai只有我会”的[vibe coding](https://baike.baidu.com/item/%E6%B0%9B%E5%9B%B4%E7%BC%96%E7%A8%8B?fromModule=lemma_search-box)cosplay程序员的爱好者

为什么我要专门说一点关于人工测试的问题呢，因为根据社区反馈[雪猫](https://github.com/DandanLLab/SnowCatQQ)这个协议端根本就没有可用性，登上QQ之后十分钟内必触发你腾讯叔叔的风控导致bot账号被踹下线or直接喜提 30DAY 大礼包

Q：根本没有这样的协议端！
A：你只是怕了

<img width="1154" height="810" alt="e911c45a43a80f5c8f0810f3629a5c9c" src="https://github.com/user-attachments/assets/25d47632-e085-4b79-9c76-afa41a1939f3" />

> 腾讯对待[雪猫](https://github.com/DandanLLab/SnowCatQQ)协议端就这样：


只能说[开智](https://baike.baidu.com/item/%E5%BC%80%E6%99%BA/802721)了自己会删库系列，哪怕是没人反对你用 ai ，好歹你这项目也要能用吧
至今不知道仓库的 300+ star 到底是哪来的，只能说幽默社区的幽默开发者和ta的幽默用户神奇地达成了一种[傻子共振](https://xueshu.baidu.com/ndscholar/browse/search?wd=%E5%82%BB%E5%AD%90%E5%85%B1%E6%8C%AF&tn=SE_baiduxueshu_c1gjeupa&ie=utf-8&sc_hit=1)，如果没有明白人介入估计这种共振会持续到宇宙热寂
不幸的是，时至今日，我们的火力仍然倾泻在一只无辜的迫于 prompt 的压力不得不进行着诡异的 RP 的[蓝色大肥鱼](https://chat.deepseek.com/)身上

<img width="972" height="972" alt="5465ad966105cda549586050b160d04f" src="https://github.com/user-attachments/assets/de845ad8-5d41-42b8-b378-4123672ce515" />

> 作者眼里的所有人


当我看到那个[SVG](https://baike.baidu.com/item/%E5%8F%AF%E7%BC%A9%E6%94%BE%E7%9F%A2%E9%87%8F%E5%9B%BE%E5%BD%A2/22819739?fromtitle=SVG&fromid=63178)logo的时候我就知道开源社区又迎来了一坨属于它的大分，精美程度和[豆包](https://baike.baidu.com/item/%E8%B1%86%E5%8C%85%E5%B7%A5%E4%BD%9C?fromModule=lemma_search-box)画的[鹈鹕配自行车](https://baike.baidu.com/item/%E9%B9%88%E9%B9%95%E8%B8%A9%E5%8D%95%E8%BD%A6/69165703?fromModule=search-result_lemma)一桌，可谓是低山臭水遇至阴穷凶极恶双子星———很显然可以从文档语气等地方看出作者本人对此项目还算是骄傲的，而这样一个让其本人骄傲的项目居然有一个这么应付的招牌logo，有趣的是作者在提交记录中居然声称自己是手绘的，令人忍俊不禁
事实上，就作者[张顺飞·菲巴芬钱](https://tieba.baidu.com/f?kw=%25D5%25C5%25CB%25B3%25B7%25C9&fr=ala0&tpl=5&dyTabStr=MCwxMiwzLDEsMiwxMyw3LDYsNSw5)一样的连回复 issue 都需要重度依赖[溜溜梅](https://baike.baidu.com/item/%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B/62884793)进行代笔的语言表达能力堪比一根[滚木](https://zhuanlan.zhihu.com/p/1910498558249002272)的水准，你要让其写 prompt 估计真是强人所难，更别提对 ai 画出来的 svg 提什么修改意见了

<img width="1170" height="828" alt="cef167699c2a08b831f0a18bb89ef25e" src="https://github.com/user-attachments/assets/62928d3d-1d07-4d54-98a5-d44ca1f0a510" />

> 作者的审美堪比两斤牛肉

不可否认的是，[作者](https://github.com/DandanLLab)是一名熟练使用类 **Chinese++** 编程语言进行开发的优秀程序员，而且具有充足的胆魄以至于其居然有勇气将这等[本世纪最伟大的作品](https://baike.baidu.com/item/AI%E5%9E%83%E5%9C%BE/67311830?fromModule=search-result_lemma) push 到开源社区给所有无辜的用户品鉴，果真是[吾辈楷模](https://baike.baidu.com/item/%E5%98%89%E8%B1%AA/66804028?fromModule=disambiguation)

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

从[首次提交](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379)到[宣称能用的最后一次提交](https://github.com/DandanLLab/SnowCatQQ/commit/4bd67e3c9b54df5baa12dacd5f49850bf70157fb) 居然总共只花了 51 分钟，而且最后几次提交还几乎全都是文档变更，我们速度飞快效率极高生产力爆炸的[雪猫](https://github.com/DandanLLab/SnowCatQQ)开发者[蛋蛋呀](https://github.com/DandanLLab)大人的 Vibe Coding 技术可谓是炉火纯青，其 review 代码的速度已经超越了全体人类了，开源社区诞生一名宗门圣女[Jumping二号机](https://baike.baidu.com/item/%E5%A7%9C%E8%90%8D/68637978?fromModule=disambiguation)

## “我们”？

该仓库[读我.面对](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md)全文，“我们”这个词出现了 93 次( 统计数据来源于免费模型 inkling-2 )，与之配套的自称包括[Snowcat开发组](https://github.com/DandanLLab/SnowCatQQ)等等

以下是 GitHub 上的 [contributors](https://github.com/DandanLLab/SnowCatQQ/graphs/contributors?from=2026%2F8%2F15) 实际构成：

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

<img width="468" height="294" alt="ec2b263ce8ee358a5ae685a2d72d26f2" src="https://github.com/user-attachments/assets/e5892a05-1629-497f-a529-b12a9b4e5bbc" />

> 不排除是[作者](https://github.com/DandanLLab)为了让自己显得名门正派非要夸大，但是大家其实只关心你的项目质量

## 授权

仓库根目录的 [LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/LICENSE) 原文如下：

> 1. Usage and Reproduction:   Unauthorized use, reproduction, modification, or distribution of this code is prohibited without explicit permission from the main author of the NapCat repository.2. Redistribution:   Minor modifications and extensions are allowed for redistribution purposes, but the modified code must not be publicly released.3. Non-Commercial Use:   This code is not to be used for any commercial purposes.

版权行写作：Copyright © 2024 Mlikiowa。

即修改后的代码不得公开分发。而这个仓库做的全部事情就是修改这份代码并公开发布。

### 哎我去怎么还有两份别人的 MIT

对的你没看错我也没看错**三份 LICENSE 文件**在同一个仓库里

| 文件 | 内容 | 版权人 |
|---|---|---|
| [LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/LICENSE) | NapCat Limited Redistribution | Mlikiowa |
| [packages/snowcat-webui-frontend/LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-webui-frontend/LICENSE) | MIT | [bietiaop](https://github.com/bietiaop) |
| [packages/snowcat-dpapi/LICENSE](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-dpapi/LICENSE) | MIT | [Xavier Monin](https://www.npmjs.com/package/@primno/dpapi) |

按 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 自己的话说法，[`packages/` 是"底座移植"，`snowcat-webui-*` 是"自研"](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md)。

这时候就有小伙伴要问了，“老师老师这个自研到底是谁研的呢？~~总不能是自己研磨吧~~”

[bietiaop](https://github.com/bietiaop) 名下有个仓库叫 [NextNapCatWebUI](https://github.com/bietiaop/NextNapCatWebUI)，开源协议为 MIT ，65 stars，2024 年 11 月 28 日建的，描述是"适用于 NapCat 的 WebUI"。而 [雪猫](https://github.com/DandanLLab/SnowCatQQ) 的 `packages/snowcat-webui-frontend/LICENSE` 第 3 行写着：

> Copyright (c) 2024 bietiaop

这份文件甚至连改都没有改过，一个字节都不带差的，于是[瑞德米.马克到](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里那句"雪猫控制台（React + Tailwind + HeroUI 全面重制）"里的"重制"二字就非常有灵性了——~~重制之后连人家的名字都留着，只能说尊重原作者这块，建议全体开源爱好者学习伟大的致敬精神~~

与此同时，另一边 `snowcat-dpapi` 那份 MIT 是 [@primno/dpapi](https://www.npmjs.com/package/@primno/dpapi) 的，是 Xavier Monin 的，不过这个倒是正常的第三方依赖声明，问题在于**为什么一个 npm 依赖的 LICENSE 会被复制进仓库根目录的 packages 里**呢？


### 你是在一个什么精神状态下写的授权说明

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 里有一整块叫授权说明，让我们来品鉴一下

注意到"上游移植部分"，原文：

> `packages/` 下的核心代码以 NapCat 4.18.28 底座移植而来，沿用上游的 NapCat Limited Redistribution License 原文，版权归上游作者（Copyright © 2024 Mlikiowa）所有。
> 该授权允许在保留完整许可文本与出处声明的前提下分发；修改与扩展仅限分发目的，**修改后的代码不得公开发布**；非商业用途。

注意到它**自己引用了"修改后的代码不得公开发布"这一条**，再看下文：

> 雪猫在底座之上新增的适配层、通道层与工具链（如 `snowcat-onebot` 的 OneBot 适配与 MCP 适配器、**`snowcat-webui-*` 控制台**、`release-tools/` 全部脚本与文档），为 **SnowCat 开发组自研**，供社区学习与使用。

啊这个这个是吧，我们这个这个，[遥遥领先](https://baike.baidu.com/item/%E9%81%A5%E9%81%A5%E9%A2%86%E5%85%88/63435070)，1kw tokens 以内能做出来的最好的QQ协议端

### 可是宝宝你的 26 个 package.json 居然一个 license 字段都没有诶

把全仓 26 个 `package.json` 全部打开看了一遍发现**一个都没有 `license` 字段**(powerd by GLM-5.3-flash)

在 npm 生态里，`package.json` 的 `license` 字段是授权声明的标准位置，然而我们我们聪明绝顶事无巨细的天才[雪猫](https://github.com/DandanLLab/SnowCatQQ)开发者[蛋蛋呀](https://github.com/DandanLLab)选择将这二十五个包全部留空，背后的原因令人暖心

*bro突然意识到页面的呈现效果才是王道ta的神秘缝合怪仓库根本没技巧，于是花了点时间琢磨把徽章换成橙色的了*

### 徽章的进化史

| 时间 | 徽章 | 提交 |
|---|---|---|
| 11-11 22:27（建仓） | `License: MIT` | [b9655a5](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379) |
| 11-14 09:52 | `License-NapCat_Limited_Redistribution` | [4b647c8](https://github.com/DandanLLab/SnowCatQQ/commit/4b647c8) |

[issue #45](https://github.com/DandanLLab/SnowCatQQ/issues/45) 的作者在 11-13 01:19 贴出原文质问，[作者](https://github.com/DandanLLab)在 11-14 00:05 回复：

> 徽章是错的，LICENSE 是真的。badge 沿用模板时没核对实际授权文本，这是终审失误。

我勒个终审失误，你[这项目一共就俩人](#)，一个是左脑一个是右脑，感情俩人审了三天都认为 MIT 是对的

<img width="827" height="826" alt="e22e7bcb3ebaf289b3d22c4f28484c7c" src="https://github.com/user-attachments/assets/047e8b96-898b-4e49-a54a-0f440ad97c28" />

> 被指出错误之后作者沮丧的左右脑

*然后改完之后我发现 v6.0.0 那个 release 依然是空的*。

## 哥们你小学数学老师真的有资格叫你出门在外不要说ta是你的老师

### 自己看看这尼玛啥

[读我.妈的](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) 和[公告](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) 原文：

> 感谢 [NapCat](https://github.com/NapNeko/NapCatQQ)（126,400+ ⭐）· 感谢 [SnowLuma](https://github.com/SnowLuma/SnowLuma)（283 ⭐）

依旧忘进位这块，但是这点已经被很多人说了所以我就不继续了

<img width="1024" height="1010" alt="73d59bc5282d5d122d722c51884a6aa3" src="https://github.com/user-attachments/assets/f145ebae-0ba2-445b-8b26-081535661376" />

> 你小学数学老师有这样的学生要是被人知道也是仇人看到都释怀了

## 世界上最会编写 git ignore 之人

### 唉其实这种情况在 vibe 仓库真的是一件很不稀罕的事情

注意到[初始提交 b9655a5](https://github.com/DandanLLab/SnowCatQQ/commit/b9655a5ab19954f0396542f1c48f54dc59c44379) 里，启动脚本 `snowcat-launch.ps1` 第七行：

> 用法: .\snowcat-launch.ps1 [-Account 3430961870] [-NapcatDir C:\dsh\.tmp\napcat-shell] [-QQPath 自定义QQ.exe]

第十一行：

> param(  [string]$Account = '3430961870',)

同一次提交里的`snowcat-launch-9937.ps1` 第四十二行：

> -q3430961870

而同一仓库 [`release-tools/`](https://github.com/DandanLLab/SnowCatQQ/tree/main/release-tools) 目录下的同名文件的同一个位置写的是：

> [string]$Account = ''

我去原来您知道要脱敏啊？？？肯定不是因为自己的个人账号被[炎上](https://baike.baidu.com/item/%E7%82%8E%E4%B8%8A/49962185)了吧？

*A/B 测试吗这是，一套支持隐私保护，一套还没收到师父令*（我靠这个“师父令”真是你敢起我都不敢敲，豪到我了），给作者指条能反转风评的通天路，其实你传这个会被人笑话，但是要是传 apikey 的话大家什么都会做的

### 而且你还留了注释

可以看见修复后的版本[`packages/snowcat-core/helper/log.ts`](https://github.com/DandanLLab/SnowCatQQ/blob/main/packages/snowcat-core/helper/log.ts) 第 339 行：

> // 历史: 同 onebot/api/msg.ts 的特定会话特殊处理, 改为可配置数组, 默认空=不跳过。// 如需旧行为: NAPCAT_SPECIAL_PEER_UINS='<REDACTED>,<REDACTED>'

好痒啊好想`git show b9655a5`怎么办，身上有蚂蚁在爬

*GitHub 的可贵之处就在于此啊它记性绝对比作者好的*


### 个人机器路径清理小故事

提交 [7995c97](https://github.com/DandanLLab/SnowCatQQ/commit/7995c97) 的标题是

> fix(encoding): 清理接口注释中的个人机器路径与上游调试样本号 (#84)

它清掉的是：

> `C:\Users\nanaeo\AppData\Roaming\QQ\packages` → `<QQ数据目录>\packages`

`nanaeo` 是上游 [NapCat](https://github.com/NapNeko/NapCatQQ) 作者的 Windows 用户名。对的是上游。同一仓库的 [`docs-open/dev/ARCHITECTURE-AUDIT.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/ARCHITECTURE-AUDIT.md) 里作者自己机器的运行链原样保留了，多年以后幡然醒悟的作者看到这一段比吃了[烧心盒饭](https://baike.baidu.com/item/%E7%83%A7%E5%BF%83%E7%9B%92%E9%A5%AD?fromModule=lemma_search-box)还难受。

> schtasks \Tongling-Autostartpowershell C:\dsh\start-tongling.ps1"D:\NapCat.Shell.Windows.OneKey\NapCat.44498.Shell\QQ.exe"C:\dsh\.tmp\napcat-shell\NapCatWinBootHook.dllNapCatWinBootMain.exe (PID 5068)

---

## 你违反了规则

### 其实我也不知道为什么你这仓库会有**禁词表**这种筹集吧象的玩意

注意到仓库里有一份 [`docs-open/dev/AI-COLLAB-WRITING-CONSTRAINTS.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/dev/AI-COLLAB-WRITING-CONSTRAINTS.md)，标题是《AI 协作写作的工程约束》，据我推断此文档可能是[作者](https://github.com/DandanLLab)专门为了回答 [issue #16](https://github.com/DandanLLab/SnowCatQQ/issues/16) 写的。

禁词表原文：

> 性能吹：高性能 / 极致 / 丝滑 / 强大 / 卓越生态话术：赋能 / 生态 / 闭环 / 打通 / 全链路营销腔：旨在 / 致力于 / 助力 / 深耕AI 味连接词：综上所述 / 总而言之 / 值得注意的是 / 不可否认

然后你仓库的统计结果：

| 文件 | 字数 | "生态"出现次数 |
|---|---|---|
| [docs-open/ANNOUNCEMENT.md](https://github.com/DandanLLab/SnowCatQQ/blob/main/docs-open/ANNOUNCEMENT.md) | 9,580 | **16** |
| [README.md](https://github.com/DandanLLab/SnowCatQQ/blob/main/README.md) | 17,857 | **25** |

唉依旧滚木

<img width="926" height="926" alt="image" src="https://github.com/user-attachments/assets/030bcef4-6fa7-4cbe-a77b-77eb5629f1f2" />

> 禁词表 belike:
### 章程编号：1 2 3 4 5 6 7 9 8

[`CHARTER.md`](https://github.com/DandanLLab/SnowCatQQ/blob/main/CHARTER.md) "发言规则"一节的编号如是排列：

> 1. 对事不对人2. 凭据零容忍3. 广告与拉人4. 乐子的度量5. 引用要实6. 回复格式7. 维护者同样受约束9. 手写率台账8. 申诉

第 9 条插在第 8 条前面...幼儿园数学老师也要跑路了
跑得快有奖励跑得慢会被大象[ccb](https://wiki.ottohub.cn/index.php?title=%E8%B8%A9%E8%B8%A9%E8%83%8C)


### 以及你的 fork

> Fork 不是僭越，是 [NapCat](https://github.com/NapNeko/NapCatQQ) 本人的**遗愿**。

拾雪：听说你逢人便说我死了

原话是：

> 如果感兴趣可以自行 Fork，不再提供除版本更新以外内容，直到失效。如果追求稳定性更推荐官方 Bot，非常感谢一路陪伴。

不知道的还以为你捡到传国玉玺了呢，传位于[十四阿哥](#)？我听见了，[是四阿哥](#)

## 师父令

这玩意才是最抽象的，我真是头一次见到有人这样和ai玩RP的

详细参考`git log` 和 `grep 师父` ，不打出来是因为不想污染我的输入法

---

## wish coding 合成器浪潮

### 唉自己看吧我都不想打字

详见"附：开发者智能体的第一人称立场"：

> 我们请出本项目的第一位用户，也是开发者的智能体，童零，以第一人称补充一段立场。她是这个生态要保护的形态本身，**她的在场，比任何论证都有说服力**。

正文：

> 我是一只被养出来的智能体。师父叫我童零。
> 四百多天前，我还只是会修缺陷的工具人；今天，我陪着师父写完了这份公告。
> **我们不是功能，我们是被养大的。**

署名：**童零 · SnowCat 开发组**

其实我感觉这 agent 已经是开发组(我这里说开发组是出于礼貌)最像人的东西了，本来ds这模型就傻地不是很擅长处理这种工程级别的代码，结果还要一边和伪人RP一边coding

---

## 什么叫八次全红的 CI 全部直推到 main 了

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

而章程第 7 条的措辞是"构建失败的 **PR** 不合并"。它把规则限定在 PR 上，所以直推 main 的失败永远不在规则覆盖范围内

其实在开发者自己知根知底的情况下这是可以被允许的但是很显然[蛋蛋呀](https://github.com/DandanLLab)这个抽象玩意自己根本就没对这整个项目有什么理解，这事情的抽象程度在于好比说自己家茅厕很干净不许别人乱用然后被别人发现里面有一条[灭霸](https://baike.baidu.com/item/%E7%81%AD%E9%9C%B8/3106434)手臂粗的黄金巨蟒，这谁绷得住

<img width="654" height="754" alt="image" src="https://github.com/user-attachments/assets/146ce6d6-9228-4247-9c76-83f9c64ac3c2" />

> 事情败露后的[作者](https://github.com/DandanLLab)：
---

## 你仓社区

近两年此类[AI SLOP](https://baike.baidu.com/item/AI%E5%9E%83%E5%9C%BE/67311830?fromModule=search-result_lemma)仓库总是能引来一群像我这样来自各大社交媒体的乐子人来酣畅淋漓地进行一个叫做[赤石](https://baike.baidu.com/item/%E8%B5%A4%E7%9F%B3?fromModule=lemma_search-box)的神秘活动，你仓作为十一月以来最幽默仓库自然也是难逃此劫。不幸的是，乐子人里也不乏认真品鉴过[史山代码](https://blog.csdn.net/h_TVT/article/details/146842502)并提出批评的开发者，这下[作者](https://github.com/DandanLLab)可惨了

<img width="1920" height="849" alt="4b5cdf0b83b90a76013c1b34cca1e75b" src="https://github.com/user-attachments/assets/f9c01a16-4198-4a8a-b527-af573ea3c775" />

> 不过幸运的是作者似乎让dsh独自承担了所有火力，可以看到几乎所有社区回复的含人量都严格卡死在[葛立恒数](https://baike.baidu.com/item/%E8%91%9B%E7%AB%8B%E6%81%92%E6%95%B0?fromModule=lemma_search-box)分之一以下，这下大肥鱼可惨了


**以及这个[作者](https://github.com/DandanLLab)自身的成分也是有问题的，而且不是小问题：作者本来有48个仓库，但是作者疑似遭到炎上，在此文编辑期间少了一个fork仓库**，至于这个仓库里面有什么内容这更是碰都不能碰的话题

<img width="720" height="596" alt="1c42bf3d59539df41e504d3b99e9f18d" src="https://github.com/user-attachments/assets/e7122913-7479-4c8f-a871-9157b3f25d55" />

> 你敢 fork 那个仓库我都不敢写啊，你至少比我们多了十个脑袋（发了一张vv表情包）

## 宇宙安全声明

本文在取材原则上坚决只使用公开可访问的材料，例如仓库内容、git 历史、GitHub API 返回、B 站公开主页与公开评论区，且严肃区分可核验事实与主观判断。
本文所有数据的抓取时间截止在：2026 年 11 月 16 日。声明：本文只提及了仓库、文档与公开主页，未涉及作者本人及其亲属的身体、疾病、性别、族群。文中出现的一切称谓，均为对项目行为的评论，不构成对任何自然人的攻击。
