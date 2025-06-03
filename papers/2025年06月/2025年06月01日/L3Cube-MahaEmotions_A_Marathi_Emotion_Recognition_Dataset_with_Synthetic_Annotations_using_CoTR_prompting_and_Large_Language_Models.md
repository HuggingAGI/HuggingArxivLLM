# L3Cube-MahaEmotions: 一个基于CoTR提示学习和大语言模型进行合成标注的马拉地情感识别数据集

发布时间：2025年06月01日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）进行情绪识别，特别是在资源匮乏的语言如马拉地语中。研究中使用了LLMs进行数据标注和情绪分类，并评估了不同模型的表现。这属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `情绪识别`

> L3Cube-MahaEmotions: A Marathi Emotion Recognition Dataset with Synthetic Annotations using CoTR prompting and Large Language Models

# 摘要

> 在资源匮乏的语言如马拉地语中，情绪识别仍然面临挑战，这主要是由于标注数据的缺乏。我们提出了L3Cube-MahaEmotions，一个高质量的马拉地语情绪识别数据集，包含11种细致的情绪标签。训练数据是通过大型语言模型（LLMs）进行合成标注，而验证集和测试集则是人工标注，以作为可靠的黄金标准基准。基于MahaSent数据集，我们应用了翻译链（CoTR）提示技术，其中马拉地语句子被翻译成英语并通过单个提示进行情绪标注。评估了GPT-4和Llama3-405B，最终选择GPT-4用于训练数据标注，因其标注质量更优。我们采用标准指标评估模型性能，并探索了标签聚合策略（如联合、交集）。尽管GPT-4的预测优于微调的BERT模型，但基于BERT的模型在合成标签上的训练未能超越GPT-4。这凸显了高质量人工标注数据的重要性以及情绪识别的内在复杂性。这项研究的重要发现是，像GPT-4和Llama3-405B这样的通用LLMs在复杂低资源情绪识别任务上比微调后的BERT模型具有更好的泛化能力。该数据集和模型已公开分享在https://github.com/l3cube-pune/MarathiNLP

> Emotion recognition in low-resource languages like Marathi remains challenging due to limited annotated data. We present L3Cube-MahaEmotions, a high-quality Marathi emotion recognition dataset with 11 fine-grained emotion labels. The training data is synthetically annotated using large language models (LLMs), while the validation and test sets are manually labeled to serve as a reliable gold-standard benchmark. Building on the MahaSent dataset, we apply the Chain-of-Translation (CoTR) prompting technique, where Marathi sentences are translated into English and emotion labeled via a single prompt. GPT-4 and Llama3-405B were evaluated, with GPT-4 selected for training data annotation due to superior label quality. We evaluate model performance using standard metrics and explore label aggregation strategies (e.g., Union, Intersection). While GPT-4 predictions outperform fine-tuned BERT models, BERT-based models trained on synthetic labels fail to surpass GPT-4. This highlights both the importance of high-quality human-labeled data and the inherent complexity of emotion recognition. An important finding of this work is that generic LLMs like GPT-4 and Llama3-405B generalize better than fine-tuned BERT for complex low-resource emotion recognition tasks. The dataset and model are shared publicly at https://github.com/l3cube-pune/MarathiNLP

[Arxiv](https://arxiv.org/abs/2506.00863)