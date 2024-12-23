# Context-DPO：让语言模型与上下文的忠实度相契合

发布时间：2024年12月17日

`LLM应用` `模型优化`

> Context-DPO: Aligning Language Models for Context-Faithfulness

# 摘要

> 大型语言模型（LLMs）要给出可靠的回应，就得遵循用户指令和检索到的信息。尽管对齐技术能让 LLMs 与人类的意图和价值观相符，但通过对齐来提升上下文忠实度这方面仍有待深入探索。为此，我们提出了$	extbf{Context-DPO}$，这是首个专门用于增强 LLMs 上下文忠实度的对齐方法。我们还引入了$	extbf{ConFiQA}$，这是一个基准，它模拟具有知识冲突的检索增强生成（RAG）场景，用于评估上下文忠实度。借助 ConFiQA 中针对提供的上下文问题的忠实和顽固回应，我们的 Context-DPO 通过直接偏好优化来对齐 LLMs。大量实验表明，我们的 Context-DPO 显著提高了上下文忠实度，在热门开源模型上实现了 35%至 280%的提升。进一步分析显示，Context-DPO 在保留 LLMs 生成能力的同时，为上下文的利用提供了可解释的见解。我们的代码和数据发布于 https://github.com/byronBBL/Context-DPO

> Reliable responses from large language models (LLMs) require adherence to user instructions and retrieved information. While alignment techniques help LLMs align with human intentions and values, improving context-faithfulness through alignment remains underexplored. To address this, we propose $\textbf{Context-DPO}$, the first alignment method specifically designed to enhance LLMs' context-faithfulness. We introduce $\textbf{ConFiQA}$, a benchmark that simulates Retrieval-Augmented Generation (RAG) scenarios with knowledge conflicts to evaluate context-faithfulness. By leveraging faithful and stubborn responses to questions with provided context from ConFiQA, our Context-DPO aligns LLMs through direct preference optimization. Extensive experiments demonstrate that our Context-DPO significantly improves context-faithfulness, achieving 35% to 280% improvements on popular open-source models. Further analysis demonstrates that Context-DPO preserves LLMs' generative capabilities while providing interpretable insights into context utilization. Our code and data are released at https://github.com/byronBBL/Context-DPO

[Arxiv](https://arxiv.org/abs/2412.15280)