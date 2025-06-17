# 从涌现到控制：探究与调控语言模型中的自我反思

发布时间：2025年06月13日

`LLM理论` `人工智能` `机器学习`

> From Emergence to Control: Probing and Modulating Self-Reflection in Language Models

# 摘要

> 自我反思——大型语言模型 (LLM) 重新审视、评估和修订自身推理的能力——作为一种强大的行为，最近通过可验证奖励的强化学习 (RLVR) 得到了实现。尽管自我反思与推理准确性的提升密切相关，但其起源和内在机制仍然不为人所理解。在这项研究中，我们首先证明了自我反思并非仅限于经过 RLVR 微调的模型：它已经在预训练模型中出现，尽管非常罕见。为了探究这一潜在能力，我们引入了 Reflection-Inducing Probing 方法，该方法将来自微调模型的引发反思的推理轨迹注入到预训练模型中。这一干预措施使 Qwen2.5 的自我反思频率从 0.6% 提升至 18.6%，揭示了其隐藏的反思能力。此外，我们对内部表示的分析表明，预训练和微调模型都保持了隐藏状态，这些状态能够明确区分自我反思和非自我反思的上下文。基于这一观察，我们构建了一个自我反思向量，这是一个与自我反思推理相关的激活空间中的方向。通过操控这一向量，我们实现了对预训练和微调模型自我反思行为的双向控制。在多个推理基准测试中的实验表明，增强这些向量可将推理性能提升高达 12%，而抑制它们则降低了计算成本，从而提供了一种灵活的机制，可以在不进行额外训练的情况下平衡推理质量和效率之间的权衡。我们的发现进一步加深了对自我反思的理解，并支持了越来越多的研究，这些研究表明理解模型内部机制可以实现对行为的精确控制。


> Self-reflection -- the ability of a large language model (LLM) to revisit, evaluate, and revise its own reasoning -- has recently emerged as a powerful behavior enabled by reinforcement learning with verifiable rewards (RLVR). While self-reflection correlates with improved reasoning accuracy, its origin and underlying mechanisms remain poorly understood. In this work, {\it we first show that self-reflection is not exclusive to RLVR fine-tuned models: it already emerges, albeit rarely, in pretrained models}. To probe this latent ability, we introduce Reflection-Inducing Probing, a method that injects reflection-triggering reasoning traces from fine-tuned models into pretrained models. This intervention raises self-reflection frequency of Qwen2.5 from 0.6\% to 18.6\%, revealing a hidden capacity for reflection. Moreover, our analysis of internal representations shows that both pretrained and fine-tuned models maintain hidden states that distinctly separate self-reflective from non-reflective contexts. Leveraging this observation, {\it we then construct a self-reflection vector, a direction in activation space associated with self-reflective reasoning}. By manipulating this vector, we enable bidirectional control over the self-reflective behavior for both pretrained and fine-tuned models. Experiments across multiple reasoning benchmarks show that enhancing these vectors improves reasoning performance by up to 12\%, while suppressing them reduces computational cost, providing a flexible mechanism to navigate the trade-off between reasoning quality and efficiency without requiring additional training. Our findings further our understanding of self-reflection and support a growing body of work showing that understanding model internals can enable precise behavioral control.

[Arxiv](https://arxiv.org/abs/2506.12217)