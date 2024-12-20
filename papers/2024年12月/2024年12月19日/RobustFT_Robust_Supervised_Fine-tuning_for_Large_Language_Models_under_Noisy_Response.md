# RobustFT：针对大型语言模型在噪声响应下的稳健监督微调

发布时间：2024年12月19日

`LLM应用` `语言模型` `数据处理`

> RobustFT: Robust Supervised Fine-tuning for Large Language Models under Noisy Response

# 摘要

> 监督微调（SFT）对于让大型语言模型（LLMs）适配特定领域或任务至关重要。然而，实证实验显示，实际应用中收集的数据必然含噪，这给下游任务的模型性能带来巨大挑战。所以，当下迫切需要一个抗噪的 SFT 框架来提升下游任务中的模型能力。为应对此挑战，我们推出了一个强大的 SFT 框架（RobustFT），它能对下游任务数据进行噪声检测与重新标注。在噪声识别方面，我们的方法采用具备推理增强模型的多专家协作系统，实现出色的噪声检测。在去噪阶段，我们运用一种上下文增强策略，融合最相关且最可信的知识，再经仔细评估生成可靠的标注。另外，我们引入基于响应熵的有效数据选择机制，确保只保留高质量样本用于微调。在五个数据集上针对多个 LLMs 开展的大量实验表明，RobustFT 在噪声场景中表现卓越。

> Supervised fine-tuning (SFT) plays a crucial role in adapting large language models (LLMs) to specific domains or tasks. However, as demonstrated by empirical experiments, the collected data inevitably contains noise in practical applications, which poses significant challenges to model performance on downstream tasks. Therefore, there is an urgent need for a noise-robust SFT framework to enhance model capabilities in downstream tasks. To address this challenge, we introduce a robust SFT framework (RobustFT) that performs noise detection and relabeling on downstream task data. For noise identification, our approach employs a multi-expert collaborative system with inference-enhanced models to achieve superior noise detection. In the denoising phase, we utilize a context-enhanced strategy, which incorporates the most relevant and confident knowledge followed by careful assessment to generate reliable annotations. Additionally, we introduce an effective data selection mechanism based on response entropy, ensuring only high-quality samples are retained for fine-tuning. Extensive experiments conducted on multiple LLMs across five datasets demonstrate RobustFT's exceptional performance in noisy scenarios.

[Arxiv](https://arxiv.org/abs/2412.14922)