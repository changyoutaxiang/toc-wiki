# toc-wiki

只读编译层 + raw。口径 **v1**。

## 用途

舰队问答知识库（TOC / 外教战役）。供 Agent 与人工检索，不作为可写工作区。

## 内容结构

```
README.md
wiki/TOC/           # 编译层（概念 / 决策 / 综合等）
sources/外教战役/   # raw 源材料
```

## 规则

- **不可改 `sources/`**：sources 为只读 raw；变更应回写正本后再重新导出同步。
- 本仓不含 common-feed 全量，仅 TOC 相关切片。
- 同步到 box 路径：`/home/box/knowledge/toc-wiki`

## 来源

自「极简 LLMwiki」只读导出（rsync，排除 `.DS_Store` / `.git` / `.obsidian` 等）。
正本勿在本仓修改。
