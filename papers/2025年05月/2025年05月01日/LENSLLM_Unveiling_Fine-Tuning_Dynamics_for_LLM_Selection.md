# LENSLLM：揭开LLM选择的微调动态

发布时间：2025年05月01日

`LLM理论` `人工智能` `模型评估`

> LENSLLM: Unveiling Fine-Tuning Dynamics for LLM Selection

# 摘要

> 随着开源大语言模型（LLMs）的普及和多样化下游任务的涌现，如何高效选择模型成为了亟待解决的问题。由于计算资源的限制，对所有候选模型进行微调在现实中并不现实。尽管在LLMs选择方面已有最新进展，但一个基础性的研究问题仍处于萌芽阶段：我们如何建模LLMs在微调过程中的动态行为，从而加深我们对它们在多样化下游任务中泛化性能的理解？在本研究中，我们提出了一种新颖的理论框架，为评估LLMs的泛化能力提供了一个恰当的视角，从而能够准确且高效地选择适用于下游应用的LLMs。具体而言，我们首先推导出一个基于Hessian的PAC-Bayes泛化界，揭示了LLMs的微调动态，然后引入了LENSLLM——一种基于神经切线核（NTK）的修正缩放模型，该模型能够在保持计算效率的同时，实现对多样化任务的准确性能预测。在3个大规模基准测试中的大量实证结果表明，我们的模型在LLMs选择方面达到了高达91.1%的准确率，并将计算成本降低了88.5%，超越了5种最先进的方法。我们已在Github上开源了所提出的LENSLLM模型及相应结果，链接为：https://github.com/Susan571/LENSLLM.git。

> The proliferation of open-sourced Large Language Models (LLMs) and diverse downstream tasks necessitates efficient model selection, given the impracticality of fine-tuning all candidates due to computational constraints. Despite the recent advances in LLM selection, a fundamental research question largely remains nascent: how can we model the dynamic behaviors of LLMs during fine-tuning, thereby enhancing our understanding of their generalization performance across diverse downstream tasks? In this work, we propose a novel theoretical framework that provides a proper lens to assess the generalization capabilities of LLMs, thereby enabling accurate and efficient LLM selection for downstream applications. In particular, we first derive a Hessian-based PAC-Bayes generalization bound that unveils fine-tuning dynamics of LLMs and then introduce LENSLLM, a Neural Tangent Kernel(NTK)-based Rectified Scaling Model that enables accurate performance predictions across diverse tasks while maintaining computational efficiency. Extensive empirical results on 3 large-scale benchmarks demonstrate that our model achieves up to 91.1% accuracy and reduces up to 88.5% computational cost in LLM selection, outperforming 5 state-of-the-art methods. We open-source our proposed LENSLLM model and corresponding results at the Github link: https://github.com/Susan571/LENSLLM.git.

[Arxiv](https://arxiv.org/abs/2505.03793)