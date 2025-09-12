# 面向文本到模型转换的全局约束大型语言模型智能体

发布时间：2025年09月10日

`Agent` `基础理论`

> Global Constraint LLM Agents for Text-to-Model Translation

# 摘要

> 将优化或满足性问题的自然语言描述准确转换为MiniZinc模型颇具挑战，这一过程既需逻辑推理能力，又需约束编程专业知识。为此，我们提出一种智能体框架：多个专精的大型语言模型（LLM）智能体按全局约束类型分解建模任务——每个智能体专注于检测特定类别的全局约束并生成对应代码，最后由组装智能体将这些约束代码片段整合为完整的MiniZinc模型。通过将问题拆解为更小且定义清晰的子任务，每个LLM只需处理更简单的推理任务，从而有望降低整体复杂度。我们对多个LLM开展了初步实验，结果表明其性能优于零样本提示、思维链提示等基线方法。最后，我们还勾勒了未来工作的完整路线图，重点指出了潜在的改进方向与增强方案。

> Natural language descriptions of optimization or satisfaction problems are challenging to translate into correct MiniZinc models, as this process demands both logical reasoning and constraint programming expertise. We introduce a framework that addresses this challenge with an agentic approach: multiple specialized large language model (LLM) agents decompose the modeling task by global constraint type. Each agent is dedicated to detecting and generating code for a specific class of global constraint, while a final assembler agent integrates these constraint snippets into a complete MiniZinc model. By dividing the problem into smaller, well-defined sub-tasks, each LLM handles a simpler reasoning challenge, potentially reducing overall complexity. We conduct initial experiments with several LLMs and show better performance against baselines such as one-shot prompting and chain-of-thought prompting. Finally, we outline a comprehensive roadmap for future work, highlighting potential enhancements and directions for improvement.

[Arxiv](https://arxiv.org/abs/2509.08970)