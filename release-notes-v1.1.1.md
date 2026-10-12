# v1.1.1 增量审计修复

v1.1.0 执行层的同日增量审计（见 [AUDIT.md](AUDIT.md) 增量审计节）发现 1 项忠实度硬伤＋3 项一致性问题＋6 项建议，本版全部落实。

## 修复

- **范文卡忠实度（P1）**：interview-guide 卡 3 拆分陈云青浦素材——310-330 斤细账归位双季稻报告，母猪账（饲料/青草/奶水）另列，消除两条线索捏合。
- **一致性（P2）**：overview.html 目录树补齐 workflow/models/rubrics/evals 并同步 SKILL.md 行描述；runs.log.md 断链修复；README 目录结构补 release-notes 与审计增量口径。
- **工程（P3）**：
  - 安装脚本复制后剔除 `evals/runs` 评测产物（保留简报/评分表/跑分日志供回归），沙盒冒烟 6/6 通过；
  - 修复 install.ps1 UTF-8 BOM 丢失导致的 PowerShell 5.1 解析故障；
  - workflow 新增课题卡交付表述纪律（不带内部工序名）；
  - 问卷走访示范稿"缴饭费"改独立性纪律口径，与 SKILL.md 映射表对齐；
  - 三份评测简报写明字数/题数口径（正文计，附件不计）；
  - models/README 注明示范稿筛项编号对应 rubrics 现行版本；
  - overview 统计条改口径标注。

**Full Changelog**: https://github.com/yxdwind/how-to-research/compare/v1.1.0...v1.1.1
