# 大型语言模型中的涌现式响应规划

发布时间：2025年02月10日

`LLM理论`

> Emergent Response Planning in LLM

# 摘要

> 在这项研究中，我们发现，尽管大型语言模型（LLMs）仅经过预测下一个词的训练，但它们的隐藏表示中却编码了超出下一个词的未来输出，展现出一种$	extbf{涌现的规划行为}$。通过简单的探测实验，我们发现LLM的提示表示中包含了其整个响应的全局特征，具体包括$	extit{结构属性}$（如响应长度和推理步骤），$	extit{内容属性}$（如故事创作中的角色选择和多项选择题的答案），以及$	extit{行为属性}$（如回答信心和事实一致性）。除了揭示这种规划能力外，我们还研究了这种能力如何随着模型规模在不同任务中扩展，以及它在生成过程中的演变。这一发现表明，LLMs在隐藏表示中为未来输出进行规划，这为提升生成过程的透明度和控制能力提供了潜在的应用前景。

> In this work, we argue that large language models (LLMs), though trained to predict only the next token, exhibit emergent planning behaviors: $\textbf{their hidden representations encode future outputs beyond the next token}$. Through simple probing, we demonstrate that LLM prompt representations encode global attributes of their entire responses, including $\textit{structural attributes}$ (response length, reasoning steps), $\textit{content attributes}$ (character choices in storywriting, multiple-choice answers at the end of response), and $\textit{behavioral attributes}$ (answer confidence, factual consistency). In addition to identifying response planning, we explore how it scales with model size across tasks and how it evolves during generation. The findings that LLMs plan ahead for the future in their hidden representations suggests potential applications for improving transparency and generation control.

[Arxiv](https://arxiv.org/abs/2502.06258)