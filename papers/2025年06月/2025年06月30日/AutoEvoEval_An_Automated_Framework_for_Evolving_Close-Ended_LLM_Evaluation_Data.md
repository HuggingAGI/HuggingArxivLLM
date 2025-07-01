# AutoEvoEval：面向闭式大型语言模型评估数据的自动化框架

发布时间：2025年06月30日

`LLM应用

摘要主要讨论了大型语言模型（LLMs）在评估基准中的表现问题，并提出了一种新的评估框架AutoEvoEval。该框架专注于生成多样化和具挑战性的测试样本，以更全面地评估模型的稳健性和泛化能力。研究结果揭示了现有评估基准的局限性，并强调了进化评估方法的重要性。因此，这篇论文属于LLM应用类别，因为它专注于将评估框架应用于实际模型，以改进模型的评估方法。` `问答系统` `评估框架`

> AutoEvoEval: An Automated Framework for Evolving Close-Ended LLM Evaluation Data

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出色，但现有评估基准往往静态且难以全面衡量其在现实场景中的稳健性和泛化能力。此前基于进化或对抗性数据增强的研究虽提升了评估多样性，却缺乏对扰动类型和多步复杂性的系统控制，限制了全面稳健性分析。为此，我们提出了AutoEvoEval——一个专为多项选择问答等封闭式任务设计的基于进化的评估框架。AutoEvoEval引入了22个可解释的原子进化操作，并支持多轮组合，从而能够生成多样化、具挑战性且贴近现实的测试样本。我们针对一系列开源和闭源的LLMs进行了广泛实验，深入探讨了四个关键研究问题。实验结果显示，原子操作平均导致准确率下降7.283个百分点，其中破坏结构或误导语义的编辑导致最大的性能下降。值得注意的是，同一扰动下不同模型的敏感性差异显著，而结合多个进化步骤可将对抗效应放大高达52.932个百分点。这些发现表明，现有基准可能高估了模型的真实泛化能力，凸显了基于进化的稳健性评估的重要性。更多代码和资源请访问：https://github.com/SYSUSELab/AutoEvoEval。

> Large language models (LLMs) have shown remarkable performance on various tasks, but existing evaluation benchmarks are often static and insufficient to fully assess their robustness and generalization in realistic scenarios. Prior work using evolutionary or adversarial data augmentation has improved evaluation diversity but lacks systematic control over perturbation types and multi-step complexity, limiting comprehensive robustness analysis. To address these gaps, we propose AutoEvoEval, an evolution-based evaluation framework for close-ended tasks such as multi-choice question answering. AutoEvoEval introduces 22 interpretable atomic evolution operations and supports multi-round compositions, enabling controlled generation of diverse, challenging, and realistic test samples. We conduct extensive experiments addressing four research questions on a broad set of open- and closed-source LLMs. Our results show that atomic operations cause an average accuracy drop of 7.283\%, with structure-disrupting or misleading semantic edits causing the largest declines. Model sensitivities vary significantly for the same perturbation, and combining multiple evolution steps amplifies adversarial effects by up to 52.932\%. These findings suggest current benchmarks may overestimate true model generalization and emphasize the need for evolution-aware robustness evaluation. Code and resources are available at: https://github.com/SYSUSELab/AutoEvoEval.

[Arxiv](https://arxiv.org/abs/2506.23735)