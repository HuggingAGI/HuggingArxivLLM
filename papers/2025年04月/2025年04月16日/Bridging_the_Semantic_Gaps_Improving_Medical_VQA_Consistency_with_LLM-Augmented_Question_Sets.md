# 跨越语义鸿沟：借助LLM增强型问题集优化医学VQA一致性

发布时间：2025年04月16日

`LLM应用` `问答系统`

> Bridging the Semantic Gaps: Improving Medical VQA Consistency with LLM-Augmented Question Sets

# 摘要

> 医学视觉问答 (MVQA) 系统能够通过自然语言查询解读医学图像。然而，问题表述中的语言变异性常常影响了这些系统的稳定性。为了解决这一问题，我们提出了一种语义等效问题增强 (SEQA) 框架，该框架利用大型语言模型 (LLMs) 生成多样化但语义等效的问题表述。这种方法在保持语义不变的同时丰富了语言多样性。我们还引入了一个评估指标，总一致性率-语义等效输入与正确答案 (TAR-SC)，用于评估模型在面对语义等效的语言变体时生成一致且正确回答的能力。此外，我们还提出了三个多样性指标：每张图像的问答项平均数 (ANQI)、每张图像具有相同答案的问题平均数 (ANQA)，以及每张图像具有相同语义的开放性问题平均数 (ANQS)。通过 SEQA 框架，我们增强了 SLAKE、VQA-RAD 和 PathVQA 这三个基准 MVQA 公共数据集。结果表明，所有三个数据集在引入更多语义等效问题后均取得了显著提升：ANQI 平均增加 86.1，ANQA 平均增加 85.1，ANQS 平均增加 46。随后的实验在增强后的数据集上，分别在零样本和微调设置下评估了三个 MVQA 模型（M2I2、MUMC 和 BiomedGPT）。实验结果表明，在 MVQA 数据集上，微调后的模型平均准确率提升了 19.35%，而我们提出的 TAR-SC 指标平均提升了 11.61%，这表明模型一致性有了显著提升。

> Medical Visual Question Answering (MVQA) systems can interpret medical images in response to natural language queries. However, linguistic variability in question phrasing often undermines the consistency of these systems. To address this challenge, we propose a Semantically Equivalent Question Augmentation (SEQA) framework, which leverages large language models (LLMs) to generate diverse yet semantically equivalent rephrasings of questions. Specifically, this approach enriches linguistic diversity while preserving semantic meaning. We further introduce an evaluation metric, Total Agreement Rate with Semantically Equivalent Input and Correct Answer (TAR-SC), which assesses a model's capability to generate consistent and correct responses to semantically equivalent linguistic variations. In addition, we also propose three other diversity metrics - average number of QA items per image (ANQI), average number of questions per image with the same answer (ANQA), and average number of open-ended questions per image with the same semantics (ANQS). Using the SEQA framework, we augmented the benchmarked MVQA public datasets of SLAKE, VQA-RAD, and PathVQA. As a result, all three datasets achieved significant improvements by incorporating more semantically equivalent questions: ANQI increased by an average of 86.1, ANQA by 85.1, and ANQS by 46. Subsequent experiments evaluate three MVQA models (M2I2, MUMC, and BiomedGPT) under both zero-shot and fine-tuning settings on the enhanced datasets. Experimental results in MVQA datasets show that fine-tuned models achieve an average accuracy improvement of 19.35%, while our proposed TAR-SC metric shows an average improvement of 11. 61%, indicating a substantial enhancement in model consistency.

[Arxiv](https://arxiv.org/abs/2504.11777)