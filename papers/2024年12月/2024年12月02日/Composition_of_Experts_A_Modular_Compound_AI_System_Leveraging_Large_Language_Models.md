# 《专家组合：借助大型语言模型的模块化复合人工智能系统》

发布时间：2024年12月02日

`LLM应用` `人工智能` `计算机系统`

> Composition of Experts: A Modular Compound AI System Leveraging Large Language Models

# 摘要

> 大型语言模型（LLMs）进步显著，但其整体性在可扩展性、成本及定制化方面存在挑战。本文引入了专家组合（CoE），这是一个借助多个专家LLMs的模块化复合人工智能系统。CoE通过路由器为给定输入动态挑选最合适的专家，从而有效利用资源并提升性能。我们阐述了训练CoE的一般性问题，并探讨了相关的内在复杂性。我们提出了一种两步路由策略来应对这些复杂性，先是用路由器将输入划分为不同类别，再进行类别与专家的映射以获取所需专家。CoE为构建复合人工智能系统提供了灵活且高性价比的解决方案。我们的实证评估显示，CoE在减少计算开销的同时实现了出色的性能。鉴于CoE由众多专家LLMs构成，它在经济高效服务方面有独特的系统要求。我们展示了利用SambaNova SN40L RDU独特的三层内存架构对CoE的高效实现。使用开放权重LLMs Qwen/Qwen2-7B-Instruct、google/gemma-2-9b-it、google/gemma-2-27b-it、meta-llama/Llama-3.1-70B-Instruct 和 Qwen/Qwen2-72B-Instruct 得到的CoE，在Arena-Hard上平均活跃参数仅310亿时得分59.4，在MT-Bench上平均活跃参数540亿时得分9.06。

> Large Language Models (LLMs) have achieved remarkable advancements, but their monolithic nature presents challenges in terms of scalability, cost, and customization. This paper introduces the Composition of Experts (CoE), a modular compound AI system leveraging multiple expert LLMs. CoE leverages a router to dynamically select the most appropriate expert for a given input, enabling efficient utilization of resources and improved performance. We formulate the general problem of training a CoE and discuss inherent complexities associated with it. We propose a two-step routing approach to address these complexities that first uses a router to classify the input into distinct categories followed by a category-to-expert mapping to obtain desired experts. CoE offers a flexible and cost-effective solution to build compound AI systems. Our empirical evaluation demonstrates the effectiveness of CoE in achieving superior performance with reduced computational overhead. Given that CoE comprises of many expert LLMs it has unique system requirements for cost-effective serving. We present an efficient implementation of CoE leveraging SambaNova SN40L RDUs unique three-tiered memory architecture. CoEs obtained using open weight LLMs Qwen/Qwen2-7B-Instruct, google/gemma-2-9b-it, google/gemma-2-27b-it, meta-llama/Llama-3.1-70B-Instruct and Qwen/Qwen2-72B-Instruct achieve a score of $59.4$ with merely $31$ billion average active parameters on Arena-Hard and a score of $9.06$ with $54$ billion average active parameters on MT-Bench.

[Arxiv](https://arxiv.org/abs/2412.01868)