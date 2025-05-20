# SLOT：测试时的样本定制语言模型优化

发布时间：2025年05月18日

`LLM应用` `人工智能`

> SLOT: Sample-specific Language Model Optimization at Test-time

# 摘要

> 我们提出了一种名为SLOT的创新方法，它是一种参数高效的测试时推理技术，旨在让语言模型更精准地响应每个特定提示。当前的大型语言模型（LLMs）在处理复杂指令时往往表现欠佳，尤其是在面对未被充分代表的样本时。为了解决这一问题，SLOT通过在测试时进行少量优化，更新一个轻量化的样本特定参数向量。该向量被添加到输出层前的最终隐藏层，并通过缓存每样本优化过程中的最后一层特征实现高效适应。通过仅最小化输入提示的交叉熵损失，SLOT使模型更好地与每个给定指令对齐并遵循其指示。实验结果表明，SLOT在多个基准测试和大型语言模型上均优于对比方法。例如，配备SLOT的Qwen2.5-7B在GSM8K上的准确率提升了8.6%，从57.54%跃升至66.19%。同时，配备SLOT的DeepSeek-R1-Distill-Llama-70B在GPQA上达到了70B级别模型中的最先进准确率68.69%。我们的代码可在GitHub上获取：https://github.com/maple-research-lab/SLOT。

> We propose SLOT (Sample-specific Language Model Optimization at Test-time), a novel and parameter-efficient test-time inference approach that enhances a language model's ability to more accurately respond to individual prompts. Existing Large Language Models (LLMs) often struggle with complex instructions, leading to poor performances on those not well represented among general samples. To address this, SLOT conducts few optimization steps at test-time to update a light-weight sample-specific parameter vector. It is added to the final hidden layer before the output head, and enables efficient adaptation by caching the last layer features during per-sample optimization. By minimizing the cross-entropy loss on the input prompt only, SLOT helps the model better aligned with and follow each given instruction. In experiments, we demonstrate that our method outperforms the compared models across multiple benchmarks and LLMs. For example, Qwen2.5-7B with SLOT achieves an accuracy gain of 8.6% on GSM8K from 57.54% to 66.19%, while DeepSeek-R1-Distill-Llama-70B with SLOT achieves a SOTA accuracy of 68.69% on GPQA among 70B-level models. Our code is available at https://github.com/maple-research-lab/SLOT.

[Arxiv](https://arxiv.org/abs/2505.12392)