# # 无需外部指导的多语言模型微调后门清理

发布时间：2025年05月22日

`LLM应用` `多模态`

> Backdoor Cleaning without External Guidance in MLLM Fine-tuning

# 摘要

> 多模态大型语言模型 (MLLMs) 在微调即服务 (FTaaS) 场景中得到广泛应用，用户通过提交数据集对通用模型进行微调以适应具体任务。然而，这种灵活性却暗藏风险——恶意微调只需极少 effort 就能在 MLLMs 中植入后门。我们的研究发现，后门触发器会系统性地破坏跨模态处理，导致注意力集中在非语义区域，这一现象我们称之为“注意力坍塌”。基于这一发现，我们提出了一种名为“相信你的眼睛”(BYE) 的数据过滤框架。该框架利用注意力熵模式作为自监督信号，精准识别并过滤后门样本。BYE 通过三阶段流程实现：首先，使用微调模型提取注意力图；其次，通过双模态分离计算熵分数并分析敏感层；最后，进行无监督聚类以移除可疑样本。与传统防御方法不同，BYE 无需干净的监督信号、辅助标签或模型修改。实验结果表明，BYE 在多种数据集、模型和触发类型上均表现出色：它将攻击成功率降至近乎零，同时保持正常任务性能，为 MLLMs 中的后门威胁提供了一个 robust 且通用的解决方案。

> Multimodal Large Language Models (MLLMs) are increasingly deployed in fine-tuning-as-a-service (FTaaS) settings, where user-submitted datasets adapt general-purpose models to downstream tasks. This flexibility, however, introduces serious security risks, as malicious fine-tuning can implant backdoors into MLLMs with minimal effort. In this paper, we observe that backdoor triggers systematically disrupt cross-modal processing by causing abnormal attention concentration on non-semantic regions--a phenomenon we term attention collapse. Based on this insight, we propose Believe Your Eyes (BYE), a data filtering framework that leverages attention entropy patterns as self-supervised signals to identify and filter backdoor samples. BYE operates via a three-stage pipeline: (1) extracting attention maps using the fine-tuned model, (2) computing entropy scores and profiling sensitive layers via bimodal separation, and (3) performing unsupervised clustering to remove suspicious samples. Unlike prior defenses, BYE equires no clean supervision, auxiliary labels, or model modifications. Extensive experiments across various datasets, models, and diverse trigger types validate BYE's effectiveness: it achieves near-zero attack success rates while maintaining clean-task performance, offering a robust and generalizable solution against backdoor threats in MLLMs.

[Arxiv](https://arxiv.org/abs/2505.16916)