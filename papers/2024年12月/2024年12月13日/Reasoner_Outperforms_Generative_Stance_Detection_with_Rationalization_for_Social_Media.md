# Reasoner 表现出色：社交媒体中基于合理化的生成式立场检测

发布时间：2024年12月13日

`LLM应用` `社交媒体`

> Reasoner Outperforms: Generative Stance Detection with Rationalization for Social Media

# 摘要

> 立场检测对于通过分析用户生成的内容来识别那些破坏信任的偏见和有害叙述，进而培育以人为本的网络而言，极其重要。随着大型语言模型（LLMs）的发展，现有的方法把立场检测当作分类问题来处理，为建模复杂的群体互动提供了有力手段，也提升了自然语言任务方面的能力。然而，这些方法通常缺乏可解释性，限制了其为预测给出透明且易懂的理由的能力。本研究采用一种生成式方法，立场预测包含清晰、可解释的依据，并通过单任务和多任务学习将其融入较小的语言模型中。我们发现，把推理引入立场检测能让较小的模型（FlanT5）超越 GPT-3.5 的零样本性能，提升幅度高达 9.57%。此外，我们的结果显示，推理能力能增强多任务学习的性能，但可能会降低单任务场景下的效果。关键的是，我们证明了可靠的依据有助于将其提炼到 SLMs 中，推动了构建可解释、值得信赖的系统，以解决歧视问题、增进信任以及促进社交媒体上的公平参与。

> Stance detection is crucial for fostering a human-centric Web by analyzing user-generated content to identify biases and harmful narratives that undermine trust. With the development of Large Language Models (LLMs), existing approaches treat stance detection as a classification problem, providing robust methodologies for modeling complex group interactions and advancing capabilities in natural language tasks. However, these methods often lack interpretability, limiting their ability to offer transparent and understandable justifications for predictions. This study adopts a generative approach, where stance predictions include explicit, interpretable rationales, and integrates them into smaller language models through single-task and multitask learning. We find that incorporating reasoning into stance detection enables the smaller model (FlanT5) to outperform GPT-3.5's zero-shot performance, achieving an improvement of up to 9.57%. Moreover, our results show that reasoning capabilities enhance multitask learning performance but may reduce effectiveness in single-task settings. Crucially, we demonstrate that faithful rationales improve rationale distillation into SLMs, advancing efforts to build interpretable, trustworthy systems for addressing discrimination, fostering trust, and promoting equitable engagement on social media.

[Arxiv](https://arxiv.org/abs/2412.10266)