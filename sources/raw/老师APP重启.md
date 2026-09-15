---
type: initiative
title: 老师 APP 重启
status: active
priority: p1
owner: Tammi
blockers: ["内部专职开发资源不足", "外包/AI工程师承接后的长期维护 owner 未定", "教师敏感数据 API 权限、安全审批、代码 review 和上线审计流程未定"]
next_step: "在老师 APP 主阵地定位之外，先拍实开发资源路径、API 权限隔离、代码 review、上线审计和长期维护 owner；外包只能在安全流程内按任务交付，不能直接绕流程上线"
next_review_at: 2026-05-06
serves_lever: infra.comms-matrix
last_signal_at: 2026-05-14
decision_state: draft
human_loop: leon
workstream: 沟通阵地
tags: [battle, infra, comms, app]
updated_at: 2026-05-15
source_count: 2
confidence: medium
multica_project_id: 2403312e-c723-4832-acd6-cfc9a6be4363
multica_issue_id: 5e24a144-5943-4518-accc-8352d981b407
multica_issue_number: PM-37
---

# 当前判断

「老师 APP 重启」是「沟通阵地」基建下挂的两条子项目之一，与「WhatsApp 建设」并列。

> 项目档案待拆解。Leon 在未来 1-2 天内会从业务角度补齐：背景判断、关键抓手、blockers、milestones、owner 链路，以及与 WhatsApp 主阵地的分工边界。  
> 2026-05-07 的新讨论进一步明确：老师 APP 应该是体制内主阵地，负责高频提醒、标准传达、异常跟进和蜜月期课程的主触达。
> 2026-05-14 APIs/Cocos 技术需求会补充了工程边界：APP 可考虑外包或 AI 工程师临时承接，但因涉及教师敏感数据和 API 权限，必须经过权限隔离、代码 review、上线审计和长期维护 owner 设计。

## 状态卡片

- owner: Tammi
- status: active
- priority: p1
- decision_state: draft
- blockers: App 主阵地功能分层仍待落地；内部专职开发资源不足；外包/AI工程师承接后的长期维护 owner、API 权限隔离、安全审批、代码 review 和上线审计流程未定
- next step: 拍实开发资源路径、安全审计流程和长期维护 owner，再进入外包/AI工程师任务拆解
- next review: 2026-05-18
- last signal: 2026-05-14
- human loop: leon

## 项目定义

- 外教在岗触达的体制内主阵地
- 承接平台标准、考核口径和质量反馈的稳定传达
- 负责蜜月期课程的高频提醒与异常介入入口

## 当前共识

- App 主阵地应承担最多、最稳定的日常触达
- WhatsApp 适合作为高触达辅助阵地，不应和 App 混成双主阵地
- 课前提醒、课中异常、课后反馈、正向表扬，都应优先在 App 内形成闭环
- Teacher APP 涉及敏感教师数据，接口设计必须避免“通过一个号拉取号内所有老师数据”的权限漏洞
- 外包成本约 8000 元/月/人，可作为短期补位，但外包人员离场后的代码维护、风格统一和安全责任不能悬空

## 下一步

- 先把 App 的消息、语音、异常提醒和表扬流设计清楚
- 与 CRM / 触达系统打通蜜月期标签
- 明确与 WhatsApp / SMS 的分层边界，避免操作链过长

## Timeline

- 2026-05-07: 新讨论把老师 APP 明确为体制内主阵地，并把蜜月期课程的主触达窗口放到这里。
- 2026-05-14: APIs/Cocos 技术需求会确认 Teacher APP 可考虑外包加速，但 API 安全、教师敏感数据、代码 review、上线审计和长期维护 owner 是先决条件。

---

# Sources

- [2026-05-07-与Tammi王慧沟通矩阵建设会.md](../meetings/2026-05-07-%E4%B8%8ETammi%E7%8E%8B%E6%85%A7%E6%B2%9F%E9%80%9A%E7%9F%A9%E9%98%B5%E5%BB%BA%E8%AE%BE%E4%BC%9A.md)
- [2026-05-14-APIs-and-Cocos技术需求会.md](<2026-05-14-APIs-and-Cocos-Technical-requirements.md>)
