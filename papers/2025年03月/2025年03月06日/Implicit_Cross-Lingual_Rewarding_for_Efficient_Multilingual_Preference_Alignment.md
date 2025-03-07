# 隐式跨语言奖励机制：实现高效多语言偏好对齐

发布时间：2025年03月06日

`LLM应用

理由：这篇论文探讨了如何将直接偏好优化（DPO）方法应用于多语言大型语言模型的对齐问题，提出了一种通过隐式奖励模型将英文模型的偏好转移到其他语言的方法。该研究属于将DPO技术应用于多语言模型的偏好对齐，属于LLM的应用层面。` `多语言模型` `偏好对齐`

> Implicit Cross-Lingual Rewarding for Efficient Multilingual Preference Alignment

# 摘要

> 直接偏好优化（DPO）已成为将大型语言模型（LLMs）与人类偏好对齐的突出方法。尽管DPO在对齐英文LLMs方面取得了显著进展，但多语言偏好对齐仍受制于数据稀缺问题。为了解决这一问题，我们提出了一种新方法，通过隐式奖励从已良好对齐的英文模型中捕捉学习到的偏好，并通过迭代训练将其转移到其他语言。具体而言，我们从英文DPO对齐模型的 logits 和其对应的参考模型中推导出一个隐式奖励模型。然后利用这个奖励模型对跨语言指令遵循对中的偏好关系进行标注，使用英文指令来评估多语言响应。标注后的数据随后用于多语言DPO微调，从而实现从英文到其他语言的偏好知识转移。对Llama3进行两次微调迭代，在X-AlpacaEval排行榜上所有训练语言的平均胜率提高了12.72%，长度控制胜率提高了5.97%。我们的研究结果表明，利用现有的英文对齐模型可以实现高效且有效的多语言偏好对齐，大大减少了对大量多语言偏好数据的需求。代码可在https://github.com/ZNLP/Implicit-Cross-Lingual-Rewarding获取

> Direct Preference Optimization (DPO) has become a prominent method for aligning Large Language Models (LLMs) with human preferences. While DPO has enabled significant progress in aligning English LLMs, multilingual preference alignment is hampered by data scarcity. To address this, we propose a novel approach that $\textit{captures}$ learned preferences from well-aligned English models by implicit rewards and $\textit{transfers}$ them to other languages through iterative training. Specifically, we derive an implicit reward model from the logits of an English DPO-aligned model and its corresponding reference model. This reward model is then leveraged to annotate preference relations in cross-lingual instruction-following pairs, using English instructions to evaluate multilingual responses. The annotated data is subsequently used for multilingual DPO fine-tuning, facilitating preference knowledge transfer from English to other languages. Fine-tuning Llama3 for two iterations resulted in a 12.72% average improvement in Win Rate and a 5.97% increase in Length Control Win Rate across all training languages on the X-AlpacaEval leaderboard. Our findings demonstrate that leveraging existing English-aligned models can enable efficient and effective multilingual preference alignment, significantly reducing the need for extensive multilingual preference data. The code is available at https://github.com/ZNLP/Implicit-Cross-Lingual-Rewarding

[Arxiv](https://arxiv.org/abs/2503.04647)