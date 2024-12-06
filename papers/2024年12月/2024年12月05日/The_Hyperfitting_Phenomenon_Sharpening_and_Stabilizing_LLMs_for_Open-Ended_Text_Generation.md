# 《超拟合现象：让大型语言模型在开放式文本生成中更锐利和稳定》

发布时间：2024年12月05日

`LLM应用` `人工智能`

> The Hyperfitting Phenomenon: Sharpening and Stabilizing LLMs for Open-Ended Text Generation

# 摘要

> 这篇论文介绍了在极小数据集上对预训练大型语言模型（LLMs）过度拟合所产生的反直觉泛化结果。在开放式文本生成场景中，有明确记载显示，LLMs 倾向生成重复、枯燥的序列，使用贪心解码生成时此现象尤为突出。即便最先进、含数十亿参数且通过在大型数据集上进行下一个标记预测训练的 LLMs，这一问题仍存在。我们发现，进一步微调这些模型，使其在少量样本上达到近乎零的训练损失——我们称此过程为超拟合——长序列生成能力会大幅增强。这些超拟合模型的贪心解码在长序列上甚至比 Top-P 采样表现更优，无论在多样性还是人类偏好方面。此现象适用于各种规模的 LLMs、不同领域，甚至自回归图像生成。我们还发现，该现象与 Grokking 和双重下降显著不同。令人惊讶的是，我们的实验表明，超拟合模型很少陷入其训练过的重复序列，即便明确阻止这些序列，也能产出高质量的结果。所有超拟合模型都会产生极低熵的预测，通常几乎将所有概率都分配给单个标记。

> This paper introduces the counter-intuitive generalization results of overfitting pre-trained large language models (LLMs) on very small datasets. In the setting of open-ended text generation, it is well-documented that LLMs tend to generate repetitive and dull sequences, a phenomenon that is especially apparent when generating using greedy decoding. This issue persists even with state-of-the-art LLMs containing billions of parameters, trained via next-token prediction on large datasets. We find that by further fine-tuning these models to achieve a near-zero training loss on a small set of samples -- a process we refer to as hyperfitting -- the long-sequence generative capabilities are greatly enhanced. Greedy decoding with these Hyperfitted models even outperform Top-P sampling over long-sequences, both in terms of diversity and human preferences. This phenomenon extends to LLMs of various sizes, different domains, and even autoregressive image generation. We further find this phenomena to be distinctly different from that of Grokking and double descent. Surprisingly, our experiments indicate that hyperfitted models rarely fall into repeating sequences they were trained on, and even explicitly blocking these sequences results in high-quality output. All hyperfitted models produce extremely low-entropy predictions, often allocating nearly all probability to a single token.

[Arxiv](https://arxiv.org/abs/2412.04318)