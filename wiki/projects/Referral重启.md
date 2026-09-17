---
rebuild_review_scope: "2026-09-15新增整理未经逐条人审；原有人类认可按原日期与范围保留"
projection: public
type: project
title: Referral 重启
tags: [battle, referral, recruitment]
related: [2026-04-25-cost-per-launch下调至1500并转向Referral, 漏斗分流策略, Q2关键决策与判断, 外教质量提升战役, 外教转介绍数据口径冲突与待核清单, 2026-08-14-高质量获客与转介绍-战略提醒, 素材机器与切片传播法, Referral-转介绍语义岛-2026-09-14]
created: 2026-08-30
updated: 2026-09-15
sources: ["外教战役/Referral重启.md", "外教战役/2026-09-05_外教转介绍知识库入库建议_数字复核版.md", "common-feed/J-8c4df9e93c88c6a4ae947a3c__ad300247b67128bb.4b3d18fc8c31.md", "common-feed/J-e595745aee1d632a2143e153__b6d159e866f59cd9.30582acd6940.json", "common-feed/J-735fad10d2f2ad9f83e27271__355663e6fffc3bad.aa3fe0b49a7e", "common-feed/J-f8fd9005ce87882cd45f407f__355663e6fffc3bad.aa3fe0b49a7e", "common-feed/J-e24dd162f0238830ed3713be__acc5118b37fd769f.aa3fe0b49a7e", "common-feed/J-21d9bb317a9010618bb1160f__36eb0efdbd25baeb.4c18cf080c4a.md"]
review: 已审
review_scope: 2026-09-15 Leon批量认可转已审：R1批量蒸馏页按其指示默认已审，认可蒸馏忠实性，未逐条人工复核；页面所载未决问题与待验证事项不因此裁决
facility: llmwiki
ingress_revisions: ["J-8c4df9e93c88c6a4ae947a3c@ad300247b67128bb.4b3d18fc8c31", "J-e595745aee1d632a2143e153@b6d159e866f59cd9.30582acd6940", "J-735fad10d2f2ad9f83e27271@355663e6fffc3bad.aa3fe0b49a7e", "J-f8fd9005ce87882cd45f407f@355663e6fffc3bad.aa3fe0b49a7e", "J-e24dd162f0238830ed3713be@acc5118b37fd769f.aa3fe0b49a7e", "J-21d9bb317a9010618bb1160f@36eb0efdbd25baeb.4c18cf080c4a"]
---
> 授权记录（2026-09-14）：Leon 授权本页整页外发（页首 `projection: public`）。正文原有段级 `projection: local-only` 标记已同步更正为 `projection: public`；各段 `review` 状态与 `facility` / `ingress_revisions` / `journal_revisions` / `processing_review` 溯源字段一律未改。


# Referral 重启
> **2026-09-11 粗筛改判：可留待审**（BCD 提案 · Leon 批改判回 A）。

> **权威阅读顺序（2026-09-14 · 语意层导读 · REF 岛 P0）**
> 1. **CPL／渠道决策（已审）** → [2026-04-25-cost-per-launch下调至1500并转向Referral](../decisions/2026-04-25-cost-per-launch%E4%B8%8B%E8%B0%83%E8%87%B31500%E5%B9%B6%E8%BD%AC%E5%90%91Referral.md) （[A](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBzbD8B5r9YAn) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnZeY3nVxAZB1Gv)）（1500 约束 + 向 Referral 集中；**不**证明现行 CPL 已达标）
> 2. **项目叙事（本页·内容级待审）** → 组织问题优先的三层打法；漏斗分流已合并为本页历史附录（**不作**现行渠道切分正本）
> 3. **高质量假设（待验证）** → [2026-08-14-高质量获客与转介绍-战略提醒](../queries/2026-08-14-%E9%AB%98%E8%B4%A8%E9%87%8F%E8%8E%B7%E5%AE%A2%E4%B8%8E%E8%BD%AC%E4%BB%8B%E7%BB%8D-%E6%88%98%E7%95%A5%E6%8F%90%E9%86%92.md) （[A](https://alidocs.dingtalk.com/i/nodes/7QG4Yx2JpLMrqaGdcq4aeYOxJ9dEq3XD) · [Leon](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzkdbmve8BQEx5rG)）（假设 ≠ 已证明高质量获客；非 H2 新增项目／预算／DRI）
> 4. **数据开口** → [外教转介绍数据口径冲突与待核清单](../queries/%E5%A4%96%E6%95%99%E8%BD%AC%E4%BB%8B%E7%BB%8D%E6%95%B0%E6%8D%AE%E5%8F%A3%E5%BE%84%E5%86%B2%E7%AA%81%E4%B8%8E%E5%BE%85%E6%A0%B8%E6%B8%85%E5%8D%95.md) （[A](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKYOABk18akx1Z5N) · [Leon](https://alidocs.dingtalk.com/i/nodes/b9Y4gmKWrPNpBnG0seqLMq6MJGXn6lpz)）／[问题账](../%E9%97%AE%E9%A2%98%E8%B4%A6.md)（本地资料，钉钉／GitHub未提供） **TOC-79**（未核前不得 CURRENT ANSWER、不得择一写成正本）
> 5. **候选未扩权**：KOC／Champions／原子小队／激励方案＝设计候选，**未**批准为制度；09-10：有运营人员 ≠ 端到端 owner 已任命
> 6. **口述／时点数字 ≠ 正式基线**（周报／会议口述、Q2 汇编时点、Jovic 冲突快照一律不得扫成现行经营数）
>
> 语义岛：[Referral-转介绍语义岛-2026-09-14](../queries/Referral-%E8%BD%AC%E4%BB%8B%E7%BB%8D%E8%AF%AD%E4%B9%89%E5%B2%9B-2026-09-14.md) （[A](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IervO6l0W1DK0g6l) · [Leon](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKnA2Nm81waOeDk)）。


<!-- common-feed:J-e595745aee1d632a2143e153@b6d159e866f59cd9.30582acd6940:start -->
## 2026-09-10 一手回忆：渠道发现没有自动变成组织学习

Katherine 回忆自己此前做 Referral 时，一名“聪明的老师”自行找到一个 Facebook 群组，带来的 leads 很强；她同时指出，AICCA 当时没有理解这套做法，也不知道怎样从这名老师身上学习。这个单点案例为本页既有判断补了一层机制证据：问题不只在老师愿不愿意推荐，还在组织能否识别有效的个体发现、还原适用条件，再把它变成其他人可测试的做法。（源：`J-e595745aee1d632a2143e153`，revision `b6d159e866f59cd9.30582acd6940`，2026-09-10 14:10，sender 袁慧茹 Katherine。）

本批没有该群组、线索数量、转化、留存、质量、时间窗或后续复制记录，因此这里只保存**一手历史案例与待验证问题**，不证明 Facebook 群组现在仍有效、不把“超级给力”换算成 ROI，也不据此批准渠道、预算或 Referral 机制。聊天内 `TOC小王` 的战略回答是 Agent 输出，不作为第二份独立来源；同页图片、文件、音频和链接正文未随 task 交付，其独有内容未读。

来源原件：[聊天 JSON](../../sources/provenance-local/common-feed/J-e595745aee1d632a2143e153__b6d159e866f59cd9.30582acd6940.json)（本地资料，钉钉／GitHub未提供）与[完整旁路](../../sources/provenance-local/common-feed/J-e595745aee1d632a2143e153__b6d159e866f59cd9.30582acd6940.json.delivery.json)（本地资料，钉钉／GitHub未提供）。Journal 登记发生日 2026-09-10、接收日 2026-09-11、actor=`multiple`，无明确 correction 或 supersedes；页级 review 已于 2026-09-15 批量认可转已审（蒸馏忠实性），`projection: public`。
<!-- common-feed:J-e595745aee1d632a2143e153@b6d159e866f59cd9.30582acd6940:end -->

<!-- common-feed:J-8c4df9e93c88c6a4ae947a3c@ad300247b67128bb.4b3d18fc8c31:start -->
## 2026-09-09 下午讨论：从转介绍线索到新师落地的组织候选

下午原稿将 Referral/KOC 的问题从获客继续推进到“谁把新老师招来、落地、管到前几个月并承担质量责任”。现场提出由少量好老师、KOC/CO 类角色承担部分招聘、landing 与带教，并讨论按新老师前若干月收入或课量分享价值；还出现“把更多钱给老师”的方向。（源：`J-8c4df9e93c88c6a4ae947a3c`，revision `ad300247b67128bb.4b3d18fc8c31`，prepared 232–328、490–730、2686–2698行；发生日/接收日均为2026-09-09。）

这是高价值但高治理风险的**设计候选**，不是已批准渠道制度、组织岗位、预算或提成政策。“KOC/CO/小CEO/下线”等词在现场含义未冻结，也没有 owner、试验范围或退出条件。进入任何试验前至少要写清：角色定义、收入/提成规则、教学质量责任、新师毕业标准、客户与老师权益、退出与反滥用条件；投入数字与渠道占比需统一市场、基期、教师群体和时间窗后再核。

来源原件：[下午原稿](../../sources/provenance-local/common-feed/J-8c4df9e93c88c6a4ae947a3c__ad300247b67128bb.4b3d18fc8c31.md)（本地资料，钉钉／GitHub未提供）与[完整旁路](../../sources/provenance-local/common-feed/J-8c4df9e93c88c6a4ae947a3c__ad300247b67128bb.4b3d18fc8c31.md.delivery.json)（本地资料，钉钉／GitHub未提供）。本段不把业务试验建议写成制度，页面保持 `review: 待审`、`projection: public`。
<!-- common-feed:J-8c4df9e93c88c6a4ae947a3c@ad300247b67128bb.4b3d18fc8c31:end -->

### 2026-09-15重读：渠道比较要带上承接条件

9月9日下午强调“真正的这个不是launch，而是合格”：推荐人可帮助新人进入真实工作，培养阶段后再由系统持续承接；但骨干也可能被竞品吸引，贡献、报酬、退出和后续责任仍需设计。几百人、若干月分成、首课或50课结算是不同例子，未冻结成启用制度。（[下午前段原稿](../../sources/raw/J-e20148b20cd02b7836c868ab__30d9973fafbe5447.0a92559cf98e.md) （[A](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcedBbbN186zbX04v) · [Leon](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS73ZKzyYWMwvDqPk)），L160–186、L230–272。）

同场承认更多线索未带来预期的质量结果，并将推荐奖励与招聘人力、工具成本分开。比较2026年上线群体时又提到优先分课、国内海外双市场以及推荐人的支持；后段对是否优先分课还有不同说法。渠道的留存、收入和利用率差异，须连同机会和支持核对，不能全部归因于原始人选更好。完整获取成本与当时分课范围仍待同批记录，不由CPL排名推出削减渠道。（同源 L130–156、L188–214、L274–298、L898–900。）

<!-- common-feed:J-21d9bb317a9010618bb1160f@36eb0efdbd25baeb.4c18cf080c4a:start -->
## 袁慧如反馈核对：KOC 选择与激励讨论仍属候选

反馈提出从既有转介绍老师中筛选 KOC；原始转写支持“从已有转介绍群体中选一部分重点经营”的候选方向，但未形成名单、筛选标准、负责人、预算或运行回执。2000/2600、400/600 和人均 3 个的证据强弱统一留在 [外教转介绍数据口径冲突与待核清单](../queries/%E5%A4%96%E6%95%99%E8%BD%AC%E4%BB%8B%E7%BB%8D%E6%95%B0%E6%8D%AE%E5%8F%A3%E5%BE%84%E5%86%B2%E7%AA%81%E4%B8%8E%E5%BE%85%E6%A0%B8%E6%B8%85%E5%8D%95.md) （[A](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKYOABk18akx1Z5N) · [Leon](https://alidocs.dingtalk.com/i/nodes/b9Y4gmKWrPNpBnG0seqLMq6MJGXn6lpz)），不在本页写成当前规模。

多人讨论中同时出现前 2—3 个月约 10%、首节课/满 50 节后的结算节点、前 10 节落地质量责任等不同方案；对象、基数、期限、结算条件、审批和执行状态均未冻结，不能合并为已生效的薪酬或佣金制度。

来源原件：[袁慧如反馈](../../sources/raw/J-21d9bb317a9010618bb1160f__36eb0efdbd25baeb.4c18cf080c4a.md) （[A](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHarY5DANJlemrZQ3) · [Leon](https://alidocs.dingtalk.com/i/nodes/P0MALyR8kl4DxXd2TDE30mPgW3bzYmDO)），修订 `36eb0efdbd25baeb.4c18cf080c4a`。P2 完整路径：`/Users/wangdong/Desktop/Leon-work/projects/TOC/_raw/meetings-raw/2026-09-09_StratPlan-2027/02_StratPlan-2027-1_原稿.md`（00:28:40—00:31:57、00:40:16—00:46:25）。v5/v6 摘录仅作对照，不构成独立证据。
<!-- common-feed:J-21d9bb317a9010618bb1160f@36eb0efdbd25baeb.4c18cf080c4a:end -->


> [!warning] 待审
> 本页编译自《Referral重启.md》（decision_state aligned、updated_at 2026-04-25、confidence medium、human_loop leon）。
> 内容未经 Leon 审定，**不得当作正式结论引用**；本页为 2026-04 时点判断记录，后续是否被 [2026-04-25-cost-per-launch下调至1500并转向Referral](../decisions/2026-04-25-cost-per-launch%E4%B8%8B%E8%B0%83%E8%87%B31500%E5%B9%B6%E8%BD%AC%E5%90%91Referral.md) （[A](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBzbD8B5r9YAn) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnZeY3nVxAZB1Gv)） 及 Q2 决策史演进见相关页。

## 当前判断（截至 2026-04-25）

- Referral 是 Q2 最确定的增长机会之一，但它不是流量问题，首先是**组织问题**：如果没有实际 owner 和端到端执行链条，Referral 很难从「机会」变成「增长引擎」。
- 2026-04-20「转介绍二季度爆发」会议把打法拆成 **foundation / focus / accelerator 三层结构**——Referral 不只是渠道加码，而是在同时承担量、质、流程改造和组织创新的任务。
- 2026-04-25 公司把 cost per launch 目标从 2000 比索下调到 1500 比索后，Referral 被进一步抬升：不只是高潜机会，而是必须承接更严财务约束的主渠道之一（详见 [2026-04-25-cost-per-launch下调至1500并转向Referral](../decisions/2026-04-25-cost-per-launch%E4%B8%8B%E8%B0%83%E8%87%B31500%E5%B9%B6%E8%BD%AC%E5%90%91Referral.md) （[A](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBzbD8B5r9YAn) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnZeY3nVxAZB1Gv)））。

## 为什么它重要

- 历史数据证明有人负责时，Referral 可以稳定提供高注册量。
- 它天然更接近信任传播，具备更高质量供给潜力。
- 相比全新陌生渠道，Referral 更适合成为低试错成本的放大量。

## 当前阻塞

- 过去较长时间缺少明确 owner，执行碎片化；老师对流程不熟，持续运营和成功案例沉淀不足；用户体验存在阻塞点（如「长链接疑似诈骗」等体验层问题）。
- 如果节后仍无法明确 owner，这条线只能做有限推动，难以承担 Q2 目标。

## 当前已知信号

- 2025-06 ~ 2025-10（有人负责时）：月均 Register 明显更高。
- 2025-11 ~ 2026-02（无人负责）：渠道贡献明显下滑。
- 2026-03（兼职补位后）：出现回暖，说明机会并未消失。

## 当前打法

- 把 owner 明确当成第一前提，而不是先堆活动和政策。
- 继续恢复 webinar、placement 和基础流程；从师龄、收入、地域维度识别核心推荐人群；同步修复体验层问题。
- 4 月底前优先落 PC 分享能力、关键人群 targeted campaign、fast track 与 mentor 型 referral。
- **2026-04-24 明确 trade-off**：Center / Referral 渠道中的老师可能因追求 B+ 而延缓参加 demo；招聘数量无压力时可接受，数量承压时会转化成真实风险。
- **取消针对 A 档的超额激励**（实际覆盖比例仅约 1～2%，distract 影响未知，取消后更利于控制激励方向）。
- 围绕 15% → 25% → 33% 质量目标，不能假设已有足够 solid 的历史成功抓手；Referral 线需要与整体战役一起接受「多打测试子弹、根据反馈快速收敛杠杆」的打法——加码不应只被理解为政策加码，而是主动开辟一组允许试错的质量实验。
- 2026-04-25 起：在 1500 比索约束下，Referral 从增长机会升级为优先承接渠道，MKT 与 KOL 资源需更明显向其回流。

## 2026-08-19 材料增量：运营雏形已出现，效果仍未验真

Jovic《Referral Updates》的复核材料补出一条候选漏斗：Referrer → Referral／Lead → Register → Pre-screen → PSO → Tech Check → NTT → Demo → Onboarding → Launch；也列出 Referral Link、Teacher App Links Sharing、MyPage、Applicant／Employee Referral、Recovery Leads、Talent Scout 等候选渠道。**这些是业务结构线索，不是正式术语表**：对象定义、cohort、互斥性、归因窗口和去重规则仍缺 Owner 确认。（源：2026-09-05_外教转介绍知识库入库建议_数字复核版.md§3A）

Referral Champions 已出现“筛选影响力／内容质量 → Referral Team 提供基础脚本 → Champion 增强 → 审批后直播或发布 Reels”的运行雏形；2026 年 1—8 月表内合计 5,408 Leads、304 Launch。它强化了本页“Referral 首先是组织与机制问题”的判断，但不能证明 Champions 已跑通：准入／退出条件、Owner、审核 SLA、归因规则和 Launch 后质量结果均未补齐。（源：同上§2.1、§3A）

本批同时发现六组汇总卡与明细冲突、四套 Launch 总量不一致。数字与完整 Gate 集中见 [外教转介绍数据口径冲突与待核清单](../queries/%E5%A4%96%E6%95%99%E8%BD%AC%E4%BB%8B%E7%BB%8D%E6%95%B0%E6%8D%AE%E5%8F%A3%E5%BE%84%E5%86%B2%E7%AA%81%E4%B8%8E%E5%BE%85%E6%A0%B8%E6%B8%85%E5%8D%95.md) （[A](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKYOABk18akx1Z5N) · [Leon](https://alidocs.dingtalk.com/i/nodes/b9Y4gmKWrPNpBnG0seqLMq6MJGXn6lpz)）。在 TOC-79／80 销账前，不把 51,847 Referral、Reels、Views、激励量或 Launch 数升级成“高质量获客已成立”，也不从 5.110M 与 3,880 直接推导现行 CPL 已达标。

## 早期机制回读：推荐和持续带教是不同贡献

4月20日稿把基础体验、分享与可视化作为基础，再试目标人群活动，并将快线、导师和保障薪酬列为加速候选。一次推荐与持续带教不能混算贡献：推荐多不证明培养有效，也不赋予推荐人对老师的管理或收入支配权。3000级奖励、持续收益与mentor均为当时方案讨论，不因后续重复出现就成为已批准制度；PC月底、App可能六月只是当时计划。（[转介绍二季度爆发稿](../../sources/raw/2026-04-20-转介绍二季度爆发会议.md) （[A](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS73Mz7O1WMwvDqPk) · [Leon](https://alidocs.dingtalk.com/i/nodes/1OQX0akWmxrMP2G1sjY3wOKw8GlDd3mE)） L24–70。）

## 9月10日原稿回读：收缩需要承接，Referral也受季节影响

China marketing的停止讨论与其他市场等待Referral承接后逐步放缓，是不同范围；同场随即提醒Q4候选人可能等年末奖金、不愿换工作，Referral同样受季节性影响。不能拼成所有市场立即停投、停招或固定十月生效。衡量终点转向毕业合格的讨论，也须保留新人实际获得授课机会这一条件；原稿“十课”等口述不覆盖后继毕业标准。（[9月10日组织讨论原转写](../../sources/raw/J-6dd5304ee21a6d5751bf0fb8__87ed0489366f3f6e.0e9826a5032f.md) （[A](https://alidocs.dingtalk.com/i/nodes/14dA3GK8gjBKbMrDiE9Zq2MGJ9ekBD76) · [Leon](https://alidocs.dingtalk.com/i/nodes/pYLaezmVNejqr3vQtKZD60kgWrMqPxX6)） L4240–4372、5008–5056、5278–5410；与已有完整合并纪要是同一讨论链，不增加独立证据票。）

## Timeline

- 2025-06 至 2025-10：有明确负责人阶段，Referral 表现较好。
- 2025-11 至 2026-02：长期缺乏 owner，渠道贡献明显下滑。
- 2026-03-27：周会明确过去 6 个月缺乏明确负责人是关键根因。
- 2026-04-01：被定性为「显然确定，但当前 not ready」的 Q2 机会。
- 2026-04-20：Leon 与 Jen 对齐确认继续调高 Referral 预期，进入一轮政策巩固、加码和流程试验；同日「转介绍二季度爆发」会议拆出 foundation / focus / accelerator 三层。
- 2026-04-24：Leon 与 Jen / 慧茹明确 5 月 Referral 加码的关键 trade-off（B+ vs demo），决议取消 A 档超额激励，确立「多打测试子弹」质量推进原则。
- 2026-04-25：公司把 cost per launch 从 2000 下调到 1500 比索；Leon 与 Jen 明确更坚决从 MKT 与 KOL 收缩资源、集中到 Referral。
- 2026-09-05：新增 Jovic 2026-01—08 报告的候选业务结构与数据冲突；保留项目 `review: 待审`，未升级 CURRENT 状态。

## 相关页面

- 决策：[2026-04-25-cost-per-launch下调至1500并转向Referral](../decisions/2026-04-25-cost-per-launch%E4%B8%8B%E8%B0%83%E8%87%B31500%E5%B9%B6%E8%BD%AC%E5%90%91Referral.md) （[A](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBzbD8B5r9YAn) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnZeY3nVxAZB1Gv)）（Referral 升级为主承接渠道的直接决策）· [Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md) （[A](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y) · [Leon](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2)）（Referral 三层打法、owner 问题、A 档超额激励取消等时点判断）
- 项目：[漏斗分流策略](%E6%BC%8F%E6%96%97%E5%88%86%E6%B5%81%E7%AD%96%E7%95%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKZ0qMO81waOeDk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6zOB9W1DK0g6l)）（渠道切分：MKT/KOL 收缩、Referral 承接比例）
- 战役：[外教质量提升战役](%E5%A4%96%E6%95%99%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E6%88%98%E5%BD%B9.md) （[A](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKZRYEO81waOeDk) · [Leon](https://alidocs.dingtalk.com/i/nodes/Exel2BLV5znlv6Y3fpX7wXRbJgk9rpMq)）
- 项目：[招聘战役](%E6%8B%9B%E8%81%98%E6%88%98%E5%BD%B9.md) （[A](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9ZbRmkeWyMoPYe1) · [Leon](https://alidocs.dingtalk.com/i/nodes/dxXB52LJqnjXBmGdiZqoeljl8qjMp697)）（招聘战役总线）· [沟通矩阵建设](%E6%B2%9F%E9%80%9A%E7%9F%A9%E9%98%B5%E5%BB%BA%E8%AE%BE.md) （[A](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazlej3eJlemrZQ3) · [Leon](https://alidocs.dingtalk.com/i/nodes/mweZ92PV6M7l9QrqHq2RBEGkWxEKBD6p)）（沟通阵地基建）


## 历史附录：漏斗分流双轨（合并自 [漏斗分流策略](%E6%BC%8F%E6%96%97%E5%88%86%E6%B5%81%E7%AD%96%E7%95%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKZ0qMO81waOeDk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6zOB9W1DK0g6l)） · 2026-09-11）

> 溯源：[漏斗分流策略](%E6%BC%8F%E6%96%97%E5%88%86%E6%B5%81%E7%AD%96%E7%95%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKZ0qMO81waOeDk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6zOB9W1DK0g6l)）（2026-04 时点）。双轨+1500 约束下资源切分已被 04-25 决策与本页 Referral 主渠道叙事吸收；独特 blockers 迁此保留。

- **双轨原则**：主漏斗保稳定（不大手术）；试验田承接低效渠道与高风险实验（产品化/AI 化流程、Fast Track 等）；高质量 leads 尽量清出主漏斗。
- **1500 约束改写（04-25）**：双轨须先服从 cost-per-launch 1500 比索；外部投放与 KOL 资源地位下修，Referral 承接权重上升（见 [2026-04-25-cost-per-launch下调至1500并转向Referral](../decisions/2026-04-25-cost-per-launch%E4%B8%8B%E8%B0%83%E8%87%B31500%E5%B9%B6%E8%BD%AC%E5%90%91Referral.md) （[A](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBzbD8B5r9YAn) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnZeY3nVxAZB1Gv)））。
- **迁入的 blockers / 待明确（独特）**：试验田范围与渠道分流规则未锁定；试验田 owner、评估指标与止损条件未明确；与 Fast Track 及低效渠道的资源边界未排清；1500 约束下 MKT/KOL/Referral 切分规则尚未正式成文；何时允许试验田经验反哺主漏斗未定。
- **Timeline 要点**：04-01 创新放市场测试渠道 → 04-15 双轨升为倾向性大决策 → 04-20 KOL 倾向后被 04-25 约束改写 → 04-25 集中 Referral。

合并执行：BCD 提案 D8 · Leon 整包批准 · 2026-09-11。

## 2026-09-10 完整会议与执行版 v2.2：先冻结责任链，再试机制

组织与人才专场的完整合并纪要将 Referral 与 Center 治理列为两个优先原子小队候选，并把“没人管 Referral”的批评收束为：虽然已有运营人员，但仍缺少足够专注的端到端负责人、资源、交接边界及业务—工程共同施工。Jovic、Ben、Aika、TOC 与菲律宾骨干之间的角色仍在讨论，不能写成组织已重组或 owner 已正式任命。（源：`J-735fad10d2f2ad9f83e27271@355663e6fffc3bad.aa3fe0b49a7e`；同字节登记 `J-f8fd9005ce87882cd45f407f@355663e6fffc3bad.aa3fe0b49a7e`，只计一份内容证据。）

Agent“二宝”的《执行版 v2.2》补出 KOC/Captain、分段奖金、反作弊、定向触达和 90 天试验等组合机制，但文件自标 **DRAFT**，并明确不是慧茹决定。可用于设计试验的最小硬门是：先核 Referral/TBT 的唯一归因口径与重复计酬，触达前由法务确认不诱导现有合同违约及个人数据使用边界，工资／奖金／黑名单复核另取审批，并为教师提供解释、申诉和退出路径。未经这些门，不登记为现行政策或执行计划。（源：`J-e24dd162f0238830ed3713be`，revision `acc5118b37fd769f.aa3fe0b49a7e`。）

源内关于 Polly 常规 ₱870、活动期 ₱1,740、我方 ₱1,500，及 2025-12 双平台名单 772 人／on 333／off 375／hei 64，均依赖本 task 未交付的海报或名单原件；这里只保留为 Agent 提案引用的待核输入，不升级为当前竞品事实、名单事实或权益依据。具体冲突进入 [外教转介绍数据口径冲突与待核清单](../queries/%E5%A4%96%E6%95%99%E8%BD%AC%E4%BB%8B%E7%BB%8D%E6%95%B0%E6%8D%AE%E5%8F%A3%E5%BE%84%E5%86%B2%E7%AA%81%E4%B8%8E%E5%BE%85%E6%A0%B8%E6%B8%85%E5%8D%95.md) （[A](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKYOABk18akx1Z5N) · [Leon](https://alidocs.dingtalk.com/i/nodes/b9Y4gmKWrPNpBnG0seqLMq6MJGXn6lpz)）。

来源原件：[会议登记一](../../sources/provenance-local/common-feed/J-735fad10d2f2ad9f83e27271__355663e6fffc3bad.aa3fe0b49a7e)（本地资料，钉钉／GitHub未提供）／[旁路](../../sources/provenance-local/common-feed/J-735fad10d2f2ad9f83e27271__355663e6fffc3bad.aa3fe0b49a7e.delivery.json)（本地资料，钉钉／GitHub未提供）；[会议登记二](../../sources/provenance-local/common-feed/J-f8fd9005ce87882cd45f407f__355663e6fffc3bad.aa3fe0b49a7e)（本地资料，钉钉／GitHub未提供）／[旁路](../../sources/provenance-local/common-feed/J-f8fd9005ce87882cd45f407f__355663e6fffc3bad.aa3fe0b49a7e.delivery.json)（本地资料，钉钉／GitHub未提供）；[v2.2 原稿](../../sources/provenance-local/common-feed/J-e24dd162f0238830ed3713be__acc5118b37fd769f.aa3fe0b49a7e)（本地资料，钉钉／GitHub未提供）／[旁路](../../sources/provenance-local/common-feed/J-e24dd162f0238830ed3713be__acc5118b37fd769f.aa3fe0b49a7e.delivery.json)（本地资料，钉钉／GitHub未提供）。三项发生日 2026-09-10、接收日 2026-09-11，`actor=multiple`；页面继续 `review: 待审`、`projection: public`。

<!-- meaning-navigation:start -->
## 所在的经营问题

[D02 教师获取与准入](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D02-%E6%95%99%E5%B8%88%E8%8E%B7%E5%8F%96%E4%B8%8E%E5%87%86%E5%85%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9ZKbGp6WyMoPYe1) · [Leon](https://alidocs.dingtalk.com/i/nodes/4lgGw3P8vR2aBrGZSZjG1dEq85daZ90D)） · [D03 新师成材与早期经营](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D03-%E6%96%B0%E5%B8%88%E6%88%90%E6%9D%90%E4%B8%8E%E6%97%A9%E6%9C%9F%E7%BB%8F%E8%90%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/ndMj49yWjXK9ykGpubzXm30bJ3pmz5aA) · [Leon](https://alidocs.dingtalk.com/i/nodes/OG9lyrgJPzkq5xD6fln9E0l3WzN67Mw4)） · [D11 教师体验与公平治理](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D11-%E6%95%99%E5%B8%88%E4%BD%93%E9%AA%8C%E4%B8%8E%E5%85%AC%E5%B9%B3%E6%B2%BB%E7%90%86.md) （[A](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazxGalOJlemrZQ3) · [Leon](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9ZKzgMeWyMoPYe1)）

返回 [TutorOS第二层经营地图](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%AC%AC%E4%BA%8C%E5%B1%82%E7%BB%8F%E8%90%A5%E5%9C%B0%E5%9B%BE.md) （[A](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l) · [Leon](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v)） / [TutorOS知识总图](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%9F%A5%E8%AF%86%E6%80%BB%E5%9B%BE.md) （[A](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE) · [Leon](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno)）。以上是经营问题的阅读入口；具体判断仍按本页的来源、日期和审核范围使用。
<!-- meaning-navigation:end -->
