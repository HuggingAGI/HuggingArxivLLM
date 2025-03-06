# # 特征级别人工文本检测的洞察：借助稀疏自动编码器

发布时间：2025年03月05日

`LLM应用` `机器学习`

> Feature-Level Insights into Artificial Text Detection with Sparse Autoencoders

# 摘要

> 文本检测（ATD）随着先进大型语言模型（LLMs）的兴起变得越来越重要。尽管人们付出了诸多努力，但没有单一算法能在不同类型的未见文本上始终保持良好表现，也无法保证对新LLMs的有效泛化。可解释性在实现这一目标中扮演着关键角色。

本研究通过使用稀疏自编码器（SAE）从Gemma-2-2b的残差流中提取特征，增强ATD的可解释性。我们识别出既可解释又高效的特征，并通过领域和模型特定的统计方法、引导方法以及人工或基于LLM的解释，分析其语义和相关性。我们的方法为不同模型生成的文本与人类编写内容之间的差异提供了有价值的见解。

我们发现，尽管现代LLMs能够通过个性化提示生成类似人类的输出，但它们在信息密集型领域中仍具有独特的写作风格。

> Artificial Text Detection (ATD) is becoming increasingly important with the rise of advanced Large Language Models (LLMs). Despite numerous efforts, no single algorithm performs consistently well across different types of unseen text or guarantees effective generalization to new LLMs. Interpretability plays a crucial role in achieving this goal. In this study, we enhance ATD interpretability by using Sparse Autoencoders (SAE) to extract features from Gemma-2-2b residual stream. We identify both interpretable and efficient features, analyzing their semantics and relevance through domain- and model-specific statistics, a steering approach, and manual or LLM-based interpretation. Our methods offer valuable insights into how texts from various models differ from human-written content. We show that modern LLMs have a distinct writing style, especially in information-dense domains, even though they can produce human-like outputs with personalized prompts.

[Arxiv](https://arxiv.org/abs/2503.03601)