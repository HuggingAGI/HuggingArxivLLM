# # 超越80/20法则：高熵少数令牌助力LLM推理的高效强化学习

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Beyond the 80/20 Rule: High-Entropy Minority Tokens Drive Effective Reinforcement Learning for LLM Reasoning

# 摘要

> 强化学习与可验证奖励（RLVR）作为一种强大的方法，已崭露头角，能够显著提升大型语言模型（LLMs）的推理能力。尽管其具体机制尚未完全明了，本研究从token熵模式这一新颖视角出发，对RLVR展开了开创性的探索，全面分析了不同token对推理性能的影响。

通过考察思维链推理（CoT）中的token熵模式，我们发现仅有少数token呈现出高熵特征，而这些高熵token充当了关键分岔点，引导模型走向多样化的推理路径。进一步研究熵模式在RLVR训练过程中如何演变，我们发现RLVR主要遵循基础模型的熵模式，主要调整高熵token的熵值。这些发现突显了高熵token（即分岔token）对RLVR的重要性。

我们最终通过限制策略梯度更新仅作用于分岔token，成功优化了RLVR，并揭示了一个甚至超越80/20法则的发现：仅利用20%的token，同时保持与Qwen3-8B基础模型全梯度更新相当的性能，并在Qwen3-32B和Qwen3-14B基础模型上显著超越全梯度更新（AIME'25提升11.04，AIME'24提升7.71和4.79/5.21），凸显出强烈的扩展趋势。相比之下，仅针对80%低熵token进行训练会导致性能显著下降。

这些发现表明，RLVR的有效性主要源于对决定推理方向的高熵token的优化。综合来看，我们的研究结果突显了通过token-entropy视角理解RLVR的潜力，并通过利用高熵少数token优化RLVR，从而进一步提升LLM推理能力。

> Reinforcement Learning with Verifiable Rewards (RLVR) has emerged as a powerful approach to enhancing the reasoning capabilities of Large Language Models (LLMs), while its mechanisms are not yet well understood. In this work, we undertake a pioneering exploration of RLVR through the novel perspective of token entropy patterns, comprehensively analyzing how different tokens influence reasoning performance. By examining token entropy patterns in Chain-of-Thought (CoT) reasoning, we observe that only a small fraction of tokens exhibit high entropy, and these tokens act as critical forks that steer the model toward diverse reasoning pathways. Furthermore, studying how entropy patterns evolve during RLVR training reveals that RLVR largely adheres to the base model's entropy patterns, primarily adjusting the entropy of high-entropy tokens. These findings highlight the significance of high-entropy tokens (i.e., forking tokens) to RLVR. We ultimately improve RLVR by restricting policy gradient updates to forking tokens and uncover a finding even beyond the 80/20 rule: utilizing only 20% of the tokens while maintaining performance comparable to full-gradient updates on the Qwen3-8B base model and significantly surpassing full-gradient updates on the Qwen3-32B (+11.04 on AIME'25 and +7.71 on AIME'24) and Qwen3-14B (+4.79 on AIME'25 and +5.21 on AIME'24) base models, highlighting a strong scaling trend. In contrast, training exclusively on the 80% lowest-entropy tokens leads to a marked decline in performance. These findings indicate that the efficacy of RLVR primarily arises from optimizing the high-entropy tokens that decide reasoning directions. Collectively, our results highlight the potential to understand RLVR through a token-entropy perspective and optimize RLVR by leveraging high-entropy minority tokens to further improve LLM reasoning.

[Arxiv](https://arxiv.org/abs/2506.01939)