# 探索 GPT 在音乐理解中的评判能力

发布时间：2025年01月22日

`LLM应用

**理由**：这篇论文探讨了如何利用大型语言模型（LLMs）解决音乐信息检索（MIR）中的具体任务，如节拍跟踪、和弦提取和调性估计。论文通过将音乐数据转化为符号输入，并评估LLMs在这些任务中的表现，展示了LLMs在实际应用中的潜力。因此，这篇论文属于LLM应用类别。` `信息检索`

> Exploring GPT's Ability as a Judge in Music Understanding

# 摘要

> # 摘要
近期，基于文本的大型语言模型（LLMs）及其处理多模态感官数据的能力取得了显著进展，这促使我们探索其在音乐信息检索（MIR）中的应用。本文采用系统的提示工程方法，利用LLMs解决MIR问题。我们将音乐数据转化为符号输入，并评估LLMs在节拍跟踪、和弦提取及调性估计等关键MIR任务中检测注释错误的能力。此外，我们提出了一种概念增强方法，用于评估LLMs在提示中提供的音乐概念下的音乐推理一致性。实验测试了生成预训练变换器（GPT）的MIR能力，结果显示，GPT在节拍跟踪、和弦提取和调性估计任务中的错误检测准确率分别为65.20%、64.80%和59.72%，均显著高于随机基线。我们还发现，GPT的错误发现准确率与提供的概念信息量呈正相关。这些基于符号音乐输入的发现为未来基于LLM的MIR研究奠定了坚实基础。

> Recent progress in text-based Large Language Models (LLMs) and their extended ability to process multi-modal sensory data have led us to explore their applicability in addressing music information retrieval (MIR) challenges. In this paper, we use a systematic prompt engineering approach for LLMs to solve MIR problems. We convert the music data to symbolic inputs and evaluate LLMs' ability in detecting annotation errors in three key MIR tasks: beat tracking, chord extraction, and key estimation. A concept augmentation method is proposed to evaluate LLMs' music reasoning consistency with the provided music concepts in the prompts. Our experiments tested the MIR capabilities of Generative Pre-trained Transformers (GPT). Results show that GPT has an error detection accuracy of 65.20%, 64.80%, and 59.72% in beat tracking, chord extraction, and key estimation tasks, respectively, all exceeding the random baseline. Moreover, we observe a positive correlation between GPT's error finding accuracy and the amount of concept information provided. The current findings based on symbolic music input provide a solid ground for future LLM-based MIR research.

[Arxiv](https://arxiv.org/abs/2501.13261)