# LM4OPT项目揭示了大型语言模型在解决数学优化问题时所蕴含的巨大潜能，探索其如何有效用于构建这类问题的解决方案。

发布时间：2024年03月02日

`LLM应用`

> LM4OPT: Unveiling the Potential of Large Language Models in Formulating Mathematical Optimization Problems

# 摘要

> 在日新月异的NLP领域，将语言描述转换为优化问题的数学表达是一大挑战，亟需LLMs展现强大的理解和处理技能。本研究聚焦此任务，比较了包括GPT-3.5、GPT-4及Llama-2-7b在内的几款知名LLM在零样本和单样本环境中的表现，结果揭示出GPT-4尤其在单样本场景下优势明显。本研究创新性地提出了`LM4OPT'——一个针对Llama-2-7b设计的渐进式微调框架，结合噪声嵌入和专业数据集进行训练。但同时，研究也揭示了相较于更大的模型，如Llama-2-7b这类小型模型在面对冗长复杂输入情境时，其语境理解力明显不足。通过运用NL4Opt数据集进行实证探究，我们发现GPT-4仅凭自然语言描述的问题内容便能取得0.63的F1得分，超越了前人研究确立的基准水平，且无需借助任何附加的实体名称信息。而GPT-3.5紧跟其后，二者均胜过了微调过的Llama-2-7b。这些研究成果不仅标定了LLMs在新颖应用领域内的现有实力边界，更为今后从自然语言输入中有效构建优化问题数学模型提供了改进的方向与基础。

> In the rapidly evolving field of natural language processing, the translation of linguistic descriptions into mathematical formulation of optimization problems presents a formidable challenge, demanding intricate understanding and processing capabilities from Large Language Models (LLMs). This study compares prominent LLMs, including GPT-3.5, GPT-4, and Llama-2-7b, in zero-shot and one-shot settings for this task. Our findings show GPT-4's superior performance, particularly in the one-shot scenario. A central part of this research is the introduction of `LM4OPT,' a progressive fine-tuning framework for Llama-2-7b that utilizes noisy embeddings and specialized datasets. However, this research highlights a notable gap in the contextual understanding capabilities of smaller models such as Llama-2-7b compared to larger counterparts, especially in processing lengthy and complex input contexts. Our empirical investigation, utilizing the NL4Opt dataset, unveils that GPT-4 surpasses the baseline performance established by previous research, achieving an F1-score of 0.63, solely based on the problem description in natural language, and without relying on any additional named entity information. GPT-3.5 follows closely, both outperforming the fine-tuned Llama-2-7b. These findings not only benchmark the current capabilities of LLMs in a novel application area but also lay the groundwork for future improvements in mathematical formulation of optimization problems from natural language input.

[Arxiv](https://arxiv.org/abs/2403.01342)