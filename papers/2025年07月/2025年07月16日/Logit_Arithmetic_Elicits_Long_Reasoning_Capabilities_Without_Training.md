# Logit算术无需训练，揭示长推理能力

发布时间：2025年07月16日

`LLM应用

理由：这篇论文探讨了如何通过解码时的方法（如ThinkLogit和ThinkLogit-DPO）来提升大型语言模型的长推理能力，属于对大型语言模型应用的研究。` `推理模型`

> Logit Arithmetic Elicits Long Reasoning Capabilities Without Training

# 摘要

> 大型推理模型（LRMs）能够通过长链式思考（CoT）进行复杂推理，涉及回溯和自我修正等认知策略。近期研究表明，某些模型本身具备这种长推理能力，可能通过额外训练得以解锁。我们首先探讨了在无需任何训练的情况下能否激发此类行为。为此，我们提出了一种解码时方法ThinkLogit，该方法利用Liu等人（2024）提出的logits算术，通过一个规模小得多的模型作为引导器，对目标大型LM进行长推理调优。随后，我们展示了通过从目标模型和引导模型中采样正确的/错误的推理对，并对引导模型进行偏好优化训练，可以进一步提升性能——我们将这一设置称为ThinkLogit-DPO。实验结果表明，在使用R1-Distill-Qwen-1.5B（一个规模小21倍的模型）作为引导器时，ThinkLogit和ThinkLogit-DPO在四个数学数据集上分别实现了相对于Qwen2.5-32B模型pass@1指标26%和29%的相对提升。最后，我们还证明ThinkLogit能够转移通过强化学习获得的长推理技能，与Qwen2.5-32B基础模型相比，pass@1指标实现了13%的相对提升。我们的工作提出了一种计算效率高的方法，能够在几乎无需额外训练的情况下激发大型模型的长推理能力。


> Large reasoning models (LRMs) can do complex reasoning via long chain-of-thought (CoT) involving cognitive strategies such as backtracking and self-correction. Recent studies suggest that some models inherently possess these long reasoning abilities, which may be unlocked via extra training. Our work first investigates whether we can elicit such behavior without any training. To this end, we propose a decoding-time approach, ThinkLogit, which utilizes logits arithmetic (Liu et al., 2024) to tune a target large LM for long reasoning using a substantially smaller model as guider. We then show that we can further boost performance by training the guider model with preference optimization over correct/incorrect reasoning pairs sampled from both the target and guider model -- a setup we refer to as ThinkLogit-DPO. Our experiments demonstrate that ThinkLogit and ThinkLogit-DPO achieve a relative improvement in pass@1 by 26% and 29%, respectively, over four mathematical datasets using the Qwen2.5-32B when guided by R1-Distill-Qwen-1.5B -- a model 21x smaller. Lastly, we show that ThinkLogit can transfer long reasoning skills acquired through reinforcement learning, improving pass@1 by 13% relative compared to the Qwen2.5-32B base model. Our work presents a computationally-efficient method to elicit long reasoning in large models with minimal or no additional training.

[Arxiv](https://arxiv.org/abs/2507.12759)