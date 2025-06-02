# Reason-SVG：通过混合式奖励强化学习实现矢量图形生成中的顿悟时刻

发布时间：2025年05月30日

`LLM应用` `图形设计` `人工智能`

> Reason-SVG: Hybrid Reward RL for Aha-Moments in Vector Graphics Generation

# 摘要

> 生成高质量的可缩放矢量图形（SVG）对大型语言模型（LLMs）来说颇具挑战性，因为这需要在结构有效性、语义忠实性和视觉连贯性方面具备高级推理能力，而目前的LLMs往往难以达到这些要求。本研究中，我们引入了Reason-SVG，一个旨在提升LLM在SVG生成方面推理能力的创新框架。Reason-SVG开创了'边想边画'（DwT）的范式，模型在生成SVG代码的同时，还会输出明确的设计推理过程，模拟人类的创意过程。Reason-SVG采用了两阶段训练策略：首先，监督微调（SFT）使LLM在DwT范式下训练，以激活其基础推理能力。其次，利用组相对策略优化（GRPO）的强化学习（RL），赋能模型通过精细、奖励驱动的推理生成DwT和SVG设计推理。为了促进推理驱动的SVG生成，我们设计了一个混合奖励函数，评估DwT推理的存在性和实用性，同时考虑结构有效性、语义对齐和视觉质量。我们还推出了SVGX-DwT-10k数据集，这是一个包含10,000对SVG-DwT的高质量语料库，每段SVG代码均基于明确的DwT推理生成。通过整合DwT、SFT和混合奖励引导的RL，Reason-SVG显著提升了LLM生成精确且视觉吸引人的SVG的能力，有望在设计中带来'顿悟时刻'。

> Generating high-quality Scalable Vector Graphics (SVGs) is challenging for Large Language Models (LLMs), as it requires advanced reasoning for structural validity, semantic faithfulness, and visual coherence -- capabilities in which current LLMs often fall short. In this work, we introduce Reason-SVG, a novel framework designed to enhance LLM reasoning for SVG generation. Reason-SVG pioneers the "Drawing-with-Thought" (DwT) paradigm, in which models generate both SVG code and explicit design rationales, mimicking the human creative process. Reason-SVG adopts a two-stage training strategy: First, Supervised Fine-Tuning (SFT) trains the LLM on the DwT paradigm to activate foundational reasoning abilities. Second, Reinforcement Learning (RL), utilizing Group Relative Policy Optimization (GRPO), empowers the model to generate both DwT and SVGs rationales through refined, reward-driven reasoning. To facilitate reasoning-driven SVG generation, we design a Hybrid Reward function that evaluates the presence and utility of DwT reasoning, along with structural validity, semantic alignment, and visual quality. We also introduce the SVGX-DwT-10k dataset, a high-quality corpus of 10,000 SVG-DwT pairs, where each SVG code is generated based on explicit DwT reasoning. By integrating DwT, SFT, and Hybrid Reward-guided RL, Reason-SVG significantly improves LLM performance in generating accurate and visually compelling SVGs, potentially fostering "Aha moments" in design.

[Arxiv](https://arxiv.org/abs/2505.24499)