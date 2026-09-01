# 上海中考信息

上海中考录取分数线查询站与历年数据整理，共 16 个区的录取信息页面 + 数据 CSV。

## 内容结构

| 类别 | 文件 | 说明 |
|---|---|---|
| 主站 | `index.html` | 总览导航 |
| 分数线查询 | `query.html` | 录取分数线查询工具 |
| 各区页面 | `pudong.html` / `putong.html` / `huangpu.html` …（16 区） | 各区录取详情 |
| 数据文件 | `csv/*.csv` | 民办降分、名额分配、五年制等数据 |
| 官方信息 | `official-info.txt` | 官方发布的信息汇总 |
| 数据 JSON | `data/1-15-data.json` | 查询站数据源 |

## 技术说明

- 纯 HTML + CSS + JS，无外部依赖，离线可用
- 数据以 CSV / JSON 维护，页面读取渲染
- 内容基于官方公开信息整理

> 由本地 git 仓库通过 GitHub API 重建推送。
