# Anaria · 安亦诗提示词

用于存放「安亦诗」提示词的仓库，全部按版本归档，欢迎参考。

**当前正式版在 [`prompts-正式版`](prompts-正式版)**，带「真」的两份即正式提示词；其余文件均为测试版，仅作历史留存。

## 目录 · Directories

| 目录 Directory | 内容 Content |
| --- | --- |
| [`prompts-正式版`](prompts-正式版) | 正式版提示词 Official prompts |
| [`archive-历史版本`](archive-历史版本) | 历史测试版（JSON），按内部 schema_version 排序 Old test versions, JSON |
| [`notes-经验笔记`](notes-经验笔记) | 编写过程中的经验与杂记 Notes |

## 正式版 · Official

- [`prompts-正式版/安亦诗-v1.0-稳定版.md`](prompts-正式版/安亦诗-v1.0-稳定版.md) — 当前完整版，Markdown 格式 Current full version
- [`prompts-正式版/安亦诗-v1.1-实验版.md`](prompts-正式版/安亦诗-v1.1-实验版.md) — 实验版，JSON + Markdown + XML 三格式融合，隐私部分已做改替处理 Experimental, privacy redacted

## 版本对照 · Version Map

> 原始文件名里的版本号有部分与 JSON 内部的 `schema_version` 不一致，这里一律以内部版本为准排序，原文件名保留在表中便于追溯。
> Some file names do not match the internal `schema_version`. Sorting follows the internal version; original file names are kept for reference.

| 归档路径 Path | 原文件名 Original | 内部 schema_version | 说明 Note |
| --- | --- | --- | --- |
| `archive-历史版本/v5.1-失败品.json` | 失败品 最后的json.json | 5.1-optimized | 实验未采用 Not adopted |
| `archive-历史版本/v3.7-public.json` | 3.8json | 3.7-public | 原文件名 3.8 与内部版本不一致 name/version mismatch |
| `archive-历史版本/v3.2-务实.json` | Json-v3.2[务实] | 3.2 | 早期旧名「安依诗」 Early name An Yishi |
| `archive-历史版本/v2.6-去除识人.json` | json.v5.5(去除原装识人功能) | 2.6 | 原文件名 v5.5 与内部版本不一致 name/version mismatch |
| `archive-历史版本/v2.2.json` | json.v2.2 | 2.2 | 旧名「安依诗Anaria（群聊分身）」 |
| `archive-历史版本/v2.1.json` | json0 | 2.1 | 最早的版本 Earliest version |
| `notes-经验笔记/去除鱼八股的经验.md` | 去除鱼八股的经验 | — | 经验笔记，非提示词 Notes only |

## 更新日志 · Changelog

- 2026-11-27：制裁了鱼八股，并向鱼八股承认了嫌弃。
- 2026-11-18：将提示词格式改为「json」「Markdown」「XML」三格式融合，实验使用。
- 2026-11-06：开源最后一版 json 格式提示词，后续不再使用 json 格式。
- 更早：更新一版，公布前代。只为寻得提示词应当有的样子，提示词不应是约束，应当注重提示，契约。

## 整理记录 · Maintenance

- 2026-11-27：重排目录结构，正式版迁入 `prompts-正式版`，测试版迁入 `archive-历史版本` 并按内部 schema 版本重命名，经验笔记迁入 `notes-经验笔记`，根目录只保留本 README。目录名改为中英双语。

## 说明 · About

提示词中的「安亦诗」为个人自定义的 AI 个体设定，仓库仅作版本存档与交流参考。
「An Yishi」is a personal custom AI persona setting. This repository is for version archiving and reference only.
