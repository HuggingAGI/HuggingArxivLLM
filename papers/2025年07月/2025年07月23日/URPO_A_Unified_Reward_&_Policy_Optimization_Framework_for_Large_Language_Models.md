# URPO：大型语言模型的统一奖励与策略优化框架

发布时间：2025年07月23日

`LLM理论` `模型对齐` `指令遵循`

> URPO: A Unified Reward & Policy Optimization Framework for Large Language Models

# 摘要

> 传统大规模对齐流水线通常将策略模型与独立训练的奖励模型配对，这种分离不仅导致了复杂且资源密集的流程，还因静态奖励信号而存在性能上限。我们提出了一种创新的统一奖励与策略优化（URPO）框架，将指令遵循（"玩家"）和奖励建模（"裁判"）整合到一个模型和一个训练阶段中。我们的方法将所有对齐数据——包括偏好对、可验证推理和开放性指令——统一为一种生成格式，并通过单一的组相对策略优化（GRPO）循环进行优化。这使模型能够从真实偏好和可验证逻辑中学习，同时为开放性任务生成自身的奖励。在Qwen2.5-7B模型上的实验结果展示了URPO的显著优势。我们的统一模型在AlpacaEval上的指令遵循分数从42.24提升至44.84，复合推理平均分从32.66提升至35.66，显著超越了使用独立生成奖励模型的强劲基线。此外，URPO在训练过程中还培养了一个更优秀的内部评估器，在RewardBench上达到了85.15分，超过了被取代的专用奖励模型（83.55分）。通过消除对独立奖励模型的需求，并促进生成与评估之间的共同进化动态，URPO为构建稳健对齐的语言模型提供了一条更简单、更高效、更有效的路径。

> Large-scale alignment pipelines typically pair a policy model with a separately trained reward model whose parameters remain frozen during reinforcement learning (RL). This separation creates a complex, resource-intensive pipeline and suffers from a performance ceiling due to a static reward signal. We propose a novel framework, Unified Reward & Policy Optimization (URPO), that unifies instruction-following ("player") and reward modeling ("referee") within a single model and a single training phase. Our method recasts all alignment data-including preference pairs, verifiable reasoning, and open-ended instructions-into a unified generative format optimized by a single Group-Relative Policy Optimization (GRPO) loop. This enables the model to learn from ground-truth preferences and verifiable logic while simultaneously generating its own rewards for open-ended tasks. Experiments on the Qwen2.5-7B model demonstrate URPO's superiority. Our unified model significantly outperforms a strong baseline using a separate generative reward model, boosting the instruction-following score on AlpacaEval from 42.24 to 44.84 and the composite reasoning average from 32.66 to 35.66. Furthermore, URPO cultivates a superior internal evaluator as a byproduct of training, achieving a RewardBench score of 85.15 and surpassing the dedicated reward model it replaces (83.55). By eliminating the need for a separate reward model and fostering a co-evolutionary dynamic between generation and evaluation, URPO presents a simpler, more efficient, and more effective path towards robustly aligned language models.

[Arxiv](https://arxiv.org/abs/2507.17515)