# 基于双目标优化改进LLM的安全对齐能力

发布时间：2025年03月05日

`LLM理论` `人工智能`

> Improving LLM Safety Alignment with Dual-Objective Optimization

# 摘要

> 现有的大型语言模型（LLMs）训练时的安全对齐技术仍然容易受到越狱攻击的威胁。广泛应用的对齐方法——直接偏好优化（DPO）在实验和理论环境中都显示出一定的局限性，因为其损失函数在拒绝学习中表现欠佳。我们通过基于梯度的分析，识别出这些不足，并提出了一种改进的安全对齐方法，将DPO的目标分解为两个部分：（1）稳健的拒绝训练，即使在生成部分不安全内容时也鼓励模型拒绝；（2）针对性地消除有害知识。这种方法显著提升了LLMs在各种越狱攻击下的鲁棒性，包括预填充、后缀和多轮攻击，无论是在分布内还是分布外的场景下。此外，我们引入了一种方法，通过在拒绝学习中加入基于奖励的标记级加权机制，强调关键拒绝标记，从而进一步增强了对对抗性攻击的防御能力。我们的研究表明，对越狱攻击的鲁棒性与训练过程中标记分布的变化以及拒绝和有害标记的内部表示相关，为未来在LLM安全对齐领域的研究提供了有价值的指导方向。代码可在https://github.com/wicai24/DOOR-Alignment获取。

> Existing training-time safety alignment techniques for large language models (LLMs) remain vulnerable to jailbreak attacks. Direct preference optimization (DPO), a widely deployed alignment method, exhibits limitations in both experimental and theoretical contexts as its loss function proves suboptimal for refusal learning. Through gradient-based analysis, we identify these shortcomings and propose an improved safety alignment that disentangles DPO objectives into two components: (1) robust refusal training, which encourages refusal even when partial unsafe generations are produced, and (2) targeted unlearning of harmful knowledge. This approach significantly increases LLM robustness against a wide range of jailbreak attacks, including prefilling, suffix, and multi-turn attacks across both in-distribution and out-of-distribution scenarios. Furthermore, we introduce a method to emphasize critical refusal tokens by incorporating a reward-based token-level weighting mechanism for refusal learning, which further improves the robustness against adversarial exploits. Our research also suggests that robustness to jailbreak attacks is correlated with token distribution shifts in the training process and internal representations of refusal and harmful tokens, offering valuable directions for future research in LLM safety alignment. The code is available at https://github.com/wicai24/DOOR-Alignment

[Arxiv](https://arxiv.org/abs/2503.03710)