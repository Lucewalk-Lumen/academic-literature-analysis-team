# academic-literature-analysis-team

**文献计量分析团** · v1.0.1 · `team`

> Academic literature analysis for bibliometrics and review workflows


Part of the [Lucewalk Lumen](https://github.com/Lucewalk-Lumen/about-me) collection.


## What it does

- **Data auditor** — validates the export before any number is computed
- **Network mapper** — citation and co-occurrence structures out of your own library
- **Trend analyst** — themes, trajectories and research-front shifts
- **Review outliner** — turns the analysis into a review skeleton you can write against
- Two dedicated skills: `academic-lit-analysis` (analysis engine) and `review-skeleton` (writing frame)

## How it works

- Audit first: the data auditor checks exports before computation, so numbers are trustworthy
- Mapping and trend analysis run on the audited data, then feed the review outliner
- The output is a writing frame, not just charts — designed to be written against

## Agent roster

| Agent | Role |
|---|---|
| `academic-lit-analysis-lead` | 文献计量分析团 - 主理人 析文 |
| `data-auditor` | 数据核查师 · 见核 |
| `network-mapper` | 共现网络解读 - 织网（成员） |
| `review-outliner` | 综述骨架生成 - 构纲（成员） |
| `trend-analyst` | 趋势分析师 · 鉴势 |

## Skills

`academic-lit-analysis` · `review-skeleton`

## Install

1. Download the package zip from [Releases](https://github.com/Lucewalk-Lumen/academic-literature-analysis-team/releases) or clone this repo;
2. Unzip keeping the internal manifest structure intact;
3. Import/register in WorkBuddy (custom connector → trust & enable).


## Version

Current release: **v1.0.1**. See the package manifest for details.


## License

MIT — see [LICENSE](LICENSE).


---

## How to use / 如何使用

This is an **expert package / skill for the WorkBuddy AI assistant**.

**Prerequisites · 前置条件**
- WorkBuddy installed and signed in (latest version recommended).
- Prepare your own materials first (e.g. your literature library / course outline) — the agent works under a "stay faithful to the source, cite the page" rule.

**Import / enable · 导入 / 启用**
1. Download the package zip from this repo's **Releases**, or clone the repo; keep the `.codebuddy-plugin/` manifest intact.
2. In WorkBuddy, *custom connector → trust & enable*, or import the expert / enable the skill from the skill center.
3. Run one minimal example below to confirm the output matches your standards.

**Minimal example · 最小示例**
> 把我的 WoS / CNKI 题录导进来,生成一份可下笔的综述骨架。


**Portability · 可移植性** — Delivered for WorkBuddy; won't run as-is elsewhere, but the methodology is documented in plain text and can be re-implemented on another platform. Knowledge is portable even if the runtime isn't.

**More · 更多**
Full onboarding & per-line guidance: portal [Lucewalk Lumen · 沐光行客](https://github.com/Lucewalk-Lumen/about-me) → "How to use". Issues: open one on this repo.

<details>
<summary><strong>📖 中文说明(Chinese README)</strong></summary>

# 文献计量分析团

**学术文献计量分析:从题录导出到可直接撰写的综述骨架**

- 版本:v1.0.1 · 类型:team
- 版本真源:包内 `.codebuddy-plugin/plugin.json` 的 `version` 字段
- 所属合集:[Lucewalk Experts 门户](https://github.com/Lucewalk-Lumen/about-me)(全部产品目录与品牌说明)

## 安装

1. 从本仓库 [Releases](https://github.com/Lucewalk-Lumen/academic-literature-analysis-team/releases) 页下载该包 zip(或直接克隆仓库);
2. 解压后**保持内部清单结构不变**(`.codebuddy-plugin/` 目录);
3. 在 WorkBuddy 中导入/注册(自定义连接器入口 → 信任并启用)。

能力详解见上方英文文档;品牌与全部产品目录见门户仓库。

## 许可

MIT——详见 [LICENSE](LICENSE)。

</details>
