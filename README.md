# Kevin Warsh Perspective Skill

一个适配主流 AI Agent CLI 工具的 Kevin Warsh 视角 Skill。它把 Kevin Warsh 公开材料中的央行判断框架蒸馏成可运行的分析工具，适合分析美联储政策、通胀、QE/QT、金融稳定、央行独立性、银行监管和财政-货币边界问题。

> Boundary: this skill is based on public information only. It does not speak for Kevin Warsh and does not claim access to private views.

## 兼容性

这是一个通用 AI Agent Skill 包，不是 Codex 专用 Skill。它遵循 `skills` CLI 可识别的标准结构：仓库根目录包含 `SKILL.md`，并把扩展资料放在 `references/` 中。

安装时，`skills` CLI 会根据当前环境安装到检测到的 Agent；也可以用 `--agent` 指定某个 Agent，或用 `--agent '*'` 安装到所有支持的 Agent。

## 用途

这个 Skill 适合在这些场景中触发：

- 分析 FOMC 利率决策、通胀路径、降息/加息争议。
- 判断 QE、QT、资产负债表扩张或缩表的制度后果。
- 分析金融危机、银行挤兑、流动性工具、存款保护和救助条款。
- 讨论美联储独立性、国会监督、白宫施压、财政主导风险。
- 用 Warsh 风格的市场仪表盘检查通胀、就业、信用利差、国债市场流动性、美元融资和风险资产反应。
- 做历史回测：看一个 Warsh-style Skill 是否能解释他后来真实行为或公开观点。

## 核心模型

Skill 中提炼了 7 个核心心智模型：

1. Price Stability Is Institutional Capital
2. Independence Is Earned by Staying in Lane
3. Crisis Tools Must Not Become Ordinary Governance
4. The Balance Sheet Is Policy
5. The Market Dashboard Is Not a Crystal Ball
6. Market Discipline Beats State-Client Finance
7. Communication Is Market Operations

另外加入了几个关键校准：

- 不要把 Warsh 简化成“鹰派”。
- 不要把反 QE 常态化误读成反危机救助。
- 不要从强烈内部反对自动推断公开 dissent。
- 区分三种身份模式：Fed Governor、外部改革批评者、Federal Reserve Chair。
- 危机救助不只问“救不救”，还要审计救助条款设计：保护谁、抵押品怎么估值、谁承担损失、如何退出。

## 安装

推荐使用完整 GitHub URL，并明确指定 skill 名称。默认情况下，`skills` CLI 会安装到当前环境检测到的 Agent：

```bash
npx skills add https://github.com/Biaogo94/kevin-warsh-perspective-skill --skill kevin-warsh-perspective
```

这个仓库当前只包含一个 Skill：`kevin-warsh-perspective`。仍然建议显式写 `--skill kevin-warsh-perspective`，这样命令和多 Skill 仓库的标准安装方式一致，也避免 CLI 在仓库结构变化后选错。

安装前可以先列出仓库中可用的 Skill：

```bash
npx skills add https://github.com/Biaogo94/kevin-warsh-perspective-skill --list
```

如果要安装到所有支持的 Agent：

```bash
npx skills add https://github.com/Biaogo94/kevin-warsh-perspective-skill --skill kevin-warsh-perspective --agent '*'
```

如果只想安装到某个 Agent，可以指定 `--agent <agent-name>`。例如安装到 Codex：

```bash
npx skills add https://github.com/Biaogo94/kevin-warsh-perspective-skill --skill kevin-warsh-perspective --agent codex
```

如果要安装到全局用户级目录，而不是当前项目目录：

```bash
npx skills add https://github.com/Biaogo94/kevin-warsh-perspective-skill --skill kevin-warsh-perspective --global
```

安装后可以检查：

```bash
npx skills list
```

本地安装时，可以把整个仓库目录复制到目标 Agent 的 skills 目录，或使用你的 Skill 管理器支持的本地安装流程。

## 使用示例

```text
Use Kevin Warsh perspective to analyze whether the Fed should cut rates while inflation is still above target.
```

```text
用 Warsh 视角分析 2023 年 SVB 事件：Fed 应不应该保护存款人并推出 BTFP？
```

```text
如果财政赤字很高、白宫要求降息、但核心通胀仍然偏高，Warsh-style Fed Chair 会怎么回应？
```

## 目录结构

```text
.
|-- SKILL.md
|-- agents/
|   `-- openai.yaml
`-- references/
    `-- research/
        |-- 01-writings.md
        |-- 02-conversations.md
        |-- 03-expression-dna.md
        |-- 04-external-views.md
        |-- 05-decisions.md
        |-- 06-timeline.md
        |-- 07-fomc-transcripts.md
        |-- 08-backtest.md
        |-- 09-comparative-lineage.md
        |-- 10-warsh-dashboard.md
        |-- 11-chair-constraints.md
        |-- 12-evaluation-suite.md
        |-- 13-scenario-stress-tests.md
        |-- 14-recent-developments-2026-06-17.md
        `-- 15-post-first-fomc-review-2026-07-11.md
```

## 研究与测试

已包含多层测试与动态校准：

- 历史回测：2008 Lehman/AIG、2008 ZLB、2010 reinvestment、2010 QE2。
- 压力场景：2020 COVID QE、2022 通胀、2023 SVB/BTFP、财政压力下要求降息。
- 最新动态校准：2026-06-17 Warsh 首次 FOMC 之前的官方发布边界、May 2026 CPI 能源冲击、dot plot/SEP 与沟通改革 watchlist。
- 会后实证校准：2026-07-11 复盘首次 FOMC 的12-0维持利率、短声明、取消前瞻指引、SEP个人不提交、五个任务组，以及机构证券本金转投短期国债。

当前测试结论：

```text
Historical backtest: 4 strong matches, 1 partial match, 0 misses
Scenario stress tests: 3 strong matches, 1 strong-to-partial match, 0 misses
First-chair backtest: strong match; underpredicted reform speed, SEP abstention, balance-sheet composition action, and task-force governance
```

## 验证

本地验证通过：

```text
quick_validate: Skill is valid!
Nuwa quality_check: 6/6
```

## 来源边界

主要材料来自公开来源，包括：

- Federal Reserve official biography and speeches
- Official FOMC transcripts
- 2014 Bank of England transparency review
- Hoover Institution interviews and materials
- 2026 Senate Banking nomination hearing materials
- Federal Reserve, BLS, Treasury/FDIC/Fed official releases for scenario tests

Generated using the Nuwa skill methodology from https://github.com/alchaincyf/nuwa-skill.
