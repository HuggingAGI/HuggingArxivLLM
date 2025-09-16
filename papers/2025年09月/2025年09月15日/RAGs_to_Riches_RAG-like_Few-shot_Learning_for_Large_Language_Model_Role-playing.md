# RAGs致富有：类RAG少样本学习赋能大型语言模型角色扮演

发布时间：2025年09月15日

`RAG` `医疗健康` `教育科技`

> RAGs to Riches: RAG-like Few-shot Learning for Large Language Model Role-playing

# 摘要

> 角色扮演类大型语言模型（LLMs）正越来越多地应用于医疗、教育、治理等高风险场景，一旦出错，可能直接影响用户信任与福祉。少样本学习是LLM角色扮演中一种经济高效的模式，但现有方法常导致模型以出乎意料甚至可能有害的方式“出戏”，尤其在与恶意用户交互时。借鉴检索增强生成（RAG）的思路，我们将LLM角色扮演重构为文本检索问题，提出一种名为“Rags-to-Riches”的新型提示框架——通过精选参考示例来规范LLM的输出。我们采用“LLM作为裁判”的偏好投票方式对框架进行评估，并提出两种全新的令牌级ROUGE指标：输出交集（IOO）用于量化LLM“即兴发挥”的程度，参考交集（IOR）用于衡量评估任务中少样本示例的利用率。在模拟与恶意用户交互的场景中，我们的提示策略在推理时能从参考示例中多融入35%的令牌；结果显示，在453次角色扮演交互测试中，该模型被一致评为更具真实性，且比零样本和上下文学习（ICL）方法更能持续保持角色一致性。这种方法为构建稳健且符合人类预期的LLM角色扮演框架提供了可扩展方案。

> Role-playing Large language models (LLMs) are increasingly deployed in high-stakes domains such as healthcare, education, and governance, where failures can directly impact user trust and well-being. A cost effective paradigm for LLM role-playing is few-shot learning, but existing approaches often cause models to break character in unexpected and potentially harmful ways, especially when interacting with hostile users. Inspired by Retrieval-Augmented Generation (RAG), we reformulate LLM role-playing into a text retrieval problem and propose a new prompting framework called RAGs-to-Riches, which leverages curated reference demonstrations to condition LLM responses. We evaluate our framework with LLM-as-a-judge preference voting and introduce two novel token-level ROUGE metrics: Intersection over Output (IOO) to quantity how much an LLM improvises and Intersection over References (IOR) to measure few-shot demonstrations utilization rate during the evaluation tasks. When simulating interactions with a hostile user, our prompting strategy incorporates in its responses during inference an average of 35% more tokens from the reference demonstrations. As a result, across 453 role-playing interactions, our models are consistently judged as being more authentic, and remain in-character more often than zero-shot and in-context Learning (ICL) methods. Our method presents a scalable strategy for building robust, human-aligned LLM role-playing frameworks.

[Arxiv](https://arxiv.org/abs/2509.12168)