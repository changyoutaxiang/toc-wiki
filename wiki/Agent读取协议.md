---
projection: public
type: overview
title: Agent 读取协议
review: 记录
updated: 2026-09-17
---

# TOC LLM Wiki · Agent 读取协议

> 本文件是本知识库各只读出口（两个钉钉空间、私有 GitHub）的固定读法入口，面向被授权访问的 Agent。
> 正本在 Leon 本地的独立 TOC LLMwiki 目录；读取不构成维护或执行授权。
> 引用规则一律用「文件 + 节标题」，不用行号。

## 一、读法（truth resolution）

1. 从 `wiki/TutorOS知识骨架落点索引.md` 按经营问题定位相关域页（D01–D15）。
2. 现行结论优先读：`wiki/骨架/TutorOS知识总图.md` → 域页 → 页内证据条目（`[E..]` / `[C..]` 编号）。
3. frontmatter 的 `supersedes` / `superseded_by` 成对标记新旧链；被 supersede 的页面只用于解释演化，不作为 current truth。
4. 每条结论应能追溯到 source；source 不在当前出口内时按「三、本地依赖」降置信度。
5. 不知道就回答不知道；不存在的证据不补造。
6. 钉钉出口的页面名链接不一定可点，用紧邻的 A / Leon 节点链接进入；GitHub 出口页面名链接可直接用。
7. GitHub 出口另提供机器索引 `agent/pages.jsonl`（每页一行的 id/type/review/answers/supersedes/source_availability/content_hash，含 `agent/manifest.json` 字段语义与 `agent/sources.jsonl` 源清单）；索引从正本派生、随发布再生成，用于低成本定位与确定性路由，冲突时仍以页面正文本为准。
8. 问“尚未弄清什么、为什么、什么证据会改判”时，读域页 `FRONTIER` 的 Q、`BELIEFS` 的 H、最新 DELTA 与相邻域。机器索引中的 `open_questions`、`active_hypotheses` 是待探索导航，不属于 `answers`；不得将它们表述为已证实答案。`_ops` 中未获人审的骨架改稿候选不属只读出口的现行内容。

## 二、审态语义（双层，避免误读状态冲突）

- frontmatter `review` 是页级权威字段。`已审` = 蒸馏忠实性认可（2026-09-15 批量认可语义），不等于逐条人审、业务拍板或已生效；`记录` = 留痕汇编；`待审` = 蒸馏忠实性未认可。
- 正文中的「待审」多数是**内容级或源级边界**（源为 draft、数值未冻结、提案未批准），与页级字段不构成冲突。
- 2026-09-15 批量认可翻转页级字段后，个别页面正文仍残留旧自述；**以 frontmatter 为准**。若正文自述与字段直接矛盾，按「内容待审」处理并如实返回 conflict，不自行择一。

## 三、本地依赖与置信度

- 标「本地资料，钉钉／GitHub未提供」的链接指向不在出口内的本地文件：可用性受限，据此得出的结论置信度降档，不得当作已验证证据。
- GitHub 出口的 `sources/raw/`（218 份精选原料）与 `sources/外教战役/`（历史 277 份）可直接读；钉钉出口的原料在两空间的原料目录节点下。
- 断链或指向不存在文件的引用 = 证据缺口，如实报告，不推断内容。

## 四、边界

- 各出口均为只读投影：读取不获得维护、写入、发布或执行授权。
- 已纠正的历史说法不能复活；未决问题不自动裁决。
- 查询只返回答案 + 依据 + 适用边界。

## 五、发布质量门禁

- GitHub 出口发布前运行一致性 lint：断链、未标注本地依赖、假「未提供」标注、supersedes 双向一致、必填 frontmatter、页级审态矛盾（棘轮）。
- lint 报告存正本库 `_ops/export-lint-report.json`，出口不携带；有 FAIL 即阻止发布。
