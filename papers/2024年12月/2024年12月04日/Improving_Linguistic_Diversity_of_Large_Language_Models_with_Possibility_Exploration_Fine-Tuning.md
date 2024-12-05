# 利用可能性探索微调提升大型语言模型的语言多样性

发布时间：2024年12月04日

`LLM应用` `聊天机器人` `虚拟助手`

> Improving Linguistic Diversity of Large Language Models with Possibility Exploration Fine-Tuning

# 摘要

> 虽然大型语言模型（LLMs）在模仿人类能力方面取得了显著进步，但存在其输出语言多样性降低的担忧。这致使观点和视角趋同，特定人群的代表性也不足。尽管已提出若干微调及提示技术来应对此问题，可它们通常针对特定任务，或者会大幅增加计算成本与延迟。这让它们难以应用于对延迟要求极低的应用，比如聊天机器人和虚拟助手。我们提出了可能性探索微调（PEFT），这是一个不受任务限制的框架，能够在不增加延迟和计算成本的情况下增强LLMs的文本多样性。给定相同的提示，经PEFT微调的模型能够同时生成多个不同的响应，每个响应都对应一个可控的可能性数值。在对话和故事生成任务中的实验表明，PEFT显著提升了LLM输出的多样性，候选响应之间较低的相似度可作为证明。由于PEFT更注重语义多样性而非词汇多样性，它还能显著减少对话系统中的人口偏差。相关实现和数据集可在我们的存储库获取：https://github.com/mailong25/peft_diversity

> While Large Language Models (LLMs) have made significant strides in replicating human-like abilities, there are concerns about a reduction in the linguistic diversity of their outputs. This results in the homogenization of viewpoints and perspectives, as well as the underrepresentation of specific demographic groups. Although several fine-tuning and prompting techniques have been suggested to tackle the issue, they are often tailored to specific tasks or come with a substantial increase in computational cost and latency. This makes them challenging to apply to applications that demand very low latency, such as chatbots and virtual assistants. We propose Possibility Exploration Fine-Tuning (PEFT), a task-agnostic framework that enhances the text diversity of LLMs without increasing latency or computational cost. Given the same prompt, models fine-tuned with PEFT can simultaneously generate multiple diverse responses, each corresponding with a controllable possibility number. Experiments on dialogue and story generation tasks demonstrate that PEFT significantly enhances the diversity of LLM outputs, as evidenced by lower similarity between candidate responses. Since PEFT emphasizes semantic diversity over lexical diversity, it can also notably reduce demographic bias in dialogue systems. The implementations and datasets are available in our repository: https://github.com/mailong25/peft_diversity

[Arxiv](https://arxiv.org/abs/2412.03343)