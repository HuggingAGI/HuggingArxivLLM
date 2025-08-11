# MedMKEB：面向医疗多模态大型语言模型的全面知识编辑基准。

发布时间：2025年08月07日

`LLM应用

理由：这篇论文专注于多模态大型语言模型在医学领域的应用，特别是知识编辑和更新的基准测试。它探讨了如何在医学AI中高效更新模型知识，属于实际应用层面的研究，因此归类为LLM应用。` `医学AI` `计算机视觉`

> MedMKEB: A Comprehensive Knowledge Editing Benchmark for Medical Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）的最新进展显著提升了医学AI的能力，使其能够统一理解和处理视觉与文本信息。然而，随着医学知识的不断更新，让这些模型能够高效更新过时或错误的信息而不必从头重新训练至关重要。尽管文本知识编辑已得到广泛研究，但目前仍缺乏针对涉及图像和文本模态的多模态医学知识编辑的系统性基准测试。为填补这一空白，我们提出了MedMKEB，这是首个全面基准测试，旨在评估医学多模态大型语言模型中知识编辑的可靠性、通用性、局部性、可移植性和鲁棒性。MedMKEB基于一个高质量的医学视觉问答数据集构建，并通过精心设计的编辑任务进行了丰富，包括反事实修正、语义泛化、知识迁移和对抗鲁棒性。我们还引入了人类专家验证，以确保基准测试的准确性和可靠性。在最先进的通用和医学MLLM上的广泛单次编辑和序列编辑实验表明，现有基于知识的编辑方法在医学领域存在局限性，凸显了开发专门编辑策略的必要性。MedMKEB将作为标准基准测试，推动可信且高效的医学知识编辑算法的发展。

> Recent advances in multimodal large language models (MLLMs) have significantly improved medical AI, enabling it to unify the understanding of visual and textual information. However, as medical knowledge continues to evolve, it is critical to allow these models to efficiently update outdated or incorrect information without retraining from scratch. Although textual knowledge editing has been widely studied, there is still a lack of systematic benchmarks for multimodal medical knowledge editing involving image and text modalities. To fill this gap, we present MedMKEB, the first comprehensive benchmark designed to evaluate the reliability, generality, locality, portability, and robustness of knowledge editing in medical multimodal large language models. MedMKEB is built on a high-quality medical visual question-answering dataset and enriched with carefully constructed editing tasks, including counterfactual correction, semantic generalization, knowledge transfer, and adversarial robustness. We incorporate human expert validation to ensure the accuracy and reliability of the benchmark. Extensive single editing and sequential editing experiments on state-of-the-art general and medical MLLMs demonstrate the limitations of existing knowledge-based editing approaches in medicine, highlighting the need to develop specialized editing strategies. MedMKEB will serve as a standard benchmark to promote the development of trustworthy and efficient medical knowledge editing algorithms.

[Arxiv](https://arxiv.org/abs/2508.05083)