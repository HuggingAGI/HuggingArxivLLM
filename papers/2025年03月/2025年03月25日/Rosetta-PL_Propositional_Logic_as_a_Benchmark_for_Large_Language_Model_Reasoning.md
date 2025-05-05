# Rosetta-PL：以命题逻辑为基准，评估大型语言模型的推理能力

发布时间：2025年03月25日

`LLM理论` `逻辑推理` `评估方法`

> Rosetta-PL: Propositional Logic as a Benchmark for Large Language Model Reasoning

# 摘要

> 大型语言模型（LLMs）主要在高资源语言上进行训练，这限制了它们在低资源环境和深度逻辑推理任务中的表现。本研究推出Rosetta-PL基准测试，专注于评估LLMs的逻辑推理和泛化能力。我们通过将Lean中的逻辑命题数据集翻译成自定义逻辑语言来构建Rosetta-PL，并使用该数据集对LLM（如GPT-4o）进行微调。实验表明，数据集规模和翻译方法对模型性能有显著影响。研究发现，翻译过程中保留逻辑关系能大幅提高精度，当训练样本超过约20,000时，精度趋于稳定。这些发现为优化LLM在形式化推理任务中的训练提供了重要指导，并有助于提升其在低资源语言应用中的表现。


> Large Language Models (LLMs) are primarily trained on high-resource natural languages, limiting their effectiveness in low-resource settings and in tasks requiring deep logical reasoning. This research introduces Rosetta-PL, a benchmark designed to evaluate LLMs' logical reasoning and generalization capabilities in a controlled environment. We construct Rosetta-PL by translating a dataset of logical propositions from Lean into a custom logical language, which is then used to fine-tune an LLM (e.g., GPT-4o). Our experiments analyze the impact of the size of the dataset and the translation methodology on the performance of the model. Our results indicate that preserving logical relationships in the translation process significantly boosts precision, with accuracy plateauing beyond roughly 20,000 training samples. These insights provide valuable guidelines for optimizing LLM training in formal reasoning tasks and improving performance in various low-resource language applications.

[Arxiv](https://arxiv.org/abs/2505.00001)