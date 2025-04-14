# SEAL：针对大型语言模型的可调节推理校准（免费）

发布时间：2025年04月06日

`LLM理论` `人工智能` `大型语言模型`

> SEAL: Steerable Reasoning Calibration of Large Language Models for Free

# 摘要

> 大型语言模型（LLMs）如OpenAI的o1系列，凭借扩展的思维链（CoT）推理机制，在复杂推理任务中表现卓越。然而，近期研究揭示，CoT推理过程中存在显著冗余，这不仅增加了推理延迟，还通过将注意力转向不必要的推理路径对模型性能产生了负面影响。为了解决这一问题，我们深入研究了LLMs的内部推理结构，并将其主要划分为三种思维类型：执行思维、反思思维和过渡思维。研究发现，过多的反思思维和过渡思维与失败案例密切相关，且这些思维类别在潜在空间中具有清晰的分离。基于此，我们提出了SEAL（可引导推理校准），这是一种无需训练的方法，能够无缝校准CoT过程，提升准确率的同时显著提高效率。SEAL由两个阶段组成：首先在离线阶段提取潜在空间中的推理引导向量，然后通过表示干预使用引导向量实时校准推理轨迹。值得注意的是，引导向量在不同任务间展现出强大的可迁移性。我们在多个模型（DeepSeek-R1-Distill和QwQ-32B-Preview）和基准测试（Math500、GSM8K、LiveCodeBench）上进行了广泛实验，验证了SEAL的有效性，准确率提升了高达11%，同时推理标记减少了11.8%至50.4%。我们的代码已公开发布在https://github.com/VITA-Group/SEAL。


> Large Language Models (LLMs), such as OpenAI's o1-series have demonstrated compelling capabilities for complex reasoning tasks via the extended chain-of-thought (CoT) reasoning mechanism. However, recent studies reveal substantial redundancy in the CoT reasoning traces, which not only increases inference latency but also negatively impacts model performance by diverting attention to unnecessary reasoning paths. To address this issue, we investigate the internal reasoning structures of LLMs and categorize them into three primary thought types: execution, reflection, and transition thoughts. Moreover, our analysis reveals that excessive reflection and transition thoughts are strongly correlated with failure cases and these thought categories exhibit clear separation in the latent space. Based on these, we introduce SEAL (Steerable reasoning calibration), a training-free approach that seamlessly calibrates the CoT process, improving accuracy while demonstrating significant efficiency gains. SEAL consists of an offline stage for extracting the reasoning steering vector in the latent space, followed by an on-the-fly calibration of the reasoning trace through representation intervention using the steering vector. Notably, the steering vector exhibits strong transferability across various tasks. Extensive experiments across multiple models (DeepSeek-R1-Distill and QwQ-32B-Preview) and benchmarks (Math500, GSM8K, LiveCodeBench) validate the effectiveness of SEAL, up to a 11% improvement in accuracy while reducing reasoning tokens by 11.8% to 50.4%. Our code is publicly available at https://github.com/VITA-Group/SEAL.

[Arxiv](https://arxiv.org/abs/2504.07986)