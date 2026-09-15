---
type: meeting
title: F5 屏蔽逻辑与 Lesson Support 讨论
date: 2026-06-02
participants: [Mel Quozon, 曹海璇, 邵涵, Anna, Joe, Katherine]
tags: [外教战役, F5, 前五节课, 屏蔽逻辑, 代课, LessonSupport, LearningHub, Cocos, 师生匹配]
source_file: journal/2026/06/2026-06-02/media/F5 blocking logic+ Lesson Support Discussion.srt
status: active
created_at: 2026-06-02
---

# F5 屏蔽逻辑与 Lesson Support 讨论

> 来源：[[journal/2026/06/2026-06-02/media/F5 blocking logic+ Lesson Support Discussion.srt]]  
> 背景补充：参考 [[projects/外教战役/decisions/2026-05-F5两车不合并618先行.md]]、[[projects/外教战役/meetings/2026-05-28-F5项目新生首5节课.md]]、[[projects/外教战役/meetings/2026-05-29-体验课转化提升50%.md]]。  
> 说明：原稿为中英混合 SRT 自动转写。本文按业务主线整理；人名、系统名以转写可辨识信息为准。

## 1. 核心结论

1. **这次会议把 F5 从“泛质量提升”收敛到两条可落地的系统动作：屏蔽逻辑 + 代课 / Lesson Support。** 这与前序决策一致：F5 不再承担 618 主车的全部胜负，而是做“排雷三连 + 代课逻辑改造 + 支持监控”的风险消除器。
2. **当前 March refund 样本并不能证明“老师缺勤”是 F5 退费主因。** Joe 拉取的 3 月实际退费学生样本中，前五节常规课未出现 missed lesson；12 个 teacher absence 都成功代课。数据反而显示 bad evaluation、教学表现、材料体验、级别匹配更值得追。
3. **但会议没有因此否定屏蔽逻辑。** 结论是：不能仅凭 3 月小样本调整大规则，但仍应把 F5 的风险老师、设备/网络、差评、培训完成、级别适配等条件做成更强的前置屏蔽与推荐规则。
4. **F5 屏蔽逻辑不能只看综合 QA 分。** Anna 的听课反馈表明，有的老师能量和课堂管理尚可，但 grammar / pronunciation / 级别处理能力不足；同一老师可能适合 L0/L1，却不适合 L3/L4。因此要向“分级别能力认证 / 标签 / 数据推断”演进。
5. **FT 到常规课的体验断层是关键风险。** FT 课件更丰富、更像产品；常规课尤其低级别 L0 Unit 1 Lesson 1 很容易变成 25 分钟空转。F5 退费不只是老师问题，也有材料、课件、级别、期待管理的系统断层。
6. **Cocos / Learning Hub 是未来 F5 老师准入的系统底座，但当前还不能简单用 self-paced 训练替代人工校准。** 对 F5 来说，老师需要完成 L0 / S / L1 / L2 / L3 相关训练并产生系统数据；但 Anna 明确提醒，仅开放 Learning Hub 自学不够，至少要有 live / hybrid training 或 demo review。
7. **代课逻辑的原则是“先保证课发生，再尽量用 F5 尺子”。** 课前可按 F5 推荐逻辑找代课；课中如果老师没进 AC，要立即触发代课，优先保障学生不空等。代课优先级可从 F5 老师、SBT 代课老师、抢课、其他老师依次降级。
8. **Lesson Support 需要先做资源可行性验证。** F5 已有 lesson support 监控页面，但没人主动看。短期要确认 FT support 是否能覆盖 F5，特别是 8 点高峰重叠；如不能，需要项目制人力或独立 support 试验。
9. **下一步不是继续开泛质量会，而是产出可执行规则。** 产品 / RD 侧需尽快给出 blocking logic 和 substitution logic 第一版；数据侧补足近期退费样本；培训侧确认 Learning Hub 证书、badge 和完成数据；support 侧确认 6 月短期可执行方案。

## 2. 前序背景：F5 当前在外教战役里的位置

前序会议已经把 F5 从一个“所有退费都要靠外教侧解决”的大包袱，拆成更有限但更可执行的任务：

- **F5 是新生前五节课的风险排雷工程。** 它针对的是学生从 FT / Trial 进入 regular lesson 后，最容易因为老师缺席、代课失败、老师质量、材料落差、设备/网络等因素形成退费意愿的窗口。
- **F5 不是 618 主车。** 618 先行的是更横切的车 B；F5 更像“排雷 + 驿站”，降低新生早期体验事故，避免主战场被早期差体验拖垮。
- **前序方案已收敛为三类动作：** 零课中缺席屏蔽、定向搜索强提醒 / 硬屏蔽、零学习 + 设备分屏蔽、监课页面、代课逻辑改造、完课强提醒激励等。

本次会议接续这个脉络，重点讨论两件事：

1. F5 blocking logic 具体应该屏蔽什么、推荐什么；
2. F5 lesson support / 代课怎样在课前课中真正兜底。

## 3. 数据复盘：March refund 样本给出的信号

### 3.1 Joe 拉取的数据口径

会议先看了 3 月实际退费学生样本：

- 样本：3 月 refund students，约 56 名学生；
- 课程：这些学生对应的 regular lesson booking 约 419 节；
- 完课：约 407 节完成；
- teacher absence：12 次，但全部成功 substitute；
- missed lesson：样本中未看到老师缺席导致的 missed lesson；
- late / early leave：出现少量 late 和 early leave；
- bad evaluation：约 15 条 bad evaluation。

从这个样本看，**“老师没有出现”并不是最显性的退费原因**。至少在 3 月 actual refund 数据里，缺勤被代课机制消化掉了。

### 3.2 这份数据的限制

曹海璇对数据口径提出了关键挑战：

- 3 月样本过旧，不能代表 5 月合肥 / 国内业务反馈；
- actual refund 与 submitted refund 不同，很多真实不满可能在提交退费阶段就已出现；
- 样本量不大，而且只看已退费，不足以支撑规则大改；
- 业务反馈中“老师反复缺席 / 频繁代课”的感受，可能被 March actual refund 样本低估；
- 还需要看 booking lead time：如果学生临近上课才约课，系统可能只能推荐低优先级老师，这不是单纯老师池质量问题。

因此会议没有把这份数据当作最终结论，而是把它视为一个提醒：**F5 的问题不能只按“老师缺勤”单点归因。**

## 4. Anna 的听课质量分析：退费风险更像多因素叠加

### 4.1 分析方法

Anna 选取 March refund 样本中，重复出现在多个退费学生 F5 课程里的老师进行听课分析。由于 3 月原始录播暂时拿不到 / 被锁，她先听了这些老师近期 5 月的课程，以判断老师当前教学质量和可复现问题。

这意味着 Anna 的分析不是严格因果证据，而是“同一批高风险老师的近期教学画像”。后续还需要拿到原 55 / 56 个退费学生的真实录播，与 AI prompt 分析做比对。

### 4.2 主要问题一：发音 / 口音只是其中一类问题

Anna 听到的确有 pronunciation / accent 问题，但不是所有课都严重到一票否决。更常见的情况是：

- 发音有瑕疵，但仍可勉强完成课；
- 老师能量、互动、纠错、课堂推进共同决定体验；
- 某些老师不是“差到不能上”，而是“在 F5 这种高敏感窗口不够稳”。

这说明 F5 屏蔽逻辑不能只加一个“口音 / 发音”硬阈值，而要组合多个风险维度。

### 4.3 主要问题二：低级别常规课太容易变得无聊

Anna 特别提到 L0 Unit 1 Lesson 1 这类低级别课：目标词少、内容简单、重复度高，如果老师没有足够技巧，25 分钟会非常痛苦。家长视角下，可能会觉得“这节课没有价值”。

这反映出一个系统断层：

- FT / trial lesson 的课件、节奏、视觉和互动通常更好；
- regular lesson 尤其低级别材料偏旧，很多年前设计后未系统更新；
- 学生从 FT 进入 F1/F2/F3 后，期待落差很大；
- 老师要靠个人能力把无聊材料讲活，但这对平均老师要求过高。

所以，F5 退费不能全部归因给老师；常规课材料和课件体验本身也是风险源。

### 4.4 主要问题三：级别匹配错误会放大老师问题

Anna 举了一个高龄学生被放在不合适 level 的例子。学生年龄较大，但课上理解明显跟不上；老师推进缓慢，页面完成率低，课堂体验自然很差。

这里的问题不是“老师坏”或“学生坏”，而是：

- 学生 level placement 可能不准；
- 老师没有足够能力处理错配；
- 高级别课程要求老师具备更强语言能力和语法准确性；
- 低级别适合的老师，未必适合 L3 / L4。

因此 F5 matching 不能只有“这个老师综合好不好”，还要知道“这个老师适合教哪个 level、哪类学生”。

## 5. Blocking logic：从推荐优先级走向 F5 专属排雷规则

### 5.1 现有逻辑的问题

现有新生推荐逻辑已经会看老师 reliability，例如缺勤率、迟到、早退等，并优先推荐缺勤率低于一定阈值的老师。但会议确认：

- 现有逻辑更像“优先推荐好老师”；
- 它不一定对高风险老师做硬屏蔽；
- 在月末、老师池不足或临近 booking 时，系统仍可能把风险老师推荐给 F5 学生；
- 对 F5 这种敏感窗口，仅靠“优先级”可能不够，需要更强排除条件。

### 5.2 F5 可加入的屏蔽 / 降权维度

会议讨论到的候选维度包括：

| 维度 | 会议含义 | 四化理解 |
|---|---|---|
| 出勤 / 缺勤 / late / early leave | 高频缺勤、迟到、早退老师不应进入 F5 优先池 | reliability 硬门槛 |
| bad evaluation / complaint | 差评、投诉、家长负反馈要进入屏蔽或降权 | 体验事故信号 |
| 设备 / 网络 / 环境 | 摄像头、灯光、网络、设备不达标会造成 FT→F5 期待落差 | 技术准入门槛 |
| Learning Hub / training completion | 老师是否完成对应 level / F5 训练 | 训练准入门槛 |
| level fit | 老师是否适合 L0/L1/L2/L3，不只看综合分 | 分级别能力标签 |
| QA / CE 质量 | 综合质量分可参考，但不能单独决定 | 质量证据之一 |
| booking lead time | 临近开课才约，可能导致推荐池不足 | 区分系统约束与老师质量 |

这张表的核心是：**F5 blocking logic 应该是多维排雷，而不是单一 QA 分筛选。**

### 5.3 不能用一个小样本直接改全局逻辑

会议中多次提醒：

- March actual refund 样本不够代表全部；
- 还要补 May / recent submitted refund / 合肥反馈；
- 还要区分老师问题、材料问题、level placement、booking lead time；
- 逻辑改动要先和产研 / RD 确认当前系统能力。

因此，合适路径是：**先定义 F5 专属风险维度和第一版规则，再用更宽样本验证与迭代。**

## 6. 老师分级认证：F5 不能长期靠人工记忆“谁适合教什么”

### 6.1 当前缺口：缺少可靠的 level capability 数据

会议暴露了一个长期问题：系统并不知道每个老师最适合教什么 level。大家可能凭经验知道某些老师适合低级别、某些老师能教高阶，但这没有形成稳定可用的数据资产。

这会带来三个后果：

1. F5 推荐无法精细匹配；
2. 屏蔽逻辑只能看总分和投诉，无法看“适配”；
3. 培训完成后也无法自动改变老师可教范围。

### 6.2 两条可能路径

会议中讨论了两条路径：

#### 路径 A：训练 / 认证前置

老师必须完成某个 level 或课程包的训练，才能被允许优先教该 level 的 F5 学生。Cocos L0-L2 正在接近这种模式：

- 老师在 Learning Hub 看 training video；
- 进入 AC / courseware 练习；
- 录制 demo video；
- 人工 review；
- 通过后拿到对应 certificate / badge。

这个路径更标准化、可解释，也更适合做准入规则。

#### 路径 B：用数据反推擅长 level

如果系统能用学生续约、收藏、复约、差评、退费、lookalike student 等数据反推，就可以逐步形成“这个老师在 L1 表现好、在 L3 风险高”的数据标签。

这条路径更智能，但前提是数据足够干净，且能与 booking / recommendation 系统打通。

### 6.3 本次倾向：不做离线人工 tag，优先用 Learning Hub 数据和 badge

会议中对“要不要手工给老师打 F5 tag”较谨慎。更好的方向是：

- 不制造一套离线、不可维护的人工标签；
- 让老师完成 Learning Hub / live training / demo review；
- 系统生成 training completion、certificate、badge；
- booking / recommendation 系统读取这些数据；
- 老师端 My Page 或类似页面能看到自己的 certificate，形成荣誉和激励。

但 Anna 明确提醒：**F5 训练不能只靠 self-paced。** 对前五节关键窗口，最好有 live 或 hybrid training，至少要有 demo review / 人工校准，否则老师可能只是“看完材料”，不代表真的会教。

## 7. 代课逻辑：课前与课中要分开设计

### 7.1 课前代课

如果老师在课前主动请假，系统应该按 F5 逻辑重新找老师，而不是普通替补逻辑一把梭。可行方向：

- 对 F5 学生优先找 F5 合格 / 认证老师；
- 使用同一套 blocking logic 排除高风险替补；
- 如果能提前识别老师无法上课，就不要等到开课后才补救。

会议还提到课前确认机制：系统可在课前约 5 分钟发确认 / reminder；如果老师不能确认或明确拒绝，可以在约 3 分钟前触发代课，让替补老师在学生进入前已经准备好。

### 7.2 课中代课

课中代课的优先级与课前不同。邵涵强调：如果正式上课时老师没有进入 AC，再等几分钟就已经伤害学生体验；这时第一原则是“课必须发生”。

可执行逻辑包括：

- 开课时检测老师是否进入 AC；
- 如果老师未进入，立即触发代课；
- 因为老师进入 AC / classroom 需要 1-2 分钟，所以触发不能太晚；
- 课中替补优先保障 attendance，再尽量满足 F5 质量标准。

### 7.3 替补老师优先级

会议中形成的候选顺序是：

1. unbooked F5 teachers / F5-qualified teachers；
2. SBT substitute teachers；
3. 抢课老师；
4. 其他可用老师。

这不是最终技术规则，但给出了设计原则：**正常情况用 F5 尺子，紧急情况先保证学生不空等。**

## 8. Lesson Support：已有页面，但缺少主动运营与人力安排

### 8.1 当前状态

会议确认：F5 已有 lesson support / monitoring page，但目前没有专人主动监控。这意味着系统资产已经有一部分，但还没有变成运营机制。

如果只是“页面存在”，而没有人盯、没有 trigger、没有 escalation、没有值班责任，它不能真正降低退费。

### 8.2 是否复用 FT Lesson Support

邵涵提出可以参考 FT lesson support。FT support 已经成熟，逻辑上可用于 F5：

- 课前检查老师是否 ready；
- 检查老师灯光、衣着、背景、设备；
- 高风险课提前提醒；
- 出问题时快速介入。

但会议也指出重大限制：

- FT 和 F5 高峰都在晚上 8 点左右；
- FT 当月 trial lesson 量很大，约 89K 级别；
- F5 量也不小，约 20K / 月级别；
- 如果直接把 F5 压给 FT support，可能导致 FT 与 F5 两边都被拖垮。

因此，短期要由 May / support 相关负责人确认 FT support 是否能覆盖，不能只在会议里假设“复用即可”。

### 8.3 Lesson Support 的价值边界

会议中有一个重要判断：**如果 blocking / mapping logic 不改，Lesson Support 就只是 firefighting。**

原因是：

- 如果系统持续把风险老师推荐给 F5 学生，support 只能不断救火；
- 如果没有老师级别适配，support 也无法从根上减少事故；
- 如果缺少代课逻辑，support 只能发现问题，无法快速替换；
- 如果没有培训 / 认证数据，support 不知道哪些老师是真正 F5-safe。

因此 F5 support 的正确定位应是：在 blocking logic、substitution logic、training certification 之上，做最后一公里监控与兜底。

## 9. 材料与 Cocos：F5 不是只靠老师侧能解决

会议多次回到 FT → regular lesson 的体验断层。

### 9.1 常规课材料老化

Anna 的听课反馈指出，一些 regular lesson 材料过旧、互动不足，尤其低级别课内容太少。老师如果能力一般，就很难把课讲得有价值感。

这会造成家长期待落差：

- Trial / FT 课件很好；
- 首几节 regular lesson 体验下降；
- 家长认为“正式课不如体验课”；
- F1/F2/F3 退费风险上升。

### 9.2 Cocos 的机会与边界

Cocos 可能显著改善 L0-L2：

- 课件更连续；
- 教师训练可嵌入 Learning Hub；
- 老师可以进入 AC 练习 courseware；
- demo review 和 certificate 可成为准入条件。

但会议也提醒：

- Cocos 当前主要覆盖低级别；
- L3+ 仍然会遇到老师语言能力、grammar、复杂互动等问题；
- 学术 / 产品相关负责人不在本次会中，因此不能在本会议里决定材料 overhaul。

所以，F5 短期靠 blocking + 代课 + support 排雷；中长期还要把材料、课程、Cocos 与老师训练打通。

## 10. 数据口径与未决问题

| 问题 | 为什么重要 | 下一步 |
|---|---|---|
| March actual refund 样本是否代表近期问题 | 样本过旧且只看实际退费 | 补 May / recent submitted refund / 合肥反馈 |
| 为什么业务感知“老师频繁缺席”，但样本无 missed lesson | 可能是 submitted refund、代课体验、频繁替换感知，而非 missed | 拉取更宽数据，区分 absence、substitute、student perception |
| booking lead time 是否影响推荐质量 | 临近约课可能只能推低优先级老师 | 在分析中加入 lead time |
| bad evaluation 与退费关系 | 15 条 bad eval 是明显信号，但需看维度 | 拆差评原因：教学、设备、态度、材料、level |
| 老师 level capability 如何进入系统 | F5 需要知道谁适合教 L0/L1/L2/L3 | Learning Hub certificate + 数据反推 |
| F5 support 是否有足够人力 | 页面存在不等于有人监控 | May / support 侧确认短期方案 |
| Cocos 覆盖外的 level 如何处理 | L3+ 仍然有 teacher language / grammar 风险 | 学术 / 产品 / 培训共同补方案 |

## 11. 决策与后续动作

| # | 事项 | Owner | 截止 / 节奏 | 备注 |
|---|---|---|---|---|
| 1 | 产出 F5 blocking logic 第一版 | 曹海璇 / 产研 / RD 相关老师 | 本周，会议中提到 Friday 方向 | 先和相关产品 / RD 确认当前逻辑与可改空间 |
| 2 | 产出 F5 substitution logic 第一版 | 曹海璇 / 产研 / RD 相关老师 | 本周 | 区分课前代课、课中代课；课中优先保障课发生 |
| 3 | 把现有 F5 相关文档同步给曹海璇 | Mel / Tao / 相关负责人 | 会后立即 | 便于明天与产品 / RD 对齐 |
| 4 | 补充近期退费与提交退费样本 | 数据侧 / Joe / 相关分析人 | 近期 | 不只看 March actual refund；加入 May / 合肥反馈 |
| 5 | 在数据分析中加入 booking lead time | 数据侧 | 近期 | 判断是否因临近约课导致推荐池不足 |
| 6 | Anna 继续听原始 refund student 录播 | Anna | 下次会前 | 拿到 March 原始录播后，与近期课分析区分 |
| 7 | 对比 Anna 人工听课与 AI prompt 分析结果 | Anna / 小龙 / 数据或 AI 侧 | 下次会 | 看 AI 是否能稳定识别退费风险维度 |
| 8 | 确认 Learning Hub 能否输出 level training completion / certificate / badge | Training / Learning Hub / Product | 近期 | 支撑 F5 老师准入，不做不可维护的离线 tag |
| 9 | 明确 F5 老师是否需完成 L0 / S / L1 / L2 / L3 训练 | Training / Anna / Mel | 近期 | Anna 倾向不能只 self-paced，至少 hybrid / demo review |
| 10 | 评估 F5 Lesson Support 是否能复用 FT support | May / Lesson Support 相关负责人 | 6 月短期优先 | 重点看 8 点高峰人力冲突 |
| 11 | 设计 F5 support 试验口径 | May / Mel / 邵涵 | 近期 | 可先动态监控 first five，看 refund rate 影响与 ROI |
| 12 | 将设备 / 网络 / 灯光 / 环境纳入 F5 屏蔽或 support 检查 | AC / Tech / Product | 近期 | 避免 FT 与 F5 老师呈现反差过大 |

## 12. 四化视角判断

| 四化维度 | 本次会议中的落点 |
|---|---|
| 标准化 | F5 老师准入、屏蔽维度、代课优先级、support trigger 要写成规则，而不是靠临时判断 |
| 产品化 | Learning Hub training、certificate、teacher badge、F5 support page 应成为老师与运营可理解的产品机制 |
| 系统化 | 推荐、屏蔽、代课、监控、培训完成、设备检测、bad evaluation 要进入同一闭环，否则每个团队只救自己的火 |
| AI / 数据化 | 人工听课要与 AI prompt / refund data 比对，形成可自动识别的 F5 风险画像 |

本次会议的关键判断是：**F5 不是一个“找几个好老师顶上”的运营问题，而是一个早期体验风险控制系统。** 真正要沉淀的不是“今天谁去盯课”，而是一套能持续运行的 F5 排雷规则：谁不能上、谁更适合上、谁没来谁替、谁来盯、盯到什么触发动作。

## 13. 可沉淀资产候选

- `F5 Blocking Logic 规则卡`
- `F5 Substitution Logic Playbook`
- `F5 Lesson Support 值班与触发 SOP`
- `F5 老师 Level Certification 数据流`
- `Learning Hub → Booking / Recommendation 数据接口需求`
- `F5 退费风险数据看板`
- `FT → Regular Lesson 体验断层分析`
- `Anna 人工听课 vs AI Prompt 风险识别校准报告`
