---
type: project
title: 老师 APP 重启
tags: [battle, infra, comms, app, archive-candidate]
related: [WhatsApp建设, Q2关键决策与判断]
created: 2026-08-30
updated: 2026-09-11
sources: ["外教战役/老师APP重启.md"]
review: 待审
---

# 老师 APP 重启
> **归档候选 2026-09-11（Leon 批）**：draft/薄内容，待后续物理归档；本轮不搬家。


> [!warning] 待审
> 本页编译自《老师APP重启.md》（decision_state draft、updated_at 2026-05-15、human_loop leon）。
> 项目档案待拆解，内容未经 Leon 审定，**不得当作正式结论引用**。

## 当前判断（截至 2026-05-14）

「老师 APP 重启」是「沟通阵地」基建下挂的两条子项目之一（与 [WhatsApp建设](WhatsApp%E5%BB%BA%E8%AE%BE.md) 并列）。

- **2026-05-07 定位明确**：老师 APP 应该是**体制内主阵地**，负责高频提醒、标准传达、异常跟进和蜜月期课程的主触达。
- **2026-05-14 工程边界补充**（APIs/Cocos 技术需求会）：APP 可考虑外包或 AI 工程师临时承接，但因涉及教师敏感数据和 API 权限，必须经过权限隔离、代码 review、上线审计和长期维护 owner 设计。

## 状态卡片

- owner: Tammi；priority p1；decision_state draft。
- blockers：App 主阵地功能分层仍待落地；内部专职开发资源不足；外包/AI 工程师承接后的长期维护 owner、API 权限隔离、安全审批、代码 review 和上线审计流程未定。
- next step：拍实开发资源路径、安全审计流程和长期维护 owner，再进入外包/AI 工程师任务拆解。

## 项目定义

- 外教在岗触达的体制内主阵地。
- 承接平台标准、考核口径和质量反馈的稳定传达。
- 负责蜜月期课程的高频提醒与异常介入入口。

## 当前共识

- App 主阵地应承担最多、最稳定的日常触达；WhatsApp 适合作为高触达辅助阵地，不应和 App 混成双主阵地。
- 课前提醒、课中异常、课后反馈、正向表扬，都应优先在 App 内形成闭环。
- Teacher APP 涉及敏感教师数据，接口设计必须避免「通过一个号拉取号内所有老师数据」的权限漏洞。
- 外包成本约 8000 元/月/人，可作为短期补位，但外包人员离场后的代码维护、风格统一和安全责任不能悬空。

## 下一步

- 先把 App 的消息、语音、异常提醒和表扬流设计清楚。
- 与 CRM / 触达系统打通蜜月期标签。
- 明确与 WhatsApp / SMS 的分层边界，避免操作链过长。

## Timeline

- 2026-05-07：新讨论把老师 APP 明确为体制内主阵地，并把蜜月期课程的主触达窗口放到这里。
- 2026-05-14：APIs/Cocos 技术需求会确认 Teacher APP 可考虑外包加速，但 API 安全、教师敏感数据、代码 review、上线审计和长期维护 owner 是先决条件。

## 相关页面

- 项目：[WhatsApp建设](WhatsApp%E5%BB%BA%E8%AE%BE.md)（沟通阵地另一子项目，高触达辅助阵地）
- 决策：[Q2关键决策与判断](../decisions/Q2%E5%85%B3%E9%94%AE%E5%86%B3%E7%AD%96%E4%B8%8E%E5%88%A4%E6%96%AD.md)（Teacher APP 开发资源路径、安全审批、接口权限和维护 owner 为待决策项等时点判断）
- 项目：[沟通矩阵建设](%E6%B2%9F%E9%80%9A%E7%9F%A9%E9%98%B5%E5%BB%BA%E8%AE%BE.md)（本项目与 WhatsApp 建设的上级基建）

<!-- meaning-cloud-navigation:start -->
## 钉钉阅读入口

钉钉阅读时，用下表进入相关知识；原始依据按各自权限读取。

| 页面 | A 知识库 | Leon 知识库 |
|---|---|---|
| WhatsApp建设 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerMzPZpW1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/7QG4Yx2JpLMrqaGdcqApdY3RJ9dEq3XD?utm_scene=team_space) |
| Q2关键决策与判断 | [A 库](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzoARdxvVgN7R35y?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/1R7q3QmWeerQRDdvt6dKeGRvWxkXOEP2?utm_scene=team_space) |
| 沟通矩阵建设 | [A 库](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazlej3eJlemrZQ3?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/mweZ92PV6M7l9QrqHq2RBEGkWxEKBD6p?utm_scene=team_space) |
| TutorOS知识总图 | [A 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno?utm_scene=team_space) |
| TutorOS第二层经营地图 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v?utm_scene=team_space) |

<!-- meaning-cloud-navigation:end -->
