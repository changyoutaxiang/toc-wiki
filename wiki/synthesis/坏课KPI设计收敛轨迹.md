---
type: synthesis
title: 坏课 KPI 设计收敛轨迹
tags: [synthesis, 外教战役, 坏课KPI, 外援, merged]
related: [坏课KPI设计稿, 2026-08-31-外教质量提升双周会-坏课率Q3Q4与固定老师前置指标, 2026-08-26-坏课治理双方案灰度拍板, 2026-08-27-课堂问题数据口径与课后治理优先, 外教质量提升战役]
created: 2026-08-31
updated: 2026-09-15
sources: ["LeonWikiClean:synthesis/坏课-kpi-设计收敛轨迹"]
review: 已审
review_scope: 2026-09-15 Leon批量认可转已审：R1批量蒸馏页按其指示默认已审，认可蒸馏忠实性，未逐条人工复核；页面所载未决问题与待验证事项不因此裁决
---

# 坏课 KPI 设计收敛轨迹
> **✅ 已合并入 [坏课KPI设计稿](../queries/%E5%9D%8F%E8%AF%BEKPI%E8%AE%BE%E8%AE%A1%E7%A8%BF.md) （[A](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7QK31G2WMwvDqPk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6ombDW1DK0g6l)）（2026-09-11，Leon 批 BCD）**：本页保留演化痕迹，**不删除**。现行阅读请以目标页为准；本页独特事实已迁入目标页对应附录/小节。


> 来源外援库 **Leon Wiki Clean**（corpus-distill-v2 自动蒸馏）：综合层未经 Leon 审定（review: 待审），事实可复核；外援推断节已标注「（外援推断）」，不当作正式结论引用。

坏课 KPI 设计收敛轨迹：这页总结的是教师侧战役指标如何从「看好老师数量」收敛到「看坏课率」。当前收敛出的结论是，坏课率被用作外教战役级的交付可靠性指标，且坏课必须是「客观有标准且可侦测」的事件；学生主观反馈不纳入坏课分子，而是作为探针和质检触发信号。（源：2026-08-26_坏课KPI设计稿件_v0.1.html；2026-08-26_坏课KPI设计稿件_v0.3.html）

## 事实

1. 8/25 的 Teacher event and KPI 会议形成共识：Q3/Q4 教师侧 KPI 重构，用 bad lesson rate 替代 A/B+ 老师数量；王东澄清这不是个人 KPI，而是整个战役衡量成败的量和率。2. 旧尺走不下去的原因包括：坏课率更贴近客户价值，且用户投诉/不满的最大来源集中在交付不稳定，尤其是老师缺席与设备/网络问题。3. 设计口径已收敛到分子=盒内事件按课程/约课唯一 ID 去重后的坏课课次，分母=应交付约课课次；分市场呈现，千分位展示。（源：2026-08-26_坏课KPI设计稿件_v0.1.html；2026-08-26_坏课KPI设计稿件_v0.3.html）

1. 盒子设计经历了从四大类到三大类的收敛：纪律、稳定、行为是一期可纳入的核心，学生反馈类最终不纳入坏课。2. P0 准则已经定下：坏课必须同时满足「客观有标准且可侦测」；无精打采、态度冷场这类标准模糊或难侦测的行为不进盒子。3. 纪律类中的缺席、迟到、早退和稳定类中的黑屏、无声、断连中断等，属于当前讨论中的主要候选事件。（源：2026-08-26_坏课KPI设计稿件_v0.1–v0.3 系列，外援未标具体锚点）

1. 节奏上，Q3 先冻结定义和基线，Q4 再挂目标。2. 目标值需要在「上层期望」和「可影响杠杆置信度」之间协商，当前前置红线是没有正式基线就不能挂目标。3. 数据源、行为类侦测、阈值冻结都还在对齐中，说明这条轨迹已经收敛出方向，但还没有完全生效。（源：2026-08-26_坏课KPI设计稿件_v0.1.html；2026-08-26_坏课KPI设计稿件_v0.2.html；2026-08-26_坏课KPI设计稿件_v0.3.html）

## 推断（外援推断）

1. 这条收敛轨迹的核心，不是在扩张「坏课」的范围，而是在把「坏」的定义压成可测、可复核、可被业务动作改变的盒子。（源：2026-08-26_坏课KPI设计稿件_v0.3.html）
2. 因为学生反馈类被移出分子，坏课 KPI 更像一个交付可靠性指标，而不是满意度总表；满意度相关信息转为外部探针，用来反向校验坏课口径是否打偏。（源：2026-08-26_坏课KPI设计稿件_v0.3.html）

## 仍待验证

- ③类教学行为的最终红线清单还没有全部冻结，哪些行为能被稳定侦测并纳入坏课，仍在筛选。（源：2026-08-26_坏课KPI设计稿件_v0.3.html）
- ②类课堂稳定事件的阈值还未冻结，黑屏、无声、断连中断多严重算坏课仍待定。（源：2026-08-26_坏课KPI设计稿件_v0.3.html；2026-08-26_坏课KPI设计稿件_v0.2.html）
- 目标值与正式挂 KPI 的时点仍未定稿，当前只确认先冻结基线、后挂目标。（源：2026-08-26_坏课KPI设计稿件_v0.3.html；2026-08-26_坏课KPI设计稿件_v0.2.html）

## 源文件清单

- `raw/sources/外教战役/2026-08-26_坏课KPI设计稿件_v0.1.html`
- `raw/sources/外教战役/2026-08-26_坏课KPI设计稿件_v0.2.html`
- `raw/sources/外教战役/2026-08-26_坏课KPI设计稿件_v0.3.html`

## 与 wiki 的连接

- **指标/决策页**：[坏课KPI设计稿](../queries/%E5%9D%8F%E8%AF%BEKPI%E8%AE%BE%E8%AE%A1%E7%A8%BF.md) （[A](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7QK31G2WMwvDqPk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6ombDW1DK0g6l)）（坏课率 Q3/Q4 指标设计稿 v0.4 + 08-31 提案进展，本页的指标设计收敛轨迹即其上游）；[2026-08-31-外教质量提升双周会-坏课率Q3Q4与固定老师前置指标](../decisions/2026-08-31-%E5%A4%96%E6%95%99%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E5%8F%8C%E5%91%A8%E4%BC%9A-%E5%9D%8F%E8%AF%BE%E7%8E%87Q3Q4%E4%B8%8E%E5%9B%BA%E5%AE%9A%E8%80%81%E5%B8%88%E5%89%8D%E7%BD%AE%E6%8C%87%E6%A0%87.md) （[A](https://alidocs.dingtalk.com/i/nodes/7QG4Yx2JpLMrqaGdcq4ax2Q4J9dEq3XD) · [Leon](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzLR7qE0VgN7R35y)）（坏课率 Q3/Q4 口径原则，待审）；[2026-08-26-坏课治理双方案灰度拍板](../decisions/2026-08-26-%E5%9D%8F%E8%AF%BE%E6%B2%BB%E7%90%86%E5%8F%8C%E6%96%B9%E6%A1%88%E7%81%B0%E5%BA%A6%E6%8B%8D%E6%9D%BF.md) （[A](https://alidocs.dingtalk.com/i/nodes/X6GRezwJlAvgOpGkS05doga98dqbropQ) · [Leon](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzkLEwX38BQEx5rG)）（灰度拍板与 DRI 授权）。
- **口径/概念页**：[2026-08-27-课堂问题数据口径与课后治理优先](../decisions/2026-08-27-%E8%AF%BE%E5%A0%82%E9%97%AE%E9%A2%98%E6%95%B0%E6%8D%AE%E5%8F%A3%E5%BE%84%E4%B8%8E%E8%AF%BE%E5%90%8E%E6%B2%BB%E7%90%86%E4%BC%98%E5%85%88.md) （[A](https://alidocs.dingtalk.com/i/nodes/wva2dxOW4Yml41o0IYa2D3BAVbkz3BRL) · [Leon](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKr0Gqq58akx1Z5N)）（五类判定口径与课后治理优先）；[一套标准两个接口](../concepts/%E4%B8%80%E5%A5%97%E6%A0%87%E5%87%86%E4%B8%A4%E4%B8%AA%E6%8E%A5%E5%8F%A3.md) （[A](https://alidocs.dingtalk.com/i/nodes/14dA3GK8gjBKbMrDiE5yzPgaJ9ekBD76) · [Leon](https://alidocs.dingtalk.com/i/nodes/3NwLYZXWyna7ByKdiG50mmjyVkyEqBQm)）（内部物理尺/对外沟通口径解耦——「分子盒内事件、学生反馈作探针」与内外接口解耦同构）。
- **项目页**：[外教质量提升战役](../projects/%E5%A4%96%E6%95%99%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E6%88%98%E5%BD%B9.md) （[A](https://alidocs.dingtalk.com/i/nodes/ZQYprEoWongN5ZGdiQKZRYEO81waOeDk) · [Leon](https://alidocs.dingtalk.com/i/nodes/Exel2BLV5znlv6Y3fpX7wXRbJgk9rpMq)）；[新师训战营](../projects/%E6%96%B0%E5%B8%88%E8%AE%AD%E6%88%98%E8%90%A5.md) （[A](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzR6edmn8BQEx5rG) · [Leon](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKr6O7lq8akx1Z5N)）（坏课率与试用期机制同属战役重构）。
- **问题账接续（2026-09-15）：** TOC-15 已定迟到 1 分钟起算；TOC-16 已定假早退并入，当前 Wiki 事件表已回写（TOC-92 的本地部分）。四版原设计文件仍保留历史。TOC-17 数据源、TOC-18 正式基线、TOC-67 过渡组合及稳定类具体标准仍各自保留限制；不能把历史“阈值未冻结”概括成所有事项都未决定。具体边界见[坏课KPI设计稿](../queries/%E5%9D%8F%E8%AF%BEKPI%E8%AE%BE%E8%AE%A1%E7%A8%BF.md) （[A](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7QK31G2WMwvDqPk) · [Leon](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5Iey6ombDW1DK0g6l)）与[问题账](../%E9%97%AE%E9%A2%98%E8%B4%A6.md)（本地资料，钉钉／GitHub未提供）。
