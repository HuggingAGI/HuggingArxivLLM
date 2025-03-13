# Search-R1：利用强化学习训练大型语言模型进行推理并善用搜索引擎。

发布时间：2025年03月12日

`LLM应用

LLM应用` `问答系统` `信息检索`

> Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning

# 摘要

> 在大型语言模型（LLMs）中，高效获取外部知识和最新信息对于推理和文本生成至关重要。然而，传统的检索增强和工具使用训练方法存在局限性：要么缺乏多轮检索的灵活性，要么依赖大规模监督数据。直接提示具有推理能力的先进LLMs在推理过程中使用搜索引擎也并非理想选择，因为LLM无法有效学习与搜索引擎的最优交互方式。为了解决这些问题，我们提出了Search-R1，这是DeepSeek-R1模型的扩展版本。通过强化学习（RL），Search-R1使LLM能够在逐步推理过程中自主生成（多个）搜索查询，并实时进行检索。Search-R1通过多轮搜索交互优化LLM的推理过程，借助检索标记遮蔽技术实现稳定的RL训练，并采用基于结果的简单奖励函数。实验结果显示，在七个问答数据集上，Search-R1相较于SOTA基线模型，Qwen2.5-7B提升了26%，Qwen2.5-3B提升了21%，LLaMA3.2-3B提升了10%。此外，本文还深入探讨了RL优化方法、LLM选择以及检索增强推理中响应长度动态的实证见解。Search-R1的代码和模型检查点已开源，访问地址为https://github.com/PeterGriffinJin/Search-R1。

> Efficiently acquiring external knowledge and up-to-date information is essential for effective reasoning and text generation in large language models (LLMs). Retrieval augmentation and tool-use training approaches where a search engine is treated as a tool lack complex multi-turn retrieval flexibility or require large-scale supervised data. Prompting advanced LLMs with reasoning capabilities during inference to use search engines is not optimal, since the LLM does not learn how to optimally interact with the search engine. This paper introduces Search-R1, an extension of the DeepSeek-R1 model where the LLM learns -- solely through reinforcement learning (RL) -- to autonomously generate (multiple) search queries during step-by-step reasoning with real-time retrieval. Search-R1 optimizes LLM rollouts with multi-turn search interactions, leveraging retrieved token masking for stable RL training and a simple outcome-based reward function. Experiments on seven question-answering datasets show that Search-R1 improves performance by 26% (Qwen2.5-7B), 21% (Qwen2.5-3B), and 10% (LLaMA3.2-3B) over SOTA baselines. This paper further provides empirical insights into RL optimization methods, LLM choices, and response length dynamics in retrieval-augmented reasoning. The code and model checkpoints are available at https://github.com/PeterGriffinJin/Search-R1.

[Arxiv](https://arxiv.org/abs/2503.09516)