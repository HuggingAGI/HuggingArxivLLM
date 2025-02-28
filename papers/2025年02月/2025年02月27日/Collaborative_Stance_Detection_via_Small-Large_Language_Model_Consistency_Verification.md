# 基于小-大语言模型一致性验证的协作立场检测

发布时间：2025年02月27日

`LLM应用` `社交媒体` `立场检测`

> Collaborative Stance Detection via Small-Large Language Model Consistency Verification

# 摘要

> 社交媒体立场检测旨在识别推文中针对特定目标表达的态度。当前研究更倾向于使用大型语言模型 (LLMs)，而非小型语言模型 (SLMs)，因为 LLMs 的性能提升具有压倒性优势。然而，对于需要处理海量数据分析的社交媒体监控系统而言，完全依赖 LLMs 进行立场检测在实际应用中并不现实。为此，我们提出了一种协作立场检测框架 **CoVer**（Collaborative Stance Detection via Small-Large Language Model Consistency Verification），通过共享上下文的批量推理和 LLM 与 SLM 之间的逻辑验证来提升 LLM 的利用率。具体而言，CoVer 以批次方式处理文本，通过共享上下文的 LLM 推理获得立场预测及其对应解释。随后，为排除上下文噪声带来的偏差，引入 SLM 进行逻辑一致性验证。最后，对多次表现出低逻辑一致性的文本，采用基于先前 LLM 立场预测的一致性加权聚合进行分类。实验结果表明，在零样本设置下，CoVer 在多个基准测试中优于现有最优方法，每条推文仅需 0.54 次 LLM 查询，同时显著提升了性能。我们的 CoVer 为社交媒体立场检测中的 LLM 部署提供了一种更实用的解决方案。


> Stance detection on social media aims to identify attitudes expressed in tweets towards specific targets. Current studies prioritize Large Language Models (LLMs) over Small Language Models (SLMs) due to the overwhelming performance improving provided by LLMs. However, heavily relying on LLMs for stance detection, regardless of the cost, is impractical for real-world social media monitoring systems that require vast data analysis. To this end, we propose \textbf{underline{Co}}llaborative Stance Detection via Small-Large Language Model Consistency \textbf{underline{Ver}}ification (\textbf{CoVer}) framework, which enhances LLM utilization via context-shared batch reasoning and logical verification between LLM and SLM. Specifically, instead of processing each text individually, CoVer processes texts batch-by-batch, obtaining stance predictions and corresponding explanations via LLM reasoning in a shared context. Then, to exclude the bias caused by context noises, CoVer introduces the SLM for logical consistency verification. Finally, texts that repeatedly exhibit low logical consistency are classified using consistency-weighted aggregation of prior LLM stance predictions. Our experiments show that CoVer outperforms state-of-the-art methods across multiple benchmarks in the zero-shot setting, achieving 0.54 LLM queries per tweet while significantly enhancing performance. Our CoVer offers a more practical solution for LLM deploying for social media stance detection.

[Arxiv](https://arxiv.org/abs/2502.19954)