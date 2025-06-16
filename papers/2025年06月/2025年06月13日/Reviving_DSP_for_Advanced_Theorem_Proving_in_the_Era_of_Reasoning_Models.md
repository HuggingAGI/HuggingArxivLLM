# 在推理模型时代，重拾DSP，探索高级定理证明的新可能。

发布时间：2025年06月13日

`LLM应用` `自动定理证明`

> Reviving DSP for Advanced Theorem Proving in the Era of Reasoning Models

# 摘要

> 近期，DeepSeek-Prover-V2-671B和Kimina-Prover-Preview-72B等进展展示了强化学习（RL）驱动的大规模训练在自动定理证明领域的广泛应用。令人意外的是，即使不借助任何训练，通过巧妙整合现成的推理模型与步骤证明器，也能达到类似的效果。本文提出	extbf{DSP+}，这是Draft、Sketch和Prove框架的升级版，其亮点在于为每个阶段提供了\emph{精细且集成}的神经符号增强：(1) 草稿阶段，推理模型被引导生成简洁的自然语言子目标，以支持后续的草图阶段，同时去除思考标记和对人类证明的引用；(2) 草图阶段，子目标被自动形式化为假设，以辅助证明阶段，同时根据预设规则屏蔽包含语义错误的草图行；(3) 证明阶段，将符号搜索方法（如Aesop）与步骤证明器深度结合，为草图子目标构建证明。实验结果表明，在无需额外训练或微调的情况下，DSP+分别在miniF2F、ProofNet和PutnamBench中解决了644个问题的80.7%、32.8%和24个问题，且计算资源需求低于现有最优方法。DSP+成功证明了miniF2F中的IMO问题	exttt{imo\_2019\_p1}，这是先前工作未能解决的。此外，DSP+生成的证明模式易于人类专家理解，有助于发现形式化错误；例如，在miniF2F中发现了8个错误形式化的陈述。我们的研究结果凸显了传统推理模式的潜力，而不仅仅是基于RL的训练。所有组件即将开源。

> Recent advancements, such as DeepSeek-Prover-V2-671B and Kimina-Prover-Preview-72B, demonstrate a prevailing trend in leveraging reinforcement learning (RL)-based large-scale training for automated theorem proving. Surprisingly, we discover that even without any training, careful neuro-symbolic coordination of existing off-the-shelf reasoning models and tactic step provers can achieve comparable performance. This paper introduces \textbf{DSP+}, an improved version of the Draft, Sketch, and Prove framework, featuring a \emph{fine-grained and integrated} neuro-symbolic enhancement for each phase: (1) In the draft phase, we prompt reasoning models to generate concise natural-language subgoals to benefit the sketch phase, removing thinking tokens and references to human-written proofs; (2) In the sketch phase, subgoals are autoformalized with hypotheses to benefit the proving phase, and sketch lines containing syntactic errors are masked according to predefined rules; (3) In the proving phase, we tightly integrate symbolic search methods like Aesop with step provers to establish proofs for the sketch subgoals. Experimental results show that, without any additional model training or fine-tuning, DSP+ solves 80.7\%, 32.8\%, and 24 out of 644 problems from miniF2F, ProofNet, and PutnamBench, respectively, while requiring fewer budgets compared to state-of-the-arts. DSP+ proves \texttt{imo\_2019\_p1}, an IMO problem in miniF2F that is not solved by any prior work. Additionally, DSP+ generates proof patterns comprehensible by human experts, facilitating the identification of formalization errors; For example, eight wrongly formalized statements in miniF2F are discovered. Our results highlight the potential of classical reasoning patterns besides the RL-based training. All components will be open-sourced.

[Arxiv](https://arxiv.org/abs/2506.11487)