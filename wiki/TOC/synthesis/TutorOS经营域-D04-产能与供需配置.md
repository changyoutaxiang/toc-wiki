---
projection: public
type: synthesis
title: Tutor OS 经营域 D04｜产能与供需配置
tags: [TutorOS, 第二层经营域, 产能, 供需, 配置]
related: [TutorOS第二层经营地图, TutorOS知识总图, 新老师上岗后供给流水线与预测口径-待验证问题卡, 2026-07-28-CC预约体验课预占与供给数字漏斗化, TOC成立后-教师运营系统地图与责任清单]
created: 2026-09-14
updated: 2026-09-14
sources: ["外教战役/Meeting/J-8204290b290f6a0109b82ad3__8b2f098ca571426c.85acc06602c0__Battle-1-Weekly-Meeting-2026-09-02.md", "外教战役/Meeting/轻纪要-国内外教运营待决策-2026-07-28.md", "外教战役/TOC成立后_教师运营系统地图与责任清单_草稿_v0.3.md", "common-feed/J-ffe0292293c20cd84369f608__58475e9928597051.c5141293f4a4.json"]
review: 待审
review_scope: 第二层由Agent综合建设，具体主张按所引来源状态使用；未逐条经Leon认领
architecture_version: "1.1"
meaning_domain: D04
---

# 产能与供需配置

返回 [[TutorOS第二层经营地图]] / [[TutorOS知识总图]]。

> 当前最重要的理解：产能不是教师人数、上线人数或打开的 slots，而是某个市场、课程和时段真正可被约到、能履约并有质量边界的课位。

## 当前理解与依据

1. **现行有界判断：供给必须漏斗化。** [[新老师上岗后供给流水线与预测口径-待验证问题卡]] 指出 launch、ready、active、unblocked、eligible、shown、bookable、实际授课与稳定交付不能混为一个数；多个历史数字缺同窗底表，均不能当今天基线。
2. **待审会议方向：库存要可追踪、失败可回滚。** 2026-07-28 纪要提出唯一库存账、预占/释放、双占防护、异常明细与停机线，同时明确 700/730/1200/1500/2000 是不同层级的时点口述，不是一项目标（[[2026-07-28-CC预约体验课预占与供给数字漏斗化]]）。
3. **来源已有架构：产能单元是多维对象。** 4＋2＋3 草稿定义“教师×市场×课程/产品×时段×可用状态×质量/资格状态”，并要求 O1 在跨市场冲突中给出组合与升级；该架构页待审，具体 owner 和授权未落实（[[TOC成立后-教师运营系统地图与责任清单]] O1/C1）。
4. **本页综合建议：把缺口原因与补法分离。** 缺教师、缺合格资格、缺开放时段、被 block、曝光不可见、匹配受限、现场席位不足和需求突增，分别对应招募、成长、激活、规则修复、调度或需求保护，不能一律下成“继续招聘”。

## 机制、条件与边界

核心反馈关系是：**版本化需求 → 可兑现产能视图 → 承诺与配置 → 实际预约/履约/质量 → 预测误差与缺口原因回写。** 只有同一 Teacher ID、时间窗、课型、市场、资格和状态可追溯时才成立。看板显示有余量、支持侧却找不到代课教师的聊天异常说明：若 block、客户偏好或推荐可见性未进入同一集合，表面产能会误导决策；聊天里的具体数量没有截图和生产读回，不升级为事实。

D04 管组合和缺口，不管教师从哪里来（D02）、怎样成材（D03）、教学条件是否可靠（D05）或具体匹配排序（D06）。人工预测可以用，但要有 owner、版本、刷新频率和事后回算。

## 两种模式怎样分别回答

**HBT** 的容量分散在大量教师与时段中，易受临时关闭、设备网络、响应和跨市场共享影响。活跃一次或长期在库都不是高峰可约；要看持续开放、当前资格、实际占位与履约。

**Center** 可把教师、席位、网络和固定排班组成较稳定的产能块，也能覆盖代课与多时区；但席位填充不等于约课率，固定时段不自动带来关系或学习优势，公共故障可能同时消失一批产能。Center 与 HBT 应在同一需求语言中比较，不以模式标签替代质量。

## 取舍与反证

关键取舍是产能利用率与承诺韧性。把全部课位压满会提高表面效率，却可能没有代课、波峰和故障余量；过度留备则损害教师收入和平台经济。合理配置要显式标出正常供给、受控备用与不可用状态，并按客户损失和完整成本验证。

反证包括：增加 Launch 后高峰缺口不降；解 block 后履约或客户质量恶化；Center 高填充却低约课或高取消；跨市场调度改善一方却伤害另一方承诺；预测准确但靠压低需求或改变分母。出现这些信号，应回到漏斗层和约束，而非调整总人数叙事。

## 最近一次认识变化

2026-09-14 把 N2 中的“供给形成”进一步分出 D04：教师合格与产能可兑现是不同问题。这个连接使招聘、试用、匹配、收入能共同看到同一课位，但不证明统一供给表已经存在。

## 证据与继续追问

下一份最有用证据是一张同一高峰窗口的 `active → unblocked → eligible → shown → bookable → committed → delivered-quality-known` 漏斗，逐层列集合、分母、去重、模式、原因和 owner，并用下一日/周实际结果回算。继续复用现有问题卡，不新建平行预测口径。

### 独立来源组

1. 2026-09-02 Battle-1 周会：`sources/外教战役/Meeting/J-8204290b290f6a0109b82ad3__8b2f098ca571426c.85acc06602c0__Battle-1-Weekly-Meeting-2026-09-02.md`；问题入口 [[新老师上岗后供给流水线与预测口径-待验证问题卡]]。
2. 2026-07-28 国内运营会：`sources/外教战役/Meeting/轻纪要-国内外教运营待决策-2026-07-28.md`；正文入口 [[2026-07-28-CC预约体验课预占与供给数字漏斗化]]。
3. 4＋2＋3 责任地图原稿：`sources/外教战役/TOC成立后_教师运营系统地图与责任清单_草稿_v0.3.md`；正文入口 [[TOC成立后-教师运营系统地图与责任清单]]。
4. 2026-09-08 产能/代课异常聊天：[JSON](../../../sources/common-feed/J-ffe0292293c20cd84369f608__58475e9928597051.c5141293f4a4.json)；数字保持待核。

<!-- meaning-cloud-navigation:start -->
## 钉钉阅读入口

| 页面 | A 知识库 | Leon 知识库 |
|---|---|---|
| TutorOS知识总图 | [A 库](https://alidocs.dingtalk.com/i/nodes/vNG4YZ7JnPDjwzGdsARRx9OnW2LD0oRE?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/GZLxjv9VGqKl0mPvHZooPyla86EDybno?utm_scene=team_space) |
| TutorOS第二层经营地图 | [A 库](https://alidocs.dingtalk.com/i/nodes/np9zOoBVBYq1apP5IerEveo3W1DK0g6l?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/G53mjyd80p2oeG7PcejQRwD686zbX04v?utm_scene=team_space) |
| 新老师上岗后供给流水线与预测口径-待验证问题卡 | [A 库](https://alidocs.dingtalk.com/i/nodes/14dA3GK8gjBKbMrDiE5Mew1eJ9ekBD76?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/4lgGw3P8vR2aBrGZSZjeeQQd85daZ90D?utm_scene=team_space) |
| 2026-07-28-CC预约体验课预占与供给数字漏斗化 | [A 库](https://alidocs.dingtalk.com/i/nodes/NDoBb60VLQglxbKeHazlQEPyJlemrZQ3?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/R4GpnMqJzGmRBx4dSL5nlMkn8Ke0xjE3?utm_scene=team_space) |
| TOC成立后-教师运营系统地图与责任清单 | [A 库](https://alidocs.dingtalk.com/i/nodes/P0MALyR8kl4DxXd2TD6LgE4aW3bzYmDO?utm_scene=team_space) | [Leon 库](https://alidocs.dingtalk.com/i/nodes/pGBa2Lm8aGOqaKwrSzLqEADgVgN7R35y?utm_scene=team_space) |

<!-- meaning-cloud-navigation:end -->
