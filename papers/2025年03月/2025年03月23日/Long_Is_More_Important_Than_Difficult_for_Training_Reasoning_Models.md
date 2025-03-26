# 长文本比高难度更重要：训练推理模型时，文本长度的影响比难度更大

发布时间：2025年03月23日

`LLM应用` `问答系统`

> Long Is More Important Than Difficult for Training Reasoning Models

# 摘要

> 困难问题通常伴随着长推理链，被广泛认为是提升推理模型性能的关键因素。然而，这类高难度问题十分稀缺，导致可用数据集的规模受限。本文提出了一种简单的方法来降低对问题难度的依赖。首先，我们实证研究证明，推理长度而非问题难度是影响训练模型性能的主要因素。其次，我们发现了一个关于推理长度的扩展规律，表明随着推理数据长度的增加，模型性能以对数线性的方式提升。最后，我们提出了一种生成任意长度推理数据的简单方法，并证明合成数据对训练推理模型的有效性。在我们的 Long1K 数据集上微调 Qwen2.5-32B-Instruct 语言模型后，我们推出了 Long1K-32B 模型。该模型仅使用 1,000 个训练样本就达到了令人瞩目的性能水平，在 MATH 数据集上达到了 95.6% 的准确率，在 GPQA 数据集上达到了 71.1% 的准确率，超越了 DeepSeek-R1-Distill-Qwen-32B。模型、代码和数据集均已开源，可在 https://huggingface.co/ZTss/LONG1 获取。

> Difficult problems, which often result in long reasoning traces, are widely recognized as key factors for enhancing the performance of reasoning models. However, such high-challenge problems are scarce, limiting the size of available datasets. In this paper, we propose a simple method to decouple the reliance on problem difficulty. First, we empirically demonstrate that reasoning length, rather than problem difficulty, primarily influences the performance of trained models. Second, we identify a scaling law on reasoning length, showing that model performance increases in a log-linear fashion as the reasoning data length grows. Finally, we introduce a straightforward technique to generate reasoning data of arbitrary length, and show that synthesized data is effective for training reasoning models. After fine-tuning the Qwen2.5-32B-Instruct language model on our Long1K dataset, we present our model, Long1K-32B, which achieves remarkable performance with only 1,000 training samples, achieving 95.6\% accuracy on MATH, and 71.1\% on GPQA outperforming DeepSeek-R1-Distill-Qwen-32B. The model, code, and dataset are all open-sourced, available at https://huggingface.co/ZTss/LONG1.

[Arxiv](https://arxiv.org/abs/2503.18069)