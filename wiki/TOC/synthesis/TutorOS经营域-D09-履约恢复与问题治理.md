---
projection: public
type: synthesis
title: TutorOS经营域-D09-履约恢复与问题治理
tags: [TutorOS, 第二层经营域, 履约恢复, 坏课治理, 异常恢复, 问题治理]
related: [TutorOS知识总图, TutorOS骨架节点与证据导航, 坏课KPI-坏课治理语义岛-2026-09-11, 2026-08-26-坏课治理双方案灰度拍板, 2026-08-27-课堂问题数据口径与课后治理优先]
created: 2026-09-14
updated: 2026-09-14
sources: ["common-feed/J-ec8e516b745b355494be9b0b__37a045e8a9f5aec8.e0be7b3e7cdb.html", "外教战役/Meeting/2026-08-26_Bad-Class-Issue-Updates纪要.md", "外教战役/Meeting/2026-08-27_聊下网络设备治理纪要.md"]
review: 待审
review_scope: 第二层由Agent综合建设，具体主张按所引来源状态使用；未逐条经Leon认领
architecture_version: "1.1"
meaning_domain: D09
---

# TutorOS经营域-D09-履约恢复与问题治理

返回 [[TutorOS第二层经营地图]] / [[TutorOS知识总图]]。当前最重要理解：恢复不是把客户安抚完就结束，也不是补位成功后抹掉原承诺失约；客户恢复、教师/中心根因、平台履约和后续复发必须分开结案。

## 当前理解与依据

第一，宪法要求 Lesson Delivery Case 从承诺开始记录，即使没有上成的课也要建档；原约与实际教师都保留，同一承诺下可关联多个执行尝试，补位成功不等于原师履约（[[TutorOS设计宪法全文]] §3、§5、§10、§17）。

第二，坏课语义岛把治理地图分清：坏课 KPI 设计稿是口径候选，8/26 是治理决策正本，8/27 是稳定类数据口径，8/31 是 Q3/Q4 方向候选；设计稿、会议倾向和周报口述都不能当成已挂正式 KPI（[[坏课KPI-坏课治理语义岛-2026-09-11]]）。

第三，8/26 已审治理决策给出双方案灰度：2 小时紧急约课、新师前 10 课等高风险场景先用小范围灰度和 DRI 授权推进，强调 go but set control，有证据出现立即调整（[[2026-08-26-坏课治理双方案灰度拍板]]）。

第四，8/27 数据口径说明课后治理优先于课中实时提示，因为课中链路延迟、归因不确定、误判可能干扰教学；归因只能作为建议，不能作为硬性结论下发教师（[[2026-08-27-课堂问题数据口径与课后治理优先]]）。

## 机制、条件与边界

本域的机制是“异常事实 → 客户保护 → 根因处理 → 后续验证 → 复发预防”。异常事实包括缺席、迟到、早退、断线、看不见/听不见、教材未加载、频繁进出、设备异常等；客户保护由 Service 承接接受代课、沟通、权益恢复；Tutor 负责教师侧事实、支持、治理和复检；Center 公共故障要聚合处理。

不成立的情况是把多个状态混成一个关闭：客户收到回复，不等于根因消除；菲律宾整改完成，不等于市场损失停止；老师确认出席，不等于长期不会缺席；课后治理上线，不等于坏课 KPI 全盒子上线。

## 两种模式怎样分别回答

HBT 的恢复重点在远程触达、请假线上化、AC/App/IM 通道、设备网络自查、紧急约课开关和教师反馈。分散环境下，系统要尽快知道老师是否能上课、是否需要兜底，同时不能把平台分配、短时预约或设备误判都归给老师。

Center 的恢复重点在公共现场：同一中心多课同时断线、设备或噪音问题，应建立共享事件，关联所有受影响课堂，中心负责人处理现场工单，后续验证稳定性。Center 的风险是现场管理看似有 owner，但客户恢复、教师反馈和中心整改各自结案，容易互相冒充完成。

## 取舍与反证

关键取舍是课中干预与课后治理。课中提醒能更快保护客户，但误判和延迟会打断教学；课后治理更稳，但若高频问题教师持续伤害后续学生，就必须重新评估实时触达或排课限制。灰度要保护产能，尤其 Q4 或高峰期，不能让紧急约课开关导致可预约产能突然坍塌。

反证信号包括：补位成功后原承诺异常消失；工单关闭率上升但同因复发；口述数据被当正式基线；确认出席率提升但后续缺席没下降；设备异常一半回放正常还直接处罚；Center 公共故障被拆成个人坏课。

## 最近一次认识变化

2026-09-14 的意义层变化，是把坏课治理从“降低一个坏课率”扩成履约恢复与问题治理域。它承接 D08 的证据判断，但更强调行动状态：谁恢复客户、谁处理根因、谁验证不复发。

## 证据与继续追问

下一份证据应是 10 个异常 case 的状态链：原承诺、实际尝试、客户是否接受代课、恢复动作、教师/中心根因、工单回执、后续课堂验证和复发情况，且 HBT/Center 分开。

## 来源组与真实 wiki 链接


- 组1｜9月 Tutor OS 战略设计组：[[TutorOS设计宪法全文]]
- 组2｜8/26 灰度治理决策组：[[2026-08-26-坏课治理双方案灰度拍板]]
- 组3｜8/27 课堂问题数据口径组：[[2026-08-27-课堂问题数据口径与课后治理优先]]

[[坏课KPI-坏课治理语义岛-2026-09-11]]提供权威阅读顺序与状态核对，是上述来源的导航，不另计独立业务证据。

<!-- meaning-cloud-navigation:start -->
## 钉钉阅读入口

| 页面 | A 知识库 | Leon 知识库 |
|---|---|---|
| TutorOS知识总图 | [A 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno?utm_scene=team_space) |
| TutorOS第二层经营地图 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v?utm_scene=team_space) |
| TutorOS设计宪法全文 | [A 库](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9Z7l0m1WyMoPYe1?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzR71nqQ8BQEx5rG?utm_scene=team_space) |
| 坏课KPI-坏课治理语义岛-2026-09-11 | [A 库](https://alidocs.dingtalk.com/i/nodes/1OQX0akWmxrMP2G1sjEB0wQx8GlDd3mE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazGQZXXJlemrZQ3?utm_scene=team_space) |
| 2026-08-26-坏课治理双方案灰度拍板 | [A 库](https://alidocs.dingtalk.com/i/nodes/X6GRezwJlAvgOpGkS05doga98dqbropQ?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/1zknDm0WRapqKPMxIzkLEwX38BQEx5rG?utm_scene=team_space) |
| 2026-08-27-课堂问题数据口径与课后治理优先 | [A 库](https://alidocs.dingtalk.com/i/nodes/wva2dxOW4Yml41o0IYa2D3BAVbkz3BRL?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/QPGYqjpJYr7qjAzGiKr0Gqq58akx1Z5N?utm_scene=team_space) |

<!-- meaning-cloud-navigation:end -->
