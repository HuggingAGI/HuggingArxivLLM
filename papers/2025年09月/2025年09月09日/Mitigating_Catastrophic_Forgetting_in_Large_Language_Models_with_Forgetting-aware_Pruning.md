# 通过感知遗忘剪枝缓解大型语言模型的灾难性遗忘

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Mitigating Catastrophic Forgetting in Large Language Models with Forgetting-aware Pruning

# 摘要

> 大型语言模型（LLMs）近年来在各类下游任务中展现出惊人能力，但微调时往往遭遇灾难性遗忘（CF）难题。为此，我们提出遗忘感知剪枝度量（FAPM）——一种基于剪枝的创新方法，旨在平衡CF与下游任务性能。研究发现，任务向量（即下游任务微调权重与预训练权重的差值）与预训练模型参数的重叠程度是影响CF的关键因素。基于此，FAPM将任务向量与预训练参数的比值作为CF量化指标，并将该指标融入剪枝标准。值得注意的是，FAPM无需修改训练流程或模型架构，也不依赖任何辅助数据。我们在八个数据集上开展了大量实验，涵盖自然语言推理、通用问答、医疗问答、数学问答、阅读理解及完形填空等任务。结果显示，FAPM将CF控制在仅0.25%，同时下游任务准确率保持99.67%。我们已开源实验复现代码。

> Recent advancements in large language models (LLMs) have shown impressive capabilities in various downstream tasks but typically face Catastrophic Forgetting (CF) during fine-tuning. In this paper, we propose the Forgetting-Aware Pruning Metric (FAPM), a novel pruning-based approach to balance CF and downstream task performance. Our investigation reveals that the degree to which task vectors (i.e., the subtraction of pre-trained weights from the weights fine-tuned on downstream tasks) overlap with pre-trained model parameters is a critical factor for CF. Based on this finding, FAPM employs the ratio of the task vector to pre-trained model parameters as a metric to quantify CF, integrating this measure into the pruning criteria. Importantly, FAPM does not necessitate modifications to the training process or model architecture, nor does it require any auxiliary data. We conducted extensive experiments across eight datasets, covering natural language inference, General Q&A, Medical Q&A, Math Q&A, reading comprehension, and cloze tests. The results demonstrate that FAPM limits CF to just 0.25\% while maintaining 99.67\% accuracy on downstream tasks. We provide the code to reproduce our results.

[Arxiv](https://arxiv.org/abs/2509.08255)