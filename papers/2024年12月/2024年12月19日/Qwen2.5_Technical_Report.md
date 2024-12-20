# Qwen2.5 技术报告

发布时间：2024年12月19日

`LLM应用` `语言模型` `云计算`

> Qwen2.5 Technical Report

# 摘要

> 在本报告中，我们为您介绍 Qwen2.5，这是一组旨在满足多元需求的大型语言模型系列。相较于以往版本，Qwen 2.5 在预训练和后训练阶段均有显著提升。就预训练而言，我们把高质量预训练数据集从先前的 7 万亿个标记拓展至 18 万亿个标记，为常识、专家知识及推理能力筑牢根基。在后训练方面，我们借助超 100 万个样本开展了复杂的有监督微调，还进行了多阶段强化学习。后训练技术增进了人类偏好，大幅提升了长文本生成、结构数据分析及指令遵循能力。为有效应对形形色色的使用场景，我们推出了丰富规格的 Qwen2.5 LLM 系列。开放权重产品涵盖基础和指令调整模型，并提供量化版本。另外，对于托管解决方案，专有模型当下包含两个专家混合（MoE）变体：Qwen2.5-Turbo 和 Qwen2.5-Plus，均可从阿里云模型工作室获取。Qwen2.5 在评估语言理解、推理、数学、编码、人类偏好对齐等的众多基准测试中展现出顶尖性能。具体来讲，开放权重旗舰产品 Qwen2.5-72B-Instruct 胜过众多开放和专有模型，与最先进的开放权重模型 Llama-3-405B-Instruct（约为其 5 倍规模）相比也不遑多让。Qwen2.5-Turbo 和 Qwen2.5-Plus 在分别与 GPT-4o-mini 和 GPT-4o 竞争时，具备出色的成本效益。此外，作为基石，Qwen2.5 模型在训练诸如 Qwen2.5-Math、Qwen2.5-Coder、QwQ 及多模态模型等专业模型时发挥了关键作用。

> In this report, we introduce Qwen2.5, a comprehensive series of large language models (LLMs) designed to meet diverse needs. Compared to previous iterations, Qwen 2.5 has been significantly improved during both the pre-training and post-training stages. In terms of pre-training, we have scaled the high-quality pre-training datasets from the previous 7 trillion tokens to 18 trillion tokens. This provides a strong foundation for common sense, expert knowledge, and reasoning capabilities. In terms of post-training, we implement intricate supervised finetuning with over 1 million samples, as well as multistage reinforcement learning. Post-training techniques enhance human preference, and notably improve long text generation, structural data analysis, and instruction following. To handle diverse and varied use cases effectively, we present Qwen2.5 LLM series in rich sizes. Open-weight offerings include base and instruction-tuned models, with quantized versions available. In addition, for hosted solutions, the proprietary models currently include two mixture-of-experts (MoE) variants: Qwen2.5-Turbo and Qwen2.5-Plus, both available from Alibaba Cloud Model Studio. Qwen2.5 has demonstrated top-tier performance on a wide range of benchmarks evaluating language understanding, reasoning, mathematics, coding, human preference alignment, etc. Specifically, the open-weight flagship Qwen2.5-72B-Instruct outperforms a number of open and proprietary models and demonstrates competitive performance to the state-of-the-art open-weight model, Llama-3-405B-Instruct, which is around 5 times larger. Qwen2.5-Turbo and Qwen2.5-Plus offer superior cost-effectiveness while performing competitively against GPT-4o-mini and GPT-4o respectively. Additionally, as the foundation, Qwen2.5 models have been instrumental in training specialized models such as Qwen2.5-Math, Qwen2.5-Coder, QwQ, and multimodal models.

[Arxiv](https://arxiv.org/abs/2412.15115)