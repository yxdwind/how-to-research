# models/ —— 范文拆解卡

产出前读对应卡：先看好的长什么样，再动手。每张卡 = 经典案例的结构骨架 + 可复用要点 + 合成示范稿（标注非原书内容，数字仅为格式示例）。

## 内置卡（4 产出物全覆盖）

| 文件 | 产出物 | 对应章节 | 场景筛 |
|------|--------|---------|--------|
| [plan.md](plan.md) | 调研方案/纲目 | ch02/ch03 | rubrics/plan.md |
| [questionnaire.md](questionnaire.md) | 问卷/量表 | ch05 | rubrics/questionnaire.md |
| [interview-guide.md](interview-guide.md) | 访谈/座谈/蹲点备装 | ch07/ch09/ch10 | rubrics/interview.md |
| [research-report.md](research-report.md) | 调研报告 | ch11 | rubrics/report.md |

> 示范稿中出现的筛项编号（P/W/I/R 等）对应 rubrics/ 现行版本（v1.1.0）；rubrics 重编号时需同步更新各卡。

## local/ —— 本地范文（不入仓库）

`models/local/` 放你自己积累的真实方案/问卷/访谈设计/报告（含 AI 产出后经实战检验的版本），除模板外不入仓库。**约定：产出同一类成果时，local 真实范文优先于内置卡**——真实材料永远比合成示范值钱。

1. **做法**：复制 [local/templates/](local/templates/README.md) 对应填空模板 → 重命名为「类型-场景标识.md」（如 `report-县域消费摸底.md`）→ 逐项填空（删净【】提示）→ 移到 local/ 根目录即生效。
2. **优先级**：local 根目录 > 内置卡；模板本身留在 templates/ 内，不混入 local 根目录。
3. **版权与红线**：local 卡含真实业务数据只放本地自用、不得入仓库；templates/ 四张空模板随仓库分发。
