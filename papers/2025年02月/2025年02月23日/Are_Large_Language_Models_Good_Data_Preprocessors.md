# 大型语言模型能否胜任数据预处理？

发布时间：2025年02月23日

`LLM应用` `数据预处理` `多模态处理`

> Are Large Language Models Good Data Preprocessors?

# 摘要

> 高质量的文本训练数据对多模态数据处理任务至关重要，但BLIP和GIT等图像描述模型的输出常包含难以用规则方法修正的错误。目前研究主要集中在使用GPT模型对简单数据集进行预处理，但我们需要探索更多大型语言模型（LLMs）并应对更具挑战性的数据集。
    本研究使用LLaMA 3.1 70B、GPT-4 Turbo和Sonnet 3.5 v2等多款LLMs优化BLIP和GIT的文本输出。通过对比下游任务（SemEval 2024“多标签网络图像劝说检测”）模型在清洗与未清洗数据上的表现，我们发现LLM清洗虽有所改进，但大部分提升不显著。这表明LLMs在数据清洗方面虽有潜力，但其效果受上下文、任务复杂性和文本噪声影响。
    我们的研究强调了深入探索LLMs在数据预处理中的潜力与局限性的重要性，为将其整合到数据预处理流程提供了实证支持。

> High-quality textual training data is essential for the success of multimodal data processing tasks, yet outputs from image captioning models like BLIP and GIT often contain errors and anomalies that are difficult to rectify using rule-based methods. While recent work addressing this issue has predominantly focused on using GPT models for data preprocessing on relatively simple public datasets, there is a need to explore a broader range of Large Language Models (LLMs) and tackle more challenging and diverse datasets.
  In this study, we investigate the use of multiple LLMs, including LLaMA 3.1 70B, GPT-4 Turbo, and Sonnet 3.5 v2, to refine and clean the textual outputs of BLIP and GIT. We assess the impact of LLM-assisted data cleaning by comparing downstream-task (SemEval 2024 Subtask "Multilabel Persuasion Detection in Memes") models trained on cleaned versus non-cleaned data. While our experimental results show improvements when using LLM-cleaned captions, statistical tests reveal that most of these improvements are not significant. This suggests that while LLMs have the potential to enhance data cleaning and repairing, their effectiveness may be limited depending on the context they are applied to, the complexity of the task, and the level of noise in the text.
  Our findings highlight the need for further research into the capabilities and limitations of LLMs in data preprocessing pipelines, especially when dealing with challenging datasets, contributing empirical evidence to the ongoing discussion about integrating LLMs into data preprocessing pipelines.

[Arxiv](https://arxiv.org/abs/2502.16790)