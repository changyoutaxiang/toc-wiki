---
type: decision
title: 新师培训双轨认证与 Full Monitor 考评上线（book time 新版细节）
tags: [新师培训营, Full-Monitor, 双轨认证, 分项制考评, AI-Bot首课, AC客户端]
related: [2026-07-13-战役一二重构与3500唯一基准, 2026-07-15-老师端成长工具与后台四Agent架构, 2026-07-17-新师30天出营积分决策, 2026-07-24-外教质量提升双周会-蜂巢首闭环与Jack六项要求, 2026-07-14-Cocos模板族培训与实操准入, 2026-08-18-TIDE灰度发布与范围收缩, 新师训战营-TIDE语义岛-2026-09-11]
created: 2026-08-31
updated: 2026-09-11
sources: ["外教战役/Meeting/轻纪要-book time：外教战役 新版 细节讨论-2026-07-14.md"]
review: 记录
date: 2026-07-14
decided_by: 会议（王东主持；袁慧茹 Katherine、窦欣彤、翟雨佳 Wilson、曹海璇 Shayne、曲建菲、Tina、Anna、Sophia 等）
status: 生效
supersedes: []
superseded_by: []
---

# 新师培训双轨认证与 Full Monitor 考评上线（book time 新版细节）

> 2026-07-14 外教战役新版细节专项会（实施方案细节对齐）。参与：Wang Dong (wangdong)、Yuan Huiru Katherine、Dou Xintong (Jenny)、Zhai Yujia Wilson、Jennifer、Cao Haixuan (Shayne)、Qu Jianfei、Tina、Anna、Sophia。
> 接续线：战役一新教师培训营落地推进（[2026-07-13-战役一二重构与3500唯一基准](2026-07-13-%E6%88%98%E5%BD%B9%E4%B8%80%E4%BA%8C%E9%87%8D%E6%9E%84%E4%B8%8E3500%E5%94%AF%E4%B8%80%E5%9F%BA%E5%87%86.md) 临时培训营 2,000 首试）；本会给出培训达标、考评、Full Monitor 上线与首课保护的实施细节。`review: 记录`——会议共识，拍板人归属按语义还原待复核。

## 背景

- 6,000 名教师完成视频学习，但无实操记录；仅 3,700 人满足设备要求（AC 版本 + CPU），可被打标。
- 静默升级仅覆盖约 3,000 人，约半数因未关闭并重登 AC 而失败；后续版本引入 GPU 检测，进一步限制兼容性。
- AC 客户端 5.0.38 仍有降噪（Noise Cancellation）bug，影响学生听课体验、损伤系统信誉。

## 决策内容

### 一、双轨认证标准（理想标准 = Practice Room 实操）

- **理想标准**：Practice Room 完成六类核心课型实操（类比「考完驾照再上路」），从今日起统一口径，**完成实操才算培训达标**。
- **备用标准**：特殊情况下允许未完成实操的教师应急上课，但**不作为产品承诺对外宣传**；已历史打标者需手动补做实操。
- 推进节奏：优先推动 3,700 名合格教师完成 Practice Room 实操（预计转化率 50%）；优先沟通境外越南学校的 2,000 名教师。

### 二、新教师考评采分项制而非总分制

- 五维考核指标：可靠性（出勤/迟到/早退）、满意度（点赞/差评/封禁等用户反馈）、质量（摄像头/灯光/音效）归**客户价值（权重 80%）**；产能（开课数量与时段合规）、纪律（睡觉/打盹等行为）归**公司价值（权重 20%）**。
- **任一核心维度极差（如全勤缺席）直接 Fail**，其他高分无法抵消——不设总分，防止高分项掩盖核心问题。
- 从 0 分起累积，每节课表现计入，持续合规即可毕业，激励持续改进；纪律问题与硬件/环境问题明确区分、分开处理。

### 三、Full Monitor 系统架构锁定，8 月 1 日正式上线

> **📌 时间表漂移旁注（2026-09-11）**：本会「**8 月 1 日正式上线全量新教师**」为当时计划表述，**不作现行上线证明**。后续演进见问题账 [问题账](../%E9%97%AE%E9%A2%98%E8%B4%A6.md) **TOC-32**（海外 AB → 灰测后全量 → 小范围灰测）及 [2026-08-18-TIDE灰度发布与范围收缩](2026-08-18-TIDE%E7%81%B0%E5%BA%A6%E5%8F%91%E5%B8%83%E4%B8%8E%E8%8C%83%E5%9B%B4%E6%94%B6%E7%BC%A9.md)（禁止全量、先约 50 名灰度）。运行状态以证据边界为准。

- 四模块：**数据底座**（自动读取每位教师每节课数据）／**服务分值引擎**（生成诊断报告）／**任务触发中心**（触发通知与干预任务）／**TIT 统一界面**（Agent 全程操作，减少人工干预）。
- **首批覆盖 2,000 名新教师**；数据准备为当前关键路径，**三天内完成一期字段就绪**；本周内完成历史数据模拟、建立 Baseline；本周五（7/18）前输出教师端 HTML 轻量 Web App（WiFi 部署）支持任务中心触达；**8 月 1 日正式上线全量新教师**，一个月后评估毕业人数与 Top 教师占比、启动 A/B 验证。
- Mentor 角色调整：保留情感支持功能，不再主导成长路径；系统实现基于规则的闭环管理。

### 四、首课保护机制：AI Bot 学生试讲

- 放弃空班、录播回放、假学生方案（体验尴尬且无法真实检验教学能力）；采用 **AI Bot 学生**进行首课试讲，验证准时履约，同时保护真实学生体验。

### 五、流量分配策略

- 新教师仅匹配 Cocos Level 0-2 课程，禁止分配雅思或商务英语；初期优先匹配宽容度高的老学生（上课经历 200-500 节）降低退费风险；多次缺席触发自动治理，严重违规者停止推课。

### 六、待决策项（未拍，需蔡玲对齐后确认）

- 在 AC 5.0 稳定版就绪前提下执行**强制升级**，即使部分教师暂时无法登录；
- **全局关闭 AI 降噪，回退 Crisp 软件方案**；
- 缺失数据：10 万日均课次中使用 AI 降噪的占比 + 关闭后投诉风险——需尽快收集。

## 依据

- 实操缺口事实（6,000 视频学习 vs 3,700 设备达标）与 AC 客户端故障事实（5.0.38 降噪 bug、静默升级半数失败）。
- 分项制一票否决的动机：多维度总分制会系统性掩盖核心问题（如全勤缺席）。
- 首课保护核心矛盾：验证教师能力 vs 保护真实学生体验——AI Bot 是当前可接受的折中，Bot 仿真度决定检验质量，后续需关注。

## 影响范围

- 战役一实施层：7/13「临时培训营 2,000」（[2026-07-13-战役一二重构与3500唯一基准](2026-07-13-%E6%88%98%E5%BD%B9%E4%B8%80%E4%BA%8C%E9%87%8D%E6%9E%84%E4%B8%8E3500%E5%94%AF%E4%B8%80%E5%9F%BA%E5%87%86.md)）的培训达标与系统上线口径；与 07-15「全量 AI QA 监控是硬前置」（[2026-07-15-老师端成长工具与后台四Agent架构](2026-07-15-%E8%80%81%E5%B8%88%E7%AB%AF%E6%88%90%E9%95%BF%E5%B7%A5%E5%85%B7%E4%B8%8E%E5%90%8E%E5%8F%B0%E5%9B%9BAgent%E6%9E%B6%E6%9E%84.md)）同链。
- 考评制度演化：分项制设计在 07-17 被双轨制积分取代（[2026-07-17-新师30天出营积分决策](2026-07-17-%E6%96%B0%E5%B8%8830%E5%A4%A9%E5%87%BA%E8%90%A5%E7%A7%AF%E5%88%86%E5%86%B3%E7%AD%96.md)），其「底线不达标不能靠加分补回」语义延续至 07-24 双周会五维框架（[2026-07-24-外教质量提升双周会-蜂巢首闭环与Jack六项要求](2026-07-24-%E5%A4%96%E6%95%99%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E5%8F%8C%E5%91%A8%E4%BC%9A-%E8%9C%82%E5%B7%A2%E9%A6%96%E9%97%AD%E7%8E%AF%E4%B8%8EJack%E5%85%AD%E9%A1%B9%E8%A6%81%E6%B1%82.md)）。
- 实操准入与 Cocos 培训实操考核（[2026-07-14-Cocos模板族培训与实操准入](2026-07-14-Cocos%E6%A8%A1%E6%9D%BF%E6%97%8F%E5%9F%B9%E8%AE%AD%E4%B8%8E%E5%AE%9E%E6%93%8D%E5%87%86%E5%85%A5.md)）为相邻机制，练习室与 Practice Room 是否同一口径待核对（见报告待拍项）。

## 演化记录

- 2026-07-14：本页拍板（双轨认证 / 分项制考评 / Full Monitor 8-1 上线 / AI Bot 首课；AC 降噪与强制升级列为待决策项）。
- 2026-07-17：分项制考评设计被双轨制积分（基础 40 + 课程分无封顶、100 分毕业）调整（[2026-07-17-新师30天出营积分决策](2026-07-17-%E6%96%B0%E5%B8%8830%E5%A4%A9%E5%87%BA%E8%90%A5%E7%A7%AF%E5%88%86%E5%86%B3%E7%AD%96.md)）——本页其余条款保持生效。
- 2026-07-24：双周会「底线问题 = 准入/熔断条件，不能靠加分补回」（[2026-07-24-外教质量提升双周会-蜂巢首闭环与Jack六项要求](2026-07-24-%E5%A4%96%E6%95%99%E8%B4%A8%E9%87%8F%E6%8F%90%E5%8D%87%E5%8F%8C%E5%91%A8%E4%BC%9A-%E8%9C%82%E5%B7%A2%E9%A6%96%E9%97%AD%E7%8E%AF%E4%B8%8EJack%E5%85%AD%E9%A1%B9%E8%A6%81%E6%B1%82.md) §二）承接本页一票否决语义；AC 降噪信息差登记问题账 TOC-42（工程待办）。

<!-- meaning-cloud-navigation:start -->
## 钉钉阅读入口

钉钉阅读时，用下表进入相关知识；原始依据按各自权限读取。

| 页面 | A 知识库 | Leon 知识库 |
|---|---|---|
| 2026-07-13-战役一二重构与3500唯一基准 | [A 库](https://alidocs.dingtalk.com/i/nodes/DnRL6jAJMGMqOY4eS9Zb6649WyMoPYe1?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/bva6QBXJwazmBYGpILqpY0yNWn4qY5Pr?utm_scene=team_space) |
| 2026-08-18-TIDE灰度发布与范围收缩 | [A 库](https://alidocs.dingtalk.com/i/nodes/pYLaezmVNejqr3vQtKaYpd7vWrMqPxX6?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/X6GRezwJlAvgOpGkS0qjgRy38dqbropQ?utm_scene=team_space) |
| 2026-07-15-老师端成长工具与后台四Agent架构 | [A 库](https://alidocs.dingtalk.com/i/nodes/ndMj49yWjXK9ykGpubzjz9jbJ3pmz5aA?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/X6GRezwJlAvgOpGkS0qj4wE58dqbropQ?utm_scene=team_space) |
| 2026-07-17-新师30天出营积分决策 | [A 库](https://alidocs.dingtalk.com/i/nodes/1DKw2zgV2Proed71svNkBKjy8B5r9YAn?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/9E05BDRVQ2XlqOgYuP6Zr7AgJ63zgkYA?utm_scene=team_space) |
| 2026-07-24-外教质量提升双周会-蜂巢首闭环与Jack六项要求 | [A 库](https://alidocs.dingtalk.com/i/nodes/9bN7RYPWdM5q79o4HjQ5Ggk7VZd1wyK0?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsA5opzn5W2LD0oRE?utm_scene=team_space) |
| 2026-07-14-Cocos模板族培训与实操准入 | [A 库](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazljpn9JlemrZQ3?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/gpG2NdyVX3n6ME2dS7g5pLOjWMwvDqPk?utm_scene=team_space) |
| TutorOS知识总图 | [A 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno?utm_scene=team_space) |
| TutorOS第二层经营地图 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v?utm_scene=team_space) |

<!-- meaning-cloud-navigation:end -->
