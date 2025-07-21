# Seed-X：打造具备70亿参数的多语言翻译强模型

发布时间：2025年07月17日

`LLM应用`

> Seed-X: Building Strong Multilingual Translation LLM with 7B Parameters

# 摘要

> 多语言翻译对大型语言模型（LLMs）而言是一项极具挑战性的任务，需要处理复杂的语言模式和自动化翻译中的生硬表达。本文中，我们推出了Seed-X，一个开源的LLM家族，包含指令模型和推理模型，通过70亿参数规模突破了翻译能力的极限。基础模型在涵盖28种语言的多样化高质量数据集上进行预训练，包括单语和双语内容，充分挖掘了多语言数据的潜力。随后，指令模型通过链式思维（CoT）推理进行微调，并通过强化学习（RL）进一步优化，以实现对多种语言对的更好泛化。Seed-X在28种语言上实现了与领先闭源模型（包括Gemini-2.5和GPT-4o）相当的性能，并在自动评估指标和人工评估中显著超越了更大规模的开源模型。我们分享了优化过程中的最佳实践，并公开了模型参数，以推动翻译研究和应用的发展。

> Multilingual translation stands as a challenging task for large language models (LLMs) to handle intricate language patterns and stilted translations that arise in automated translations. In this paper, we introduce Seed-X, a family of open-source LLMs comprising instruct and reasoning models, pushing the limits of translation capability with 7B parameter size. The base model is pre-trained on a diverse, high-quality dataset encompassing both monolingual and bilingual content across 28 languages, harnessing the full potential of multilingual data. The instruct model is then finetuned to translate by Chain-of-Thought (CoT) reasoning and further enhanced through reinforcement learning (RL) to achieve better generalization across diverse language pairs. Seed-X achieves performance comparable to leading closed-source models, including Gemini-2.5 and GPT-4o, across 28 languages, and significantly outperforms larger open-source models in both automatic metrics and human evaluations. We share the best practices through our optimization process, and make the parameter public available for advancing translation research and applications.

[Arxiv](https://arxiv.org/abs/2507.13618)