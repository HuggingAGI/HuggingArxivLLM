# AI智能体架构在实体关系分类中的对比分析

发布时间：2025年06月03日

`LLM应用` `数据科学` `信息抽取`

> Comparative Analysis of AI Agent Architectures for Entity Relationship Classification

# 摘要

> 实体关系分类一直是信息抽取中的难题，尤其在数据标注有限且关系结构复杂的情况下。本研究对比分析了三种基于大型语言模型（LLMs）的关系分类AI代理架构。这些架构包括（1）反思性自我评估，（2）分层任务分解，以及（3）一种新颖的多智能体动态示例生成机制，每种架构都采用了不同的推理模式和提示适应策略。特别值得一提的是，我们的动态示例生成方法引入了实时协作和对抗性提示。我们系统地对比了这些架构在不同领域和模型后端上的表现。实验结果表明，多智能体协调在性能上始终优于标准的少量样本提示，并接近微调模型的水平。这些发现为设计模块化、通用化的基于LLM的结构化关系抽取系统提供了实用的指导。源代码和数据集可在\href{https://github.com/maryambrj/ALIEN.git}{https://github.com/maryambrj/ALIEN.git}获取。

> Entity relationship classification remains a challenging task in information extraction, especially in scenarios with limited labeled data and complex relational structures. In this study, we conduct a comparative analysis of three distinct AI agent architectures designed to perform relation classification using large language models (LLMs). The agentic architectures explored include (1) reflective self-evaluation, (2) hierarchical task decomposition, and (3) a novel multi-agent dynamic example generation mechanism, each leveraging different modes of reasoning and prompt adaptation. In particular, our dynamic example generation approach introduces real-time cooperative and adversarial prompting. We systematically compare their performance across multiple domains and model backends. Our experiments demonstrate that multi-agent coordination consistently outperforms standard few-shot prompting and approaches the performance of fine-tuned models. These findings offer practical guidance for the design of modular, generalizable LLM-based systems for structured relation extraction. The source codes and dataset are available at \href{https://github.com/maryambrj/ALIEN.git}{https://github.com/maryambrj/ALIEN.git}.

[Arxiv](https://arxiv.org/abs/2506.02426)