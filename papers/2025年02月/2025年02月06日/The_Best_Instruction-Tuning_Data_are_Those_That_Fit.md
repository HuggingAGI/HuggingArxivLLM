# 最适合的指令调优数据才是最好的

发布时间：2025年02月06日

`LLM应用

理由：这篇论文主要讨论了如何通过优化监督微调（SFT）数据来提高预训练大型语言模型（LLMs）的性能。具体来说，论文提出了一个名为GRAPE的框架，该框架通过选择与目标模型预训练分布最接近的响应来进行微调。这种方法直接应用于LLMs的微调过程，属于LLM应用的范畴。` `机器学习`

> The Best Instruction-Tuning Data are Those That Fit

# 摘要

> # 摘要
高质量的监督微调（SFT）数据对于激发预训练大型语言模型（LLMs）的潜力至关重要。通常，指令会与其他LLMs生成的多个响应配对，但这些响应往往偏离目标模型的分布范围，可能导致收益递减甚至损害模型性能。我们提出了**GRAPE**，一种新颖的SFT框架，它针对目标模型的特性进行优化。对于每个指令，GRAPE从多个LLMs中收集响应，并选择与目标模型预训练分布最接近的响应，随后进行标准SFT训练。
我们通过对照实验评估GRAPE，从多个模型中为UltraInteract的每个问题采样解决方案，并在GRAPE选择的数据上微调LLaMA3.1-8B、Mistral-7B和Qwen2.5-7B等常用模型。GRAPE显著优于强基线，包括从最强模型蒸馏的绝对增益高达13.8%，在基准测试中平均增益，以及在3倍数据上训练的最大性能提升17.3%。GRAPE的强大性能在现实环境中也得到了验证。我们实验了用于Tulu3和Olmo-2的后期训练数据，GRAPE在4.5倍数据上训练的强基线上平均性能提升了6.1%，并比最先进的数据选择方法平均性能提升了3%。值得注意的是，使用1/3的数据和一半的epoch数，GRAPE使LLaMA3.1-8B的性能超过了Tulu3-SFT 3.5%。

> High-quality supervised fine-tuning (SFT) data are crucial for eliciting strong capabilities from pretrained large language models (LLMs). Typically, instructions are paired with multiple responses sampled from other LLMs, which are often out of the distribution of the target model to be fine-tuned. This, at scale, can lead to diminishing returns and even hurt the models' performance and robustness. We propose **GRAPE**, a novel SFT framework that accounts for the unique characteristics of the target model. For each instruction, it gathers responses from various LLMs and selects the one with the highest probability measured by the target model, indicating that it aligns most closely with the target model's pretrained distribution; it then proceeds with standard SFT training.
  We first evaluate GRAPE with a controlled experiment, where we sample various solutions for each question in UltraInteract from multiple models and fine-tune commonly used LMs like LLaMA3.1-8B, Mistral-7B, and Qwen2.5-7B on GRAPE-selected data. GRAPE significantly outperforms strong baselines, including distilling from the strongest model with an absolute gain of up to 13.8%, averaged across benchmarks, and training on 3x more data with a maximum performance improvement of 17.3%. GRAPE's strong performance generalizes to realistic settings. We experiment with the post-training data used for Tulu3 and Olmo-2. GRAPE outperforms strong baselines trained on 4.5 times more data by 6.1% and a state-of-the-art data selection approach by 3% on average performance. Remarkably, using 1/3 of the data and half the number of epochs, GRAPE enables LLaMA3.1-8B to surpass the performance of Tulu3-SFT by 3.5%.

[Arxiv](https://arxiv.org/abs/2502.04194)