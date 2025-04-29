# 基于 LLM 的对话数据自动演绎编码：借助对话特有的特征提升上下文理解能力

发布时间：2025年04月28日

`LLM应用`

> LLM-Assisted Automated Deductive Coding of Dialogue Data: Leveraging Dialogue-Specific Characteristics to Enhance Contextual Understanding

# 摘要

> 对话数据一直是理解学习过程的关键，它让我们深入了解学生如何参与协作讨论，以及这些互动如何塑造他们的知识构建。大型语言模型（LLMs）的出现为推进定性研究，特别是在对话数据的自动编码方面，带来了巨大机遇。然而，对话中固有的上下文复杂性对这些模型提出了独特挑战，尤其是在理解和解释复杂上下文信息方面。

本研究通过开发一种新型的LLM辅助对话数据自动编码方法，成功应对了这些挑战。我们的框架有三大创新：1) 基于对话特有的特征——交际行为和交际事件，分别使用角色提示和链式思维方法设计独立的提示来预测话语的编码；2) 采用包括GPT-4-turbo、GPT-4o和DeepSeek在内的多个LLMs进行协作编码预测；3) 利用事件与行为之间的相互关系，通过GPT-4o实现了上下文一致性检查，显著提升了准确性。

研究发现，行为预测的准确性始终高于事件预测。本研究不仅为提高对话数据自动编码的精度提供了一种新的方法论框架，还为解决对话分析中的上下文挑战提供了一种可扩展的解决方案。
    

> Dialogue data has been a key source for understanding learning processes, offering critical insights into how students engage in collaborative discussions and how these interactions shape their knowledge construction. The advent of Large Language Models (LLMs) has introduced promising opportunities for advancing qualitative research, particularly in the automated coding of dialogue data. However, the inherent contextual complexity of dialogue presents unique challenges for these models, especially in understanding and interpreting complex contextual information. This study addresses these challenges by developing a novel LLM-assisted automated coding approach for dialogue data. The novelty of our proposed framework is threefold: 1) We predict the code for an utterance based on dialogue-specific characteristics -- communicative acts and communicative events -- using separate prompts following the role prompts and chain-of-thoughts methods; 2) We engaged multiple LLMs including GPT-4-turbo, GPT-4o, DeepSeek in collaborative code prediction; 3) We leveraged the interrelation between events and acts to implement consistency checking using GPT-4o. In particular, our contextual consistency checking provided a substantial accuracy improvement. We also found the accuracy of act predictions was consistently higher than that of event predictions. This study contributes a new methodological framework for enhancing the precision of automated coding of dialogue data as well as offers a scalable solution for addressing the contextual challenges inherent in dialogue analysis.

[Arxiv](https://arxiv.org/abs/2504.19734)