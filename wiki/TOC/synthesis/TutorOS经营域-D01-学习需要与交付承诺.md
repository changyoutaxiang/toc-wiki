---
projection: public
type: synthesis
title: Tutor OS 经营域 D01｜学习需要与交付承诺
tags: [TutorOS, 第二层经营域, 学习需要, 交付承诺, 供需]
related: [TutorOS第二层经营地图, TutorOS知识总图, TutorOS设计宪法全文, TOC成立后-教师运营系统地图与责任清单, X-Y-Z三轴经营模型]
created: 2026-09-14
updated: 2026-09-14
sources: ["common-feed/J-ec8e516b745b355494be9b0b__37a045e8a9f5aec8.e0be7b3e7cdb.html", "外教战役/TOC成立后_教师运营系统地图与责任清单_草稿_v0.3.md", "外教战役/X-Y-Z三轴经营模型.md"]
review: 待审
review_scope: 第二层由Agent综合建设，具体主张按所引来源状态使用；未逐条经Leon认领
architecture_version: "1.1"
meaning_domain: D01
---

# 学习需要与交付承诺

返回 [[TutorOS第二层经营地图]] / [[TutorOS知识总图]]。

> 当前最重要的理解：承诺不是“有老师”或“系统接受了预约”，而是对某个学生、某项学习任务和某个时段，平台有把握交付一位合格、适配且真实可用的教师。

## 当前理解与依据

1. **来源已有设计：需要先于供给。** Learning OS 给出本课目标、学生起点、课程任务与预期证据；Tutor OS 回答谁能在何时完成真人交付；Service 和 Growth 分别承接客户接受、恢复与商业承诺。Tutor 不能吞并学生长期学习路径，也不能让销售承诺越过真实供给（[[TutorOS设计宪法全文]] §2—3）。
2. **现行有界理解：承诺以一节课为最小完整交付单元。** 它从源系统课次、学生、市场、时段、原约教师、课程类型与约课属性开始；取消、缺席、改期和代课也必须留在原承诺链上。Lesson Case 是设计工作定义，不等于已上线的新产品（同页 §3）。
3. **来源已有架构：需求与产能是跨责任域契约。** 4＋2＋3 草稿把市场需求、TOC 组合控制和本地供给承诺连接为 C1，要求写清预测窗口、数量、能力、课程、市场、时段、变更与失约升级；具体 owner、授权和接口仍待确认（[[TOC成立后-教师运营系统地图与责任清单]]「三份跨系统契约」）。
4. **本页综合建议：把“承诺可信度”作为本域的经营对象。** 可信度来自需求语义是否清楚、资格与时段是否当前有效、客户偏好是否被保存、异常时是否有有界替代，而不是来自名单规模或模型自信。

## 机制、条件与边界

有意义的关系是：**清楚的学习需要 + 当前可兑现的教师条件 → 可接受的交付承诺 → 实际课堂与后续结果回写 → 修正下一轮需要和供给。** 它只在任务版本、资格、时段、客户选择和源系统状态都可追溯时成立。若老师临时不可约、课程任务版本失配，或客户拒绝代课，原承诺必须保留为未兑现；不能用“后来有人上课”覆盖。

本域止于“答应交付什么”。教师从哪里来归 [[TutorOS经营域-D02-教师获取与准入]]，总体可兑现产能归 [[TutorOS经营域-D04-产能与供需配置]]，谁更适配归 D06/D07，课堂实际兑现归 D08/D09。XYZ 的稳定内核提醒我们：一个系统能接单只说明能力载体，客户是否真正得到所需学习交付才是判卷（[[X-Y-Z三轴经营模型]] §3—6）。

## 两种模式怎样分别回答

**HBT 是当前存量主流。** 承诺要把分散教师的真实开放时段、设备网络、资格、课程能力与时区放进同一次校验；“在线”“活跃”或开过 slot 都不自动等于该时段可交付。

**Center 已有供给、当前重点补建设。** 同一承诺还要核对教师是否到岗、席位与公共网络是否可用、现场支持是否覆盖，以及 Center 的固定排班能否与市场需求对应。座位存在、填充率高或经营者报出人数都不能替代具体课位。两种模式共享学生任务和承诺对象，不各造一套订单事实。

## 取舍与反证

关键取舍是“销售更快承诺”与“只承诺可兑现供给”。可以保留可逆预占、候选方案和人工预测，但必须有版本、释放、冲突防护和失败状态。若把所有不确定性都挡在门外，客户选择和新师机会会受损；若把候选当库存，则会制造失约。

足以改变当前理解的反例包括：同口径下，弱化课前任务并未降低学习结果却明显提升履约；Center 固定供给在控制课程与时段后仍没有提高承诺兑现；或客户选择经常改变，导致“原约教师”不再是有效承诺对象。此时应调整承诺颗粒度，而不是删掉未兑现事实。

## 最近一次认识变化

2026-09-14 的变化是把 N1 从一张需求入口，连接成独立经营域：它既不等于 Learning OS，也不等于供给预测。此次变化是意义层整理，不代表新接口、排课规则或业务结果已经发生。

## 证据与继续追问

下一份最有用证据是一组真实课次：从学习任务版本、客户偏好和原约教师，到资格/时段校验、实际交付、代课接受和最终结果，逐项回放成功、失约与未知。继续复用 [[新老师上岗后供给流水线与预测口径-待验证问题卡]] 的状态口径，不新增一套人审清单。

### 独立来源组

1. Tutor OS 宪法原件：[HTML](../../../sources/common-feed/J-ec8e516b745b355494be9b0b__37a045e8a9f5aec8.e0be7b3e7cdb.html)；正文入口 [[TutorOS设计宪法全文]]。
2. 4＋2＋3 责任地图原稿：`sources/外教战役/TOC成立后_教师运营系统地图与责任清单_草稿_v0.3.md`；正文入口 [[TOC成立后-教师运营系统地图与责任清单]]。
3. XYZ 正本 v1.0：`sources/外教战役/X-Y-Z三轴经营模型.md`；正文入口 [[X-Y-Z三轴经营模型]]。

<!-- meaning-cloud-navigation:start -->
## 钉钉阅读入口

| 页面 | A 知识库 | Leon 知识库 |
|---|---|---|
| TutorOS知识总图 | [A 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno?utm_scene=team_space) |
| TutorOS第二层经营地图 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v?utm_scene=team_space) |
| TutorOS设计宪法全文 | [A 库](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9Z7l0m1WyMoPYe1?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzR71nqQ8BQEx5rG?utm_scene=team_space) |
| TOC成立后-教师运营系统地图与责任清单 | [A 库](https://alidocs.dingtalk.com/i/nodes/P0MALyR8kl4DxXd2TD6LgE4aW3bzYmDO?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzLqEADgVgN7R35y?utm_scene=team_space) |
| TutorOS经营域-D02-教师获取与准入 | [A 库](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9ZKbGp6WyMoPYe1?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/4lgGw3P8vR2aBrGZSZjG1dEq85daZ90D?utm_scene=team_space) |
| TutorOS经营域-D04-产能与供需配置 | [A 库](https://alidocs.dingtalk.com/i/nodes/9bN7RYPWdM5q79o4HjQ3Ae0KVZd1wyK0?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrkQAl7MVxAZB1Gv?utm_scene=team_space) |
| X-Y-Z三轴经营模型 | [A 库](https://alidocs.dingtalk.com/i/nodes/0eMKjyp813zoLe7nSrk2nyeGVxAZB1Gv?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzLR0o9BVgN7R35y?utm_scene=team_space) |
| 新老师上岗后供给流水线与预测口径-待验证问题卡 | [A 库](https://alidocs.dingtalk.com/i/nodes/14dA3GK8gjBKbMrDiE5Mew1eJ9ekBD76?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/4lgGw3P8vR2aBrGZSZjeeQQd85daZ90D?utm_scene=team_space) |

<!-- meaning-cloud-navigation:end -->
