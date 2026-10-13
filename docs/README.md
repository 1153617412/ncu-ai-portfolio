# 文档中心 docs/

这里存放**跨周复用**的通用资料，避免每个实验目录重复造轮子。

| 文件 | 用途 |
| :--- | :--- |
| `实验报告模板.md` | 每周实验报告的统一起草模板 |
| `环境配置指南.md` | 从零安装 Python / Git / IDE 的图文步骤 |
| `常见问题.md` | 报错速查表（遇到红字先来这里找） |

## 命名约定

- 目录：全小写英文 + 连字符，例如 `week01-setup`、`week12-ml-intro`
- Python 文件：`snake_case.py`，例如 `data_clean.py`
- 实验报告：`REPORT.md`（放在对应周目录内）
- 数据文件：`data/` 下分 `raw/`（原始）与 `processed/`（处理后）

## 提交约定

每次完成一周实验后：

```bash
git add .
git commit -m "feat(week05): 完成文件读写实验与报告"
git push
```

Commit 信息格式：`类型(周次): 一句话说明`

- `feat` 新增实验内容
- `fix` 修 bug
- `docs` 只改文档
- `chore` 杂项（配置、清理）
