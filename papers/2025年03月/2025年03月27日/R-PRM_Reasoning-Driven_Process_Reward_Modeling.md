# R-PRM: 推理驱动的过程奖励建模

发布时间：2025年03月27日

`LLM理论` `数学推理`

> R-PRM: Reasoning-Driven Process Reward Modeling

# 摘要

> 大型语言模型（LLMs）在进行逐步数学推理时难免会出现错误。过程奖励模型（PRMs）通过评估每个推理步骤，成为一种有前途的解决方案。然而，现有的PRMs通常直接输出评估分数，这不仅限制了学习效率和评估准确性，还因标注数据的稀缺性而使问题更加严重。为了解决这些问题，我们提出了基于推理的过程奖励建模（R-PRM）。首先，我们利用更强的LLMs从有限的标注数据中生成种子数据，从而有效启动模型的推理能力，并实现全面的逐步评估。其次，我们通过偏好优化进一步提升性能，而无需额外的标注数据。第三，我们引入推理时的缩放机制，充分挖掘模型的推理潜力。广泛的实验表明R-PRM的有效性：在ProcessBench和PRMBench上，其F1分数分别比强大的基线模型高出11.9和8.5分。当用于指导数学推理时，R-PRM在六个具有挑战性的数据集上实现了超过8.5分的一致性准确性提升。进一步的分析表明，R-PRM展现出更全面的评估能力和更强的泛化能力，从而突显了其巨大的潜力。

> Large language models (LLMs) inevitably make mistakes when performing step-by-step mathematical reasoning. Process Reward Models (PRMs) have emerged as a promising solution by evaluating each reasoning step. However, existing PRMs typically output evaluation scores directly, limiting both learning efficiency and evaluation accuracy, which is further exacerbated by the scarcity of annotated data. To address these issues, we propose Reasoning-Driven Process Reward Modeling (R-PRM). First, we leverage stronger LLMs to generate seed data from limited annotations, effectively bootstrapping our model's reasoning capabilities and enabling comprehensive step-by-step evaluation. Second, we further enhance performance through preference optimization, without requiring additional annotated data. Third, we introduce inference-time scaling to fully harness the model's reasoning potential. Extensive experiments demonstrate R-PRM's effectiveness: on ProcessBench and PRMBench, it surpasses strong baselines by 11.9 and 8.5 points in F1 scores, respectively. When applied to guide mathematical reasoning, R-PRM achieves consistent accuracy improvements of over 8.5 points across six challenging datasets. Further analysis reveals that R-PRM exhibits more comprehensive evaluation and stronger generalization capabilities, thereby highlighting its significant potential.

[Arxiv](https://arxiv.org/abs/2503.21295)