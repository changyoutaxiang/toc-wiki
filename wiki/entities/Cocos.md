---
rebuild_review_scope: "2026-09-15原料重蒸馏新增整理未经逐条人审；原认可沿原日期与范围保留"
type: entity
title: Cocos
tags: [entity, product, cocos, 设备标准, 教材]
related: [2026-05-29-设备标准锚定Cocos黄金, 老师质量提升飞轮, 好老师生命周期, Q2关键决策与判断, 2026-07-13-CEO下半年外教战役指示-双主帅H2总纲]
created: 2026-08-30
updated: 2026-09-15
sources: ["外教战役/2026-05-设备标准锚定Cocos黄金.md", "外教战役/好老师生命周期.md", "外教战役/老师质量提升飞轮.md", "外教战役/Q2关键决策与判断.md"]
review: 记录
---

# Cocos

> 本页为教学产品/系统实体的事实与判断记录，含时点性信息（截至 2026-05-29），非当前事实源；实时产品状态以公司产品与业务数据为准。
> **口径注**：源文件中 Cocos 指教学产品/教材升级系统（「三季度教材大幅升级」「Cocos 新教材」）；AC 是老师上课用的客户端（源黑话表：「AC = 老师上课用的客户端」）。设备标准决策将「Cocos 最低硬件标准」作为黄金锚，AC 侧落地自适应动态分——二者同属设备标准治理的技术域。

## 身份

Cocos：外教教学产品/教材升级系统，计划三季度（Q3）上线新教材。源判断称其为「教学质量 game changer」（[Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md) （[A](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y) · [Leon](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2)），截至 2026-05-14）：“60分自动抬到75–85分”保留为早期体验提升的设想，不能当CE教师评级或实测效果。5月13日稿明确A/B+不会随课件自动升档；高级课程可能更依赖教师能力，机械读课件已有投诉反例。

## 与设备标准的关系

- **黄金锚**：2026-05-29 决策以 Cocos 最低硬件标准为「黄金」锚定三套打分体系（见 [2026-05-29-设备标准锚定Cocos黄金](../decisions/2026-05-29-%E8%AE%BE%E5%A4%87%E6%A0%87%E5%87%86%E9%94%9A%E5%AE%9ACocos%E9%BB%84%E9%87%91.md) （[A](https://alidocs.dingtalk.com/i/nodes/Exel2BLV5znlv6Y3fpb4763KJgk9rpMq) · [Leon](https://alidocs.dingtalk.com/i/nodes/MyQA2dXW7eRlDK7jt1vdAKzNJzlwrZgb)））——三套打分当三种货币，拿一台刚及格机器分别在 A/B/C 跑分做等效映射。
- **现行标准接续**：3500分、2026年7月1日全量上线，沿后继人类纠正使用。历史动态配置与竞品比较不另立一把现行尺。
- **AC 自适应动态分**：7/1前上线是历史目标，不是功能完成回执；与3500标准上线分开核验。
- **招聘侧**：设备分前置为招聘质控项（Q3 Cocos 教材上线后设备成为最大杠杆之一，见 [老师质量提升飞轮](../concepts/%E8%80%81%E5%B8%88%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E9%A3%9E%E8%BD%AE.md) （[A](https://alidocs.dingtalk.com/i/nodes/1OQX0akWmxrMP2G1sjE2XAoK8GlDd3mE) · [Leon](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7g53qKPWMwvDqPk)））。

## 硬件达标现状（截至 2026-05-14）

- 仅 66 名 HBT 教师设备达标，约一半教师硬件不达标——被源称为「被忽视的定时炸弹」（[Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md) （[A](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y) · [Leon](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2)））。
- 存量设备检测大致为三分之一满足、三分之一存疑/勉强、三分之一不满足（[好老师生命周期](../concepts/%E5%A5%BD%E8%80%81%E5%B8%88%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.md) （[A](https://alidocs.dingtalk.com/i/nodes/wva2dxOW4Yml41o0IYa12ndzVbkz3BRL) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnP2K4AVxAZB1Gv)），截至 2026-05-25）。
- i5八代、I3适配是当时待实测的运行假设，不保证全部课件和插件组合；采购22000有当时确认记载，但不是今天的教师准入。

## 技术路径（2026-05-14 APIs/Cocos 技术需求会）

从「单纯抬高招聘硬件门槛」转为组合方案：

- 教材轻量化：压缩至 50MB 内（原 400MB）。
- 设备/网络动态分档下发、低配设备隐藏高耗能功能（FPS 降档、预加载、限制插件数量、调整 CPU 优先级——美颜/降噪/虚拟背景让位于 Cocos）。
- 下一步实测 i5 8th Gen + 8G 内存下的性能舒适线和上限。
- Teacher APP 外包路径可行，但涉及教师敏感数据与 API 权限，必须经过权限隔离、代码 review、上线审计和长期维护 owner 设计。

## 本轮读源限定

[5月13日Cocos稿](../../sources/raw/2026-05-13-Cocos课件战略影响讨论.md) （[A](https://alidocs.dingtalk.com/i/nodes/wva2dxOW4Yml41o0IYdm3Z6bVbkz3BRL) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrdz20raVxAZB1Gv)） L37–49、124–128、169区分课堂体验与教师评级；自动纪要按语义猜测speaker，不能反推引号内均为Leon原话。同日周会还保留两路按验证加权的方向，不因“押课件”而取消教学能力建设。[5月14日技术稿](../../sources/raw/2026-05-14-APIs-and-Cocos-Technical-requirements.md) （[A](https://alidocs.dingtalk.com/i/nodes/X6GRezwJlAvgOpGkS0n9mlp98dqbropQ) · [Leon](https://alidocs.dingtalk.com/i/nodes/14dA3GK8gjBKbMrDiE9jLRqxJ9ekBD76)） L54–59、94–110的教材50MB、动态适配与测试机型是当时目标；先做20/96课程后，其余76门如何接续仍未定，不能只核性能而漏后续教学供给。

## 相关页面

- 决策：[2026-05-29-设备标准锚定Cocos黄金](../decisions/2026-05-29-%E8%AE%BE%E5%A4%87%E6%A0%87%E5%87%86%E9%94%9A%E5%AE%9ACocos%E9%BB%84%E9%87%91.md) （[A](https://alidocs.dingtalk.com/i/nodes/Exel2BLV5znlv6Y3fpb4763KJgk9rpMq) · [Leon](https://alidocs.dingtalk.com/i/nodes/MyQA2dXW7eRlDK7jt1vdAKzNJzlwrZgb)）
- 机制：[老师质量提升飞轮](../concepts/%E8%80%81%E5%B8%88%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E9%A3%9E%E8%BD%AE.md) （[A](https://alidocs.dingtalk.com/i/nodes/1OQX0akWmxrMP2G1sjE2XAoK8GlDd3mE) · [Leon](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7g53qKPWMwvDqPk)）（硬件门槛前置环节）· [好老师生命周期](../concepts/%E5%A5%BD%E8%80%81%E5%B8%88%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.md) （[A](https://alidocs.dingtalk.com/i/nodes/wva2dxOW4Yml41o0IYa12ndzVbkz3BRL) · [Leon](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrnP2K4AVxAZB1Gv)）（硬件杠杆）
- 战役：[2026-07-13-CEO下半年外教战役指示-双主帅H2总纲](../decisions/2026-07-13-CEO%E4%B8%8B%E5%8D%8A%E5%B9%B4%E5%A4%96%E6%95%99%E6%88%98%E5%BD%B9%E6%8C%87%E7%A4%BA-%E5%8F%8C%E4%B8%BB%E5%B8%85H2%E6%80%BB%E7%BA%B2.md) （[A](https://alidocs.dingtalk.com/i/nodes/NkDwLng8ZLRqrGZjc3L1DlPQVKMEvZBY) · [Leon](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZnpyqOv86EDybno)）（网络设备纳入 30 天验证维度）· [Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md) （[A](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y) · [Leon](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2)）（Cocos/AC 技术路径演进）

## Related
- [TOC/decisions/2026-05-14-Cocos教材瘦身与设备动态适配](../decisions/2026-05-14-Cocos%E6%95%99%E6%9D%90%E7%98%A6%E8%BA%AB%E4%B8%8E%E8%AE%BE%E5%A4%87%E5%8A%A8%E6%80%81%E9%80%82%E9%85%8D.md) （[A](https://alidocs.dingtalk.com/i/nodes/nYMoO1rWxaZnB3GdI9kPdKkbV47Z3je9) · [Leon](https://alidocs.dingtalk.com/i/nodes/pYLaezmVNejqr3vQtKxN4aXnWrMqPxX6)）

<!-- toc-map:backlinks:start -->

## 所属经营域与导航

相关经营问题：[D05 · 授课条件与模式治理](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D05-%E6%8E%88%E8%AF%BE%E6%9D%A1%E4%BB%B6%E4%B8%8E%E6%A8%A1%E5%BC%8F%E6%B2%BB%E7%90%86.md) · [D08 · 好课判断与逐课证据](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D08-%E5%A5%BD%E8%AF%BE%E5%88%A4%E6%96%AD%E4%B8%8E%E9%80%90%E8%AF%BE%E8%AF%81%E6%8D%AE.md) · [D10 · 教师成长与教学支持](../%E9%AA%A8%E6%9E%B6/TutorOS%E7%BB%8F%E8%90%A5%E5%9F%9F-D10-%E6%95%99%E5%B8%88%E6%88%90%E9%95%BF%E4%B8%8E%E6%95%99%E5%AD%A6%E6%94%AF%E6%8C%81.md)

[在本地目录反查本页](../TutorOS%E6%9C%AC%E5%9C%B0%E7%9F%A5%E8%AF%86%E5%AF%BC%E8%88%AA.md#page-66463c41dd6dbc8d)（本地资料，钉钉／GitHub未提供）。归属仅用于导航，不改变本页审态与适用边界。

<!-- toc-map:backlinks:end -->
