# 借助大型语言模型，运用链式思维推理解决孟加拉语数学应用题

发布时间：2025年05月27日

`LLM应用`

> Leveraging Large Language Models for Bengali Math Word Problem Solving with Chain of Thought Reasoning

# 摘要

> 孟加拉语数学单词问题（MWPs）的解决一直是自然语言处理（NLP）中的重大挑战，这主要由于孟加拉语的资源匮乏以及需要复杂的多步骤推理。现有模型难以应对复杂的孟加拉语MWPs，主要是因为此前没有人类标注的孟加拉语数据集专门针对这一任务。这一空白限制了孟加拉语数学推理的发展。为了解决这一问题，我们开发了SOMADHAN，这是一个包含8792个复杂孟加拉语MWPs的数据集，每个问题都附有手动编写的分步解答。我们设计这个数据集旨在支持在语言代表性不足的背景下进行推理聚焦的评估和模型开发。利用SOMADHAN，我们对多种大型语言模型（LLMs）——包括GPT-4o、GPT-3.5 Turbo、LLaMA系列模型、Deepseek和Qwen——进行了评估，采用零样本和少样本提示，同时测试了有无Chain of Thought（CoT）推理的情况。结果显示，CoT提示在需要多步逻辑的任务中显著提升了模型性能。其中，LLaMA-3.3 70B在少样本CoT提示下达到了最高的88%准确率。此外，我们还应用了低秩适应（LoRA）技术，以高效微调模型，使其能够以极低的计算成本适应孟加拉语MWPs。我们的工作通过提供高质量的推理数据集和解决复杂MWPs的可扩展框架，填补了孟加拉语NLP领域中的关键空白。我们致力于推动低资源语言的公平研究，并在教育和语言技术领域提升推理能力。

> Solving Bengali Math Word Problems (MWPs) remains a major challenge in natural language processing (NLP) due to the language's low-resource status and the multi-step reasoning required. Existing models struggle with complex Bengali MWPs, largely because no human-annotated Bengali dataset has previously addressed this task. This gap has limited progress in Bengali mathematical reasoning. To address this, we created SOMADHAN, a dataset of 8792 complex Bengali MWPs with manually written, step-by-step solutions. We designed this dataset to support reasoning-focused evaluation and model development in a linguistically underrepresented context. Using SOMADHAN, we evaluated a range of large language models (LLMs) - including GPT-4o, GPT-3.5 Turbo, LLaMA series models, Deepseek, and Qwen - through both zero-shot and few-shot prompting with and without Chain of Thought (CoT) reasoning. CoT prompting consistently improved performance over standard prompting, especially in tasks requiring multi-step logic. LLaMA-3.3 70B achieved the highest accuracy of 88% with few-shot CoT prompting. We also applied Low-Rank Adaptation (LoRA) to fine-tune models efficiently, enabling them to adapt to Bengali MWPs with minimal computational cost. Our work fills a critical gap in Bengali NLP by providing a high-quality reasoning dataset and a scalable framework for solving complex MWPs. We aim to advance equitable research in low-resource languages and enhance reasoning capabilities in educational and language technologies.

[Arxiv](https://arxiv.org/abs/2505.21354)