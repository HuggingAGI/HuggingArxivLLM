# # 面向流程数据的大型语言模型（LLMs）领域适配

发布时间：2025年09月03日

`LLM应用` `工业与制造`

> Domain Adaptation of LLMs for Process Data

# 摘要

> 近年来，大型语言模型（LLMs）已成为包括流程挖掘（PM）在内的多个研究领域的热门方向。当前PM领域的应用主要集中在提示工程策略，或是将事件日志转换为叙事风格数据集，进而借助LLMs的语义能力处理各类任务。与之不同的是，本研究探索将预训练LLMs直接适配到流程数据，无需进行自然语言重构——其背后的动机是：这些模型擅长生成标记序列，这与PM的目标相似。具体而言，我们聚焦参数高效微调技术，以降低此类模型常见的计算开销。实验设置围绕预测流程监控（PPM）展开，同时考虑单任务和多任务预测。结果显示，相比最先进的循环神经网络（RNN）方法及近期的基于叙事风格的解决方案，其预测性能有潜在提升，尤其在多任务场景下表现更优。此外，我们微调后的模型收敛速度更快，所需的超参数优化也显著减少。

> In recent years, Large Language Models (LLMs) have emerged as a prominent area of interest across various research domains, including Process Mining (PM). Current applications in PM have predominantly centered on prompt engineering strategies or the transformation of event logs into narrative-style datasets, thereby exploiting the semantic capabilities of LLMs to address diverse tasks. In contrast, this study investigates the direct adaptation of pretrained LLMs to process data without natural language reformulation, motivated by the fact that these models excel in generating sequences of tokens, similar to the objective in PM. More specifically, we focus on parameter-efficient fine-tuning techniques to mitigate the computational overhead typically associated with such models. Our experimental setup focuses on Predictive Process Monitoring (PPM), and considers both single- and multi-task predictions. The results demonstrate a potential improvement in predictive performance over state-of-the-art recurrent neural network (RNN) approaches and recent narrative-style-based solutions, particularly in the multi-task setting. Additionally, our fine-tuned models exhibit faster convergence and require significantly less hyperparameter optimization.

[Arxiv](https://arxiv.org/abs/2509.03161)