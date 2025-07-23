# Re:Form —— 在 LLM 中通过强化学习减少可扩展形式化软件验证中的人类先验知识：关于 Dafny 的初步研究

发布时间：2025年07月22日

`LLM理论` `软件工程` `机器学习`

> Re:Form -- Reducing Human Priors in Scalable Formal Software Verification with RL in LLMs: A Preliminary Study on Dafny

# 摘要

> 现有的基于非正式语言（如人类语言）的大型语言模型（LLMs）通过强化学习（RL）训练，面临一个重大挑战：它们的验证过程作为关键训练信号，既不可靠也难以扩展。实际上，主流的大型专有模型几乎无法生成可验证程序。一个有前景但未充分探索的替代方案是基于形式化语言的推理。将LLMs植根于严谨的形式化系统中，使其生成模型在形式化语言空间（如Dafny）中运行，从而实现推理过程和结果的自动且数学上可证明的验证。这一能力对实现大规模可靠正式软件验证至关重要。通常，人们利用人类标注的思维链等先验知识引导LLMs的推理和编码能力。然而，为监督复杂编程任务提供此类先验知识变得难以接受。本研究系统探索了如何减少对人类先验知识的依赖，以形式化语言Dafny作为试点研究的主要环境。我们的流水线主要依赖于自动且可扩展的数据整理流程，以及结合形式化语言验证器反馈的精心设计RL方案。我们引入了DafnyComp，这是一个具有自动形式化规范的组合式正式程序基准，用于规范推理。我们的监督微调（SFT）阶段使即使是较小的模型（如0.5B参数量）也能生成语法有效且可验证的Dafny代码，超越了专有模型。通过正则化增强的RL进一步提升了性能，实现了对域外任务的更强泛化能力，并在具有挑战性的DafnyComp基准上超越了所有强大基线模型。

> Existing informal language-based (e.g., human language) Large Language Models (LLMs) trained with Reinforcement Learning (RL) face a significant challenge: their verification processes, which provide crucial training signals, are neither reliable nor scalable. In fact, the prevalent large proprietary models could hardly generate verifiable programs. A promising yet largely uncharted alternative is formal language-based reasoning. Grounding LLMs in rigorous formal systems where generative models operate in formal language spaces (e.g., Dafny) enables the automatic and mathematically provable verification of their reasoning processes and outcomes. This capability is pivotal for achieving large-scale, reliable formal software verification. It is a common practice to employ human-annotated chain-of-thought and other human priors to induce the reasoning and coding capabilities of LLMs. Unfortunately, it becomes unacceptably all-consuming to provide such priors for supervising complex programming tasks. In this work, we systematically explore ways to reduce human priors with the formal language, Dafny, as the main environment for our pilot study. Our pipeline mainly relies on introducing an automatic and scalable data curation pipeline, and careful RL designs integrated with feedback from the formal language verifier. We introduce DafnyComp, a benchmark of compositional formal programs with auto-formalized specifications for specification reasoning. Our supervised fine-tuning (SFT) stage enables even small models (e.g., 0.5B) to generate syntactically valid and verifiable Dafny code, surpassing proprietary models. RL with regularization further improves performance, achieving stronger generalization to out-of-domain tasks and outperforming all strong baselines on the challenging DafnyComp benchmark.

[Arxiv](https://arxiv.org/abs/2507.16331)