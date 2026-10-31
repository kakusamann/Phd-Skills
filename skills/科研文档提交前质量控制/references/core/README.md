# 核心检查模块索引

八大模块由主 Skill 默认调度。执行全面检查时，按模块读取对应规则文件；专项检查时，只读取用户指定模块。

| 编号 | 模块 | 参考文件 | 默认优先级 |
|---|---|---|---|
| 01 | 文档结构与格式 | 01-document-structure-format.md | P0 |
| 02 | 标题与样式体系 | 02-heading-styles.md | P0 |
| 03 | 编号与交叉引用 | 03-numbering-cross-references.md | P0 |
| 04 | 图表与公式规范 | 04-figures-tables-equations.md | P0 |
| 05 | 文本与语言质量 | 05-text-language-quality.md | P1 |
| 06 | AI 生成痕迹检查 | 06-ai-writing-patterns.md | P1 |
| 07 | 复制与编辑痕迹检查 | 07-copy-editing-traces.md | P0 |
| 08 | 文档内部一致性 | 08-document-consistency.md | P1 |

## 使用提醒

- 模块默认优先级不代表该模块中的每个问题都必须使用相同等级；按实际影响分级。
- 页面尺寸和页边距不属于默认检查项。
- 写作风格默认中立，不加载风格 Profile，除非用户主动指定。
- AI 特征库默认加载，但只能报告可观察的语言模式，不得断言作者是否使用 AI。
- 文档内部一致性不默认包含摘要与结论一致性或正文引文与参考文献逐项对应。
- 所有检查均为只读；最终输出 Markdown 检查报告，不修改原始文档。
