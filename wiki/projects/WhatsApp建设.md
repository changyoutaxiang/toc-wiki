---
type: project
title: WhatsApp 建设
tags: [battle, infra, comms, whatsapp, archive-candidate]
related: [老师APP重启, Q2关键决策与判断]
created: 2026-08-30
updated: 2026-09-15
sources: ["外教战役/WhatsApp建设.md"]
review: 已审
review_scope: 2026-09-15 Leon批量认可转已审：R1批量蒸馏页按其指示默认已审，认可蒸馏忠实性，未逐条人工复核；页面所载未决问题与待验证事项不因此裁决
---

# WhatsApp 建设
> **归档候选 2026-09-11（Leon 批）**：draft/薄内容，待后续物理归档；本轮不搬家。


> [!warning] 页级 review 已于 2026-09-15 批量认可转已审（蒸馏忠实性）
> 本页编译自《WhatsApp建设.md》（decision_state draft、updated_at 2026-05-07、human_loop leon）。
> 项目档案待拆解，内容未经 Leon 审定，**不得当作正式结论引用**。

## 当前判断（截至 2026-05-07）

「WhatsApp 建设」是「沟通阵地」基建下挂的两条子项目之一（与 [老师APP重启](%E8%80%81%E5%B8%88APP%E9%87%8D%E5%90%AF.md) （[A](https://alidocs.dingtalk.com/i/nodes/yQod3RxJKGDly0PASl2kd6aeJkb4Mw9r) · [Leon](https://alidocs.dingtalk.com/i/nodes/MyQA2dXW7eRlDK7jt1v3P2EzJzlwrZgb)） 并列），承担候选人 / 老师沟通的高触达辅助阵地角色。

- **2026-05-07 定位明确**：WhatsApp **不是唯一主阵地，而是高触达辅助阵地**，主要服务蜜月期提醒、异常升级和课后纠偏。
- 项目档案待拆解：Leon 在未来 1-2 天内会从业务角度补齐主阵地 rollout 范围、协同 owner、第一批接入节点、与「老师 APP 重启」的分工边界。

## 状态卡片

- owner: Tammi；priority p0；decision_state draft。
- blockers：触达分层、蜜月期 SOP、与 App / SMS 的边界仍待落地。
- next step：把 WhatsApp 定位成高触达辅助阵地，优先承接蜜月期提醒 / 课后纠偏 / 异常升级，并与 App 主阵地和短信兜底分层清楚。

## 项目定义

- 候选人 / 老师沟通的辅助高触达通道。
- 承接 App 主阵地无法覆盖或不适合覆盖的提醒与跟进。
- 作为蜜月期课程的强提醒与快速反馈补充。

## 当前共识

- WhatsApp 触达率高，但不适合承担唯一底层方案。
- App 主阵地负责高频、可控、零成本触达；SMS / Email 负责兜底。
- WhatsApp 更适合作为异常升级、个别私聊与补充提醒阵地。

## 下一步

- 明确虚拟手机和账号风控边界。
- 把蜜月期课前提醒、课后反馈、异常升级三类场景列成第一版需求。
- 和老师 APP 的主阵地职责拆清楚，避免双主阵地混用（见 [老师APP重启](%E8%80%81%E5%B8%88APP%E9%87%8D%E5%90%AF.md) （[A](https://alidocs.dingtalk.com/i/nodes/yQod3RxJKGDly0PASl2kd6aeJkb4Mw9r) · [Leon](https://alidocs.dingtalk.com/i/nodes/MyQA2dXW7eRlDK7jt1v3P2EzJzlwrZgb)））。

## Timeline

- 2026-05-07：新讨论明确 WhatsApp 应定位为高触达辅助阵地，而不是唯一主阵地。

## 相关页面

- 项目：[老师APP重启](%E8%80%81%E5%B8%88APP%E9%87%8D%E5%90%AF.md) （[A](https://alidocs.dingtalk.com/i/nodes/yQod3RxJKGDly0PASl2kd6aeJkb4Mw9r) · [Leon](https://alidocs.dingtalk.com/i/nodes/MyQA2dXW7eRlDK7jt1v3P2EzJzlwrZgb)）（沟通阵地另一子项目，体制内主阵地）
- 决策：[Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md) （[A](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y) · [Leon](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2)）（沟通矩阵建设优先级高于零散修漏斗等时点判断）
- 项目：[沟通矩阵建设](%E6%B2%9F%E9%80%9A%E7%9F%A9%E9%98%B5%E5%BB%BA%E8%AE%BE.md) （[A](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazlej3eJlemrZQ3) · [Leon](https://alidocs.dingtalk.com/i/nodes/mweZ92PV6M7l9QrqHq2RBEGkWxEKBD6p)）（本项目与老师 APP 重启的上级基建）

<!-- toc-map:backlinks:start -->

## 所属经营域与导航

相关经营问题：[D03 · 新师成材与早期经营](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D03-%E6%96%B0%E5%B8%88%E6%88%90%E6%9D%90%E4%B8%8E%E6%97%A9%E6%9C%9F%E7%BB%8F%E8%90%A5.md) · [D09 · 履约恢复与问题治理](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D09-%E5%B1%A5%E7%BA%A6%E6%81%A2%E5%A4%8D%E4%B8%8E%E9%97%AE%E9%A2%98%E6%B2%BB%E7%90%86.md) · [D14 · 事实标准与协同执行](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D14-%E4%BA%8B%E5%AE%9E%E6%A0%87%E5%87%86%E4%B8%8E%E5%8D%8F%E5%90%8C%E6%89%A7%E8%A1%8C.md)

[在本地目录反查本页](../TutorOS%E6%9C%AC%E5%9C%B0%E7%9F%A5%E8%AF%86%E5%AF%BC%E8%88%AA.md#page-72b82a3f745c4945)（本地资料，钉钉／GitHub未提供）。归属仅用于导航，不改变本页审态与适用边界。

<!-- toc-map:backlinks:end -->
