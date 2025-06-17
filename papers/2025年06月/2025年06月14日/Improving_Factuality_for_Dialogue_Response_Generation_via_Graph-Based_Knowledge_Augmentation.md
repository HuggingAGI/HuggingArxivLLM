# 基于图的知识增强提升对话生成的事实准确性

发布时间：2025年06月14日

`LLM应用` `对话系统` `对话生成`

> Improving Factuality for Dialogue Response Generation via Graph-Based Knowledge Augmentation

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中表现出色，但在对话回应生成中存在幻觉问题。我们提出了一种新框架，结合知识检索、对话重写和知识增强生成，提升对话回应的事实准确性。同时，我们改进了事实评分方法，提供更可靠的评估。在OpendialKG和HybriDialogue数据集上，我们的方法显著优于现有基线，包括G-retriever。代码即将发布。

> Large Language Models (LLMs) succeed in many natural language processing tasks. However, their tendency to hallucinate - generate plausible but inconsistent or factually incorrect text - can cause problems in certain tasks, including response generation in dialogue. To mitigate this issue, knowledge-augmented methods have shown promise in reducing hallucinations. Here, we introduce a novel framework designed to enhance the factuality of dialogue response generation, as well as an approach to evaluate dialogue factual accuracy. Our framework combines a knowledge triple retriever, a dialogue rewrite, and knowledge-enhanced response generation to produce more accurate and grounded dialogue responses. To further evaluate generated responses, we propose a revised fact score that addresses the limitations of existing fact-score methods in dialogue settings, providing a more reliable assessment of factual consistency. We evaluate our methods using different baselines on the OpendialKG and HybriDialogue datasets. Our methods significantly improve factuality compared to other graph knowledge-augmentation baselines, including the state-of-the-art G-retriever. The code will be released on GitHub.

[Arxiv](https://arxiv.org/abs/2506.12496)