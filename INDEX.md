# 目录索引（指针文件）

本文件是仓库的指针索引：每件内容一行——路径 → 是什么 → 谁从哪里进去。
指针文件机制本身是本体系方法论的一部分（见 `docs/methodology.md` §4）：索引与树保持一致，新文件登记、删文件同行删除，索引与树不一致视为缺陷。

| 路径 | 是什么 | 从这里进去的场景 |
|---|---|---|
| `README.md` | 项目门面：一图看懂体系 + 三步接入 | 所有人，第一站 |
| `docs/methodology.md` | 方法论：复盘流水线 / 四层防线 / 回流循环 / 指针文件机制 | 想理解体系怎么运转 |
| `dataset/errors-catalog.json` | 数据集正本：146 条目位 / 835 教训，机器可读 | 做统计、建检索器 |
| `dataset/taxonomy.md` | 分类体系：A–I+Z 十类定义 + 判别句 + 防吞并细则 + D1–D7 检测失败模式 | 给错误归类、写教训卡 |
| `dataset/错误清单-人话版.md` | 人话版：按类组织、每类占比、卡 + 单发两张表 | 想快速浏览错误长什么样 |
| `playbook/team-contract-template.md` | 六栏任务合同模板（含【清单声明】栏） | 建队、派任务前 |
| `playbook/reviewer-quick-reference.md` | 审核员速查清单脱敏版：G/R/T 纪律条 + RL 出口自查 + 48 机制卡 | 审核交付时按角色跳卡 |
| `playbook/lesson-card-template.md` | 教训卡模板：错误台账 + 三选一规则化 | 回流循环立案时 |
| `playbook/project-root-checklist-template.md` | 项目根 1 层清单模板（只收项目专属教训） | 项目落位时 |
| `integration/how-to-adopt.md` | 接入指南：建队前检索清单 → 注入提示词全链路 | 要把体系接进自己的 agent 工具 |
| `LICENSE` | MIT（代码与模板）+ CC BY 4.0（文档与数据集） | 引用、复用前 |
| `.gitignore` | 仓库卫生：系统噪声、临时文件、凭据形态防误提交 | 维护者 |

## 阅读顺序建议

- 新接触本体系：`README.md` → `docs/methodology.md` → `integration/how-to-adopt.md`
- 直接要用：`playbook/` 四件模板按场景拷走；数据消费走 `dataset/` 三件
- 给错误归类：`dataset/taxonomy.md` → `playbook/lesson-card-template.md`

## 数字口径速查

146 条目位 = 48 机制卡 + 98 单发；835 通用教训（另有 4 条项目专属，全库 839 条确认错误）；逻辑条数 822 = 835 − 13（双版本折叠）。每个数字的完整口径短语见 `dataset/errors-catalog.json` 的 `meta` 与 `docs/methodology.md` §1.2。
