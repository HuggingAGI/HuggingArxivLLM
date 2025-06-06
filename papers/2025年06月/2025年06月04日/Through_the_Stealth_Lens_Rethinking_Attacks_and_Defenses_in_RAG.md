# 透过隐秘视角：重新审视RAG中的攻击与防御

发布时间：2025年06月04日

`RAG` `文本生成` `攻击防御`

> Through the Stealth Lens: Rethinking Attacks and Defenses in RAG

# 摘要

> 检索增强生成（RAG）系统容易受到注入中毒段落的攻击，即便污染率很低。我们发现现有攻击方法并未设计得足够隐蔽，因此可以被可靠检测和缓解。我们通过基于可区分性的安全游戏来形式化隐秘性。如果少量中毒段落被设计用于控制响应，它们就必须与良性段落区分开来，这本质上会损害隐秘性。这促使攻击者需要严格分析生成过程中涉及的中间信号——如注意力模式或下一个词概率分布——以避免留下容易被察觉的操控痕迹。基于注意力模式，我们提出了一种段落级别的分数——标准化段落注意力分数——并将其用于我们的注意力方差过滤算法，以识别并过滤可能被污染的段落。这种方法缓解了现有攻击，与基线防御相比，准确率提高了约【数学公式】。为了探究基于注意力的防御的极限，我们设计了更为隐秘的自适应攻击，模糊了这些痕迹，实现了高达【数学公式】的攻击成功率，凸显了提升隐秘性的挑战。

> Retrieval-augmented generation (RAG) systems are vulnerable to attacks that inject poisoned passages into the retrieved set, even at low corruption rates. We show that existing attacks are not designed to be stealthy, allowing reliable detection and mitigation. We formalize stealth using a distinguishability-based security game. If a few poisoned passages are designed to control the response, they must differentiate themselves from benign ones, inherently compromising stealth. This motivates the need for attackers to rigorously analyze intermediate signals involved in generation$\unicode{x2014}$such as attention patterns or next-token probability distributions$\unicode{x2014}$to avoid easily detectable traces of manipulation. Leveraging attention patterns, we propose a passage-level score$\unicode{x2014}$the Normalized Passage Attention Score$\unicode{x2014}$used by our Attention-Variance Filter algorithm to identify and filter potentially poisoned passages. This method mitigates existing attacks, improving accuracy by up to $\sim 20 \%$ over baseline defenses. To probe the limits of attention-based defenses, we craft stealthier adaptive attacks that obscure such traces, achieving up to $35 \%$ attack success rate, and highlight the challenges in improving stealth.

[Arxiv](https://arxiv.org/abs/2506.04390)