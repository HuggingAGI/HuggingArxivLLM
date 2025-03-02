# 交互式决策中的程序合成对话代理

发布时间：2025年02月26日

`Agent`

> Program Synthesis Dialog Agents for Interactive Decision-Making

# 摘要

> 从医疗诊断到税务规划，许多现实世界中的资格问题都可以转化为自然语言表达的决策问题，模型需根据用户特征做出二元选择。面对法律条文或频繁更新的资助机会等大型领域，人工标注（如网页表单或决策树）往往难以实施，因此亟需能够自动辅助决策的智能体。由于关键信息通常仅用户掌握，智能体提出恰当问题显得尤为重要。在决定何时结束对话时，智能体需在准确性和提问数量间找到平衡，这对用户体验和成本至关重要。为评估这一任务，我们推出BeNYfits，一个通过交互式决策制定来判断用户是否符合多个重叠社会福利机会的新基准测试。实验显示，现有语言模型在处理过程中常出现幻觉现象，GPT-4o使用ReAct风格的思维链时F1得分仅为35.7。为此，我们提出ProADA，一种创新方法，通过将对话规划映射为代码生成问题，并利用结构化数据中的空白来确定最佳下一步行动，从而辅助决策。我们的智能体ProADA将F1分数提升至55.6，同时保持几乎相同的对话轮数。

> Many real-world eligibility problems, ranging from medical diagnosis to tax planning, can be mapped to decision problems expressed in natural language, wherein a model must make a binary choice based on user features. Large-scale domains such as legal codes or frequently updated funding opportunities render human annotation (e.g., web forms or decision trees) impractical, highlighting the need for agents that can automatically assist in decision-making. Since relevant information is often only known to the user, it is crucial that these agents ask the right questions. As agents determine when to terminate a conversation, they face a trade-off between accuracy and the number of questions asked, a key metric for both user experience and cost. To evaluate this task, we propose BeNYfits, a new benchmark for determining user eligibility for multiple overlapping social benefits opportunities through interactive decision-making. Our experiments show that current language models struggle with frequent hallucinations, with GPT-4o scoring only 35.7 F1 using a ReAct-style chain-of-thought. To address this, we introduce ProADA, a novel approach that leverages program synthesis to assist in decision-making by mapping dialog planning to a code generation problem and using gaps in structured data to determine the best next action. Our agent, ProADA, improves the F1 score to 55.6 while maintaining nearly the same number of dialog turns.

[Arxiv](https://arxiv.org/abs/2502.19610)