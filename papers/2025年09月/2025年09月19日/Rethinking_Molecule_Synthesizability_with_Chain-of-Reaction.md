# 基于反应链重新思考分子可合成性

发布时间：2025年09月19日

`LLM应用` `医疗健康`

> Rethinking Molecule Synthesizability with Chain-of-Reaction

# 摘要

> 分子生成模型的一大公认痛点是，其生成的分子未必具备可合成性。尽管已有诸多尝试解决这一问题，但由于可合成分子的组合空间呈指数级膨胀，现有方法对该空间的覆盖范围有限，分子优化性能也不尽如人意。为此，我们提出ReaSyn——一个可合成投影生成框架，它通过生成可合成类似物的路径，在可合成空间中探索给定分子的邻域。为充分挖掘合成路径中蕴含的化学知识，我们创新性地将合成路径类比为大型语言模型（LLMs）中的推理路径。具体而言，受LLMs中思维链（CoT）推理的启发，我们提出反应链（CoR）表示法，清晰描述路径中每个步骤的反应物、反应类型及中间产物。借助CoR表示法，ReaSyn能在每个反应步骤中获得密集监督，进而在监督训练中明确学习化学反应规则并实现逐步推理。此外，为进一步提升ReaSyn的推理能力，我们提出基于强化学习（RL）的微调策略，以及专为可合成投影设计的目标导向测试时计算缩放方法。在可合成分子重建任务中，ReaSyn的重建率和路径多样性均为最高；在可合成目标导向分子优化中，其优化性能亦居首位；而在可合成命中扩展任务上，它显著优于以往的可合成投影方法。这些结果充分证明，ReaSyn在驾驭组合规模庞大的可合成化学空间方面具备卓越能力。

> A well-known pitfall of molecular generative models is that they are not guaranteed to generate synthesizable molecules. There have been considerable attempts to address this problem, but given the exponentially large combinatorial space of synthesizable molecules, existing methods have shown limited coverage of the space and poor molecular optimization performance. To tackle these problems, we introduce ReaSyn, a generative framework for synthesizable projection where the model explores the neighborhood of given molecules in the synthesizable space by generating pathways that result in synthesizable analogs. To fully utilize the chemical knowledge contained in the synthetic pathways, we propose a novel perspective that views synthetic pathways akin to reasoning paths in large language models (LLMs). Specifically, inspired by chain-of-thought (CoT) reasoning in LLMs, we introduce the chain-of-reaction (CoR) notation that explicitly states reactants, reaction types, and intermediate products for each step in a pathway. With the CoR notation, ReaSyn can get dense supervision in every reaction step to explicitly learn chemical reaction rules during supervised training and perform step-by-step reasoning. In addition, to further enhance the reasoning capability of ReaSyn, we propose reinforcement learning (RL)-based finetuning and goal-directed test-time compute scaling tailored for synthesizable projection. ReaSyn achieves the highest reconstruction rate and pathway diversity in synthesizable molecule reconstruction and the highest optimization performance in synthesizable goal-directed molecular optimization, and significantly outperforms previous synthesizable projection methods in synthesizable hit expansion. These results highlight ReaSyn's superior ability to navigate combinatorially-large synthesizable chemical space.

[Arxiv](https://arxiv.org/abs/2509.16084)