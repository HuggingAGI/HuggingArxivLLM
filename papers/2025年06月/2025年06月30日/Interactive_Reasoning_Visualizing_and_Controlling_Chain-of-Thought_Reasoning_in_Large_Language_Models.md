# 交互式推理：在大型语言模型中实现思维链推理的可视化与控制

发布时间：2025年06月30日

`LLM应用

理由：这篇论文讨论了如何通过交互式推理设计改进大型语言模型的推理过程，属于将模型应用于实际场景并优化用户体验的范畴，因此归类为LLM应用。` `人工智能` `人机交互`

> Interactive Reasoning: Visualizing and Controlling Chain-of-Thought Reasoning in Large Language Models

# 摘要

> 大型语言模型（LLMs）的输出质量可通过“推理”提升，即生成思维链（CoT）内容片段以优化模型输出。尽管这些思维链包含有价值的信息，但冗长且缺乏组织，审阅起来十分繁琐。此外，它们还缺少用户反馈机会，例如删除不需要的考虑因素、添加所需内容或澄清假设。为此，我们提出了交互式推理——一种将思维链输出可视化为主题层次结构的交互设计，支持用户审阅和修改。我们在Hippo中实现了这一设计，这是一个用于在面对不确定权衡时进行AI辅助决策的原型工具。通过一项包含16名参与者的用户研究，我们发现Hippo的交互式推理功能可让用户快速识别并中断错误生成，高效引导模型生成定制化响应，并更深入理解模型推理过程和输出结果。我们的工作为一种新范式奠定了基础，该范式将用户监督纳入LLM推理过程。

> The output quality of large language models (LLMs) can be improved via "reasoning": generating segments of chain-of-thought (CoT) content to further condition the model prior to producing user-facing output. While these chains contain valuable information, they are verbose and lack explicit organization, making them tedious to review. Moreover, they lack opportunities for user feedback, such as to remove unwanted considerations, add desired ones, or clarify unclear assumptions. We introduce Interactive Reasoning, an interaction design that visualizes chain-of-thought outputs as a hierarchy of topics and enables user review and modification. We implement interactive reasoning in Hippo, a prototype for AI-assisted decision making in the face of uncertain trade-offs. In a user study with 16 participants, we find that interactive reasoning in Hippo allows users to quickly identify and interrupt erroneous generations, efficiently steer the model towards customized responses, and better understand both model reasoning and model outputs. Our work contributes to a new paradigm that incorporates user oversight into LLM reasoning processes.

[Arxiv](https://arxiv.org/abs/2506.23678)