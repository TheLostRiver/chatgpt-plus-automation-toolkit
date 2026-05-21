# Contributing

感谢你对本项目的关注，欢迎提交 Issue 和 Pull Request。

## 开发环境

1. 安装 Python 3.10+
2. 安装依赖：`pip install -r requirements.txt`
3. 安装浏览器：`playwright install chromium`
4. 复制配置：`.env.example -> .env`，`config.example.yaml -> config.yaml`

## 提交规范

- 每个 PR 尽量聚焦一个主题（例如：流程修复、配置增强、文档改进）。
- 保持代码风格与现有项目一致，避免无关重构。
- 涉及流程行为变更时，请补充测试或最小复现说明。

## 安全与隐私要求

- 禁止提交真实账号、token、API key、手机号、卡密、支付信息。
- 禁止提交 `output/`、`profiles/`、`dist/`、`build/` 运行产物。
- 涉及敏感配置改动时，优先更新 `.env.example` 和文档说明。

## Issue 建议模板

- 运行命令与参数
- 关键日志片段
- 预期行为 / 实际行为
- 操作系统与 Python 版本
