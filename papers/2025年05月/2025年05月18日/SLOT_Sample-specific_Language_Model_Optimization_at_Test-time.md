# SLOT: 测试时样本特定的语言模型优化

发布时间：2025年05月18日

`LLM应用

理由：这篇论文提出了一种新的测试时推理方法SLOT，专注于优化大型语言模型对个体提示的响应。它通过在测试时进行参数更新，提升模型的准确性，属于实际应用层面的改进，因此归类为LLM应用。` `基准测试`

> SLOT: Sample-specific Language Model Optimization at Test-time

# 摘要

> 我们提出了一种名为SLOT（基于测试时的样本特定语言模型优化）的新颖且参数高效的测试时推理方法，旨在提升语言模型对个体提示的响应准确性。现有的大型语言模型（LLMs）在处理复杂指令时常常表现不佳，导致在未被良好表示的通用样本上效果欠佳。为解决这一问题，SLOT在测试时执行少量优化步骤，更新一个轻量级的样本特定参数向量。该向量被添加到输出层之前的最后一层隐藏层，并通过缓存每样本优化过程中的最后一层特征，实现高效适应。通过仅最小化输入提示的交叉熵损失，SLOT帮助模型更好地与每个给定指令对齐并遵循。实验中，我们展示了该方法在多个基准测试和LLMs上优于对比模型。例如，配备SLOT的Qwen2.5-7B在GSM8K上的准确率从57.54%提升至66.19%，而配备SLOT的DeepSeek-R1-Distill-Llama-70B在GPQA上达到了70B级别模型的最优准确率68.69%。我们的代码可在https://github.com/maple-research-lab/SLOT获取。

> We propose SLOT (Sample-specific Language Model Optimization at Test-time), a novel and parameter-efficient test-time inference approach that enhances a language model's ability to more accurately respond to individual prompts. Existing Large Language Models (LLMs) often struggle with complex instructions, leading to poor performances on those not well represented among general samples. To address this, SLOT conducts few optimization steps at test-time to update a light-weight sample-specific parameter vector. It is added to the final hidden layer before the output head, and enables efficient adaptation by caching the last layer features during per-sample optimization. By minimizing the cross-entropy loss on the input prompt only, SLOT helps the model better aligned with and follow each given instruction. In experiments, we demonstrate that our method outperforms the compared models across multiple benchmarks and LLMs. For example, Qwen2.5-7B with SLOT achieves an accuracy gain of 8.6% on GSM8K from 57.54% to 66.19%, while DeepSeek-R1-Distill-Llama-70B with SLOT achieves a SOTA accuracy of 68.69% on GPQA among 70B-level models. Our code is available at https://github.com/maple-research-lab/SLOT.

[Arxiv](https://arxiv.org/abs/2505.12392)