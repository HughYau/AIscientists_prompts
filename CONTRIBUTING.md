# 贡献指南

感谢你对 AIscientists_prompts 的兴趣！这是一个面向社区的提示词平台，欢迎大家提出建议、修正与新增高质量提示词。为帮助你高效贡献、并便于维护者审核，请遵循以下流程与约定。

## 快速开始
- 仓库地址: https://github.com/HughYau/AIscientists_prompts
- 在线预览: https://hughyau.github.io/AIscientists_prompts/

## 我可以贡献什么？
- 新的高质量提示词卡片（清晰用途、严格格式、可直接复制使用）
- 对现有提示词的修订（更清晰、更严谨、修复格式/错别字/占位符）
- 新的分类或分类优化
- 文档改进（README、指引、示例）
- 小型交互与 UI 改进（保持零依赖或最小依赖）

## 行为准则
本项目遵循 Contributor Covenant（见 `CODE_OF_CONDUCT.md`）。

## 提交 Issue
- 使用 Issue 模板（Bug/功能建议/内容提案）
- 尽量提供复现步骤、截图或示例
- 对于提示词新增，请给出：
  - 分类（category）
  - 标题（title）
  - 用途（purpose）
  - 占位符（placeholders）
  - 内容（content）
  - 来源/许可信息（若非原创）

## 提交 PR
- 从 `main` 创建分支（命名建议）：
  - `feat/prompt-<short-name>` 新提示词
  - `fix/prompt-<short-name>` 修复提示词
  - `docs/<topic>` 文档类改动
- 每个 PR 聚焦单一主题，便于快速审核
- 遵循风格与结构（见下文“提示词卡片规范”）
- PR 内容需说明：动机、变更点、截图或预览（如 UI 变动）

## 提示词卡片规范（重要）
- JSON/代码类输出：请在提示词中明确“只输出 JSON”或“只输出单代码块”，避免夹带解释文本
- 占位符：统一使用 `{placeholder_name}`，并在描述中说明含义
- 许可与来源：
  - 原创：注明 `source: { name: '原创 by <your_name>', license: 'Original', modified: false }`
  - 改编：注明来源仓库/文献、许可（如 Apache-2.0/MIT），并尽量附链接与是否改编 `modified: true`
- 分类建议（可扩展）：创意生成 / 论文撰写（通用）/ 文本审稿（LLM）/ 图像审稿（VLM）/ 最终绘图聚合 / 日志与选择 / TreeSearch / Agents 等

## 本地开发
本项目为纯静态页面：
1. 直接双击 `index.html` 或使用任意静态服务器即可预览
2. 主要编辑点：`index.html` 中的 `allPrompts` 数组（新增/修改卡片）
3. 保持 Tailwind CDN 方式，避免引入复杂构建

## 审核流程
- 维护者将根据以下维度审核：
  - 质量：是否可直接使用、无歧义、格式严格
  - 价值：是否真正解决实际问题、避免过度模板化
  - 兼容：是否不会破坏现有功能与风格
  - 许可：是否清晰、合规
- 可能会要求你补充示例或做轻微调整

## 版权与许可
- 若引用他人内容，请确保遵循其许可证（例如 Apache-2.0 需保留版权与许可声明）
- 请勿提交无法明确来源/许可的内容

感谢你的贡献！如果这个项目对你有帮助，欢迎 Star 支持并分享给更多研究者与开发者。
