# v1.2.0 执行层定型

v1.1.x 评测体系验证有效（四类产出物 × 高难简报全部过判定线）后的结构定型版：把重构做干净，并让回归守住每一次改动。

## 变更

- **SKILL.md**：执行模式段压缩为纯知识地图（六环节 ↔ 章节 ↔ 一句话要点），执行细则收敛到 workflow.md 单一来源；description 触发词扩充（mystery shopping / field studies / competitor analysis / customer interviews）。
- **models/local/templates/**：新增四张填空模板（方案/问卷/访谈/报告，随仓库分发），统一"骨架/要点/数据位/禁忌"四段结构；问卷模板自带敌意审查记录位、报告模板自带引语位与修改记录位。`.gitignore` 调整为 local/* 不入仓库但 templates/ 放行。
- **glossary**：新增"执行层术语"章（课题卡、三行自检报告、AI 代办/人机协作分轨、通用筛/场景筛、范文拆解卡、【待核实】），明确标注非原书内容。
- **cheatsheet**：新增"产出任务速查"六条判断规则（走工序、预设降级、过筛交付、【待核实】红线、人机分轨、紧急直报）。
- **workflow**：第⑥步固化自检留痕要求——全部通过时也须逐项表或标注代表项位置，纯计数汇总不算留痕。
- **install**：双脚本黑名单补全，AUDIT.md / overview.html / release-notes-* 不再装进用户技能目录。

## 评测

- **覆盖扩展**：新增 brief-7 访谈设计高难简报，四类产出物（方案/问卷/报告/访谈设计）评测覆盖 4/4；访谈轨带 skill 98.0 vs 基线 86.4（+13.4%）过判定线。
- **回归验证**：本版结构改动后跑全量回归，4/4 无退化（98–100 分）；期间发现并修复一处自检留痕形式退化（brief-4 首跑 A4 −2，固化 workflow 留痕要求后重跑 100.0）。
- 明细见 [evals/runs.log.md](evals/runs.log.md)。

**Full Changelog**: https://github.com/yxdwind/how-to-research/compare/v1.1.1...v1.2.0
