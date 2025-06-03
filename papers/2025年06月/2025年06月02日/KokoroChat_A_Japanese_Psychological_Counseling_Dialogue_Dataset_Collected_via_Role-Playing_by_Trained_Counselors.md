# KokoroChat：一个由专业咨询师通过角色扮演方式收集的日语心理咨询对话数据集

发布时间：2025年06月02日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）生成高质量的心理咨询服务回复，并通过创新性地采用角色扮演方法构建了一个高质量的日语心理咨询对话数据集KokoroChat。研究重点在于数据集的构建方法及其对LLM性能的提升，属于LLM在特定应用场景中的实际应用。` `心理咨询`

> KokoroChat: A Japanese Psychological Counseling Dialogue Dataset Collected via Role-Playing by Trained Counselors

# 摘要

> 语言模型生成心理咨询服务回复的效果，很大程度上依赖于高质量的数据集支持。传统的众包数据收集方式需要对采集人员进行严格培训，而直接使用真实咨询环境的数据又可能引发隐私和伦理问题。尽管近期有研究尝试利用大型语言模型（LLMs）来扩充心理咨询对话数据集，但生成的数据往往存在多样性和真实性的局限。为了解决这些问题，本研究创新性地采用角色扮演方法，由专业咨询师模拟咨询师与来访者的互动场景，既保证了对话质量，又有效降低了隐私泄露风险。基于此方法，我们开发了 KokoroChat 数据集，这是一个包含6589个长格式对话的日语心理咨询对话数据集，每个对话都配有完整的来访者反馈信息。实验结果显示，使用 KokoroChat 对开源 LLM 进行微调后，模型生成的咨询服务回复质量和对话自动评估效果均得到显著提升。该数据集已开源，可在 https://github.com/UEC-InabaLab/KokoroChat 获取。

> Generating psychological counseling responses with language models relies heavily on high-quality datasets. Crowdsourced data collection methods require strict worker training, and data from real-world counseling environments may raise privacy and ethical concerns. While recent studies have explored using large language models (LLMs) to augment psychological counseling dialogue datasets, the resulting data often suffers from limited diversity and authenticity. To address these limitations, this study adopts a role-playing approach where trained counselors simulate counselor-client interactions, ensuring high-quality dialogues while mitigating privacy risks. Using this method, we construct KokoroChat, a Japanese psychological counseling dialogue dataset comprising 6,589 long-form dialogues, each accompanied by comprehensive client feedback. Experimental results demonstrate that fine-tuning open-source LLMs with KokoroChat improves both the quality of generated counseling responses and the automatic evaluation of counseling dialogues. The KokoroChat dataset is available at https://github.com/UEC-InabaLab/KokoroChat.

[Arxiv](https://arxiv.org/abs/2506.01357)