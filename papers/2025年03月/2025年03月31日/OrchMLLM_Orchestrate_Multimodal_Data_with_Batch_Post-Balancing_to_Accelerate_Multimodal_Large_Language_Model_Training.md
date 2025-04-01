# OrchMLLM: 编排多模态数据，通过批量后平衡加速多模态大语言模型的训练

发布时间：2025年03月31日

`LLM应用` `人工智能` `数据科学`

> OrchMLLM: Orchestrate Multimodal Data with Batch Post-Balancing to Accelerate Multimodal Large Language Model Training

# 摘要

> 多模态大型语言模型（MLLMs）如GPT-4o引发了广泛关注。在MLLM训练探索过程中，我们发现了一种现象——模态组成不一致性，即某类模态的比例在不同样本间变化剧烈。这一现象加剧了处理小批量数据不平衡的难度，导致数据并行（DP）实例间的GPU利用率不均，严重影响了MLLM训练的效率和扩展性，进而影响训练速度，阻碍了对MLLMs的进一步研究。

为解决这些问题，我们推出了OrchMLLM，一个全面的框架，旨在缓解由模态组成不一致性导致的MLLM训练低效问题。首先，我们提出了Batch后平衡调度器，一种有效消除序列数据中小批量不平衡的技术。此外，我们将MLLM全局编排器集成到训练框架中，以编排多模态数据并解决模态组成不一致性带来的问题。我们在不同规模的MLLM上评估了OrchMLLM，证明了其高效性和扩展性。实验结果显示，当在2560块H100 GPU上训练包含三种模态的840亿参数MLLM时，OrchMLLM实现了【数学公式】的模型FLOPs利用率（MFU），在吞吐量上比Megatron-LM高出【数学公式】倍。


> Multimodal large language models (MLLMs), such as GPT-4o, are garnering significant attention. During the exploration of MLLM training, we identified Modality Composition Incoherence, a phenomenon that the proportion of a certain modality varies dramatically across different examples. It exacerbates the challenges of addressing mini-batch imbalances, which lead to uneven GPU utilization between Data Parallel (DP) instances and severely degrades the efficiency and scalability of MLLM training, ultimately affecting training speed and hindering further research on MLLMs.
  To address these challenges, we introduce OrchMLLM, a comprehensive framework designed to mitigate the inefficiencies in MLLM training caused by Modality Composition Incoherence. First, we propose Batch Post-Balancing Dispatcher, a technique that efficiently eliminates mini-batch imbalances in sequential data. Additionally, we integrate MLLM Global Orchestrator into the training framework to orchestrate multimodal data and tackle the issues arising from Modality Composition Incoherence. We evaluate OrchMLLM across various MLLM sizes, demonstrating its efficiency and scalability. Experimental results reveal that OrchMLLM achieves a Model FLOPs Utilization (MFU) of $41.6\%$ when training an 84B MLLM with three modalities on $2560$ H100 GPUs, outperforming Megatron-LM by up to $3.1\times$ in throughput.

[Arxiv](https://arxiv.org/abs/2503.23830)