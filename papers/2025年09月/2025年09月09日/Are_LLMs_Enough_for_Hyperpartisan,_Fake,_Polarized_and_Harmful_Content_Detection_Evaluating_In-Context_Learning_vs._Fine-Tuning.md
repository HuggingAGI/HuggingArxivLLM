# # 大型语言模型（LLMs）能否胜任超党派、虚假、极化和有害内容检测？评估上下文学习与微调

发布时间：2025年09月09日

`LLM应用` `媒体与娱乐`

> Are LLMs Enough for Hyperpartisan, Fake, Polarized and Harmful Content Detection? Evaluating In-Context Learning vs. Fine-Tuning

# 摘要

> 网络平台上虚假新闻、极化内容、政治偏见信息及有害内容的传播已成为一个严重问题。尽管大型语言模型已展现出应用潜力，但目前尚无研究针对不同模型、使用方法和语言对其性能进行系统的基准测试。本研究全面综述了大型语言模型在超党派与虚假新闻检测、有害推文识别及政治偏见判断中的多种适配范式。我们的实验覆盖10个数据集和5种语言（英语、西班牙语、葡萄牙语、阿拉伯语、保加利亚语），包含二分类与多分类任务场景。我们测试了多种策略，从语言模型的参数高效微调，到各类上下文学习策略及提示词设计。具体包括零样本提示词、代码本、少样本学习（采用行列式点过程进行示例的随机选择与多样化选择）及思维链。研究发现，与模型微调相比，上下文学习的性能往往欠佳。这一核心发现强调：即使是较小的模型，在特定任务场景下进行微调也至关重要——即便与上下文学习设置中评估的大型模型（本研究中为LlaMA3.1-8b-Instruct、Mistral-Nemo-Instruct-2407和Qwen2.5-7B-Instruct）相比亦是如此。

> The spread of fake news, polarizing, politically biased, and harmful content on online platforms has been a serious concern. With large language models becoming a promising approach, however, no study has properly benchmarked their performance across different models, usage methods, and languages. This study presents a comprehensive overview of different Large Language Models adaptation paradigms for the detection of hyperpartisan and fake news, harmful tweets, and political bias. Our experiments spanned 10 datasets and 5 different languages (English, Spanish, Portuguese, Arabic and Bulgarian), covering both binary and multiclass classification scenarios. We tested different strategies ranging from parameter efficient Fine-Tuning of language models to a variety of different In-Context Learning strategies and prompts. These included zero-shot prompts, codebooks, few-shot (with both randomly-selected and diversely-selected examples using Determinantal Point Processes), and Chain-of-Thought. We discovered that In-Context Learning often underperforms when compared to Fine-Tuning a model. This main finding highlights the importance of Fine-Tuning even smaller models on task-specific settings even when compared to the largest models evaluated in an In-Context Learning setup - in our case LlaMA3.1-8b-Instruct, Mistral-Nemo-Instruct-2407 and Qwen2.5-7B-Instruct.

[Arxiv](https://arxiv.org/abs/2509.07768)