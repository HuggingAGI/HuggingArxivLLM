# # 通过越狱概率评估，实现对多模态大语言模型的安全攻击与防护

发布时间：2025年03月10日

`LLM应用

摘要讨论了多模态大型语言模型（MLLMs）在越狱攻击中的安全问题，提出了新的攻击方法和防御策略，属于实际应用层面的研究，因此归类为LLM应用。` `人工智能安全` `安全防护`

> Utilizing Jailbreak Probability to Attack and Safeguard Multimodal LLMs

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在理解多模态内容方面表现出色，但它们仍易受越狱攻击影响，这些攻击利用模型安全对齐中的弱点生成有害响应。传统研究将越狱攻击简单分为成功或失败两类，但鉴于MLLMs响应的随机性，这种二元分类方式并不适用。为此，我们引入了越狱概率，量化输入的越狱潜力，即MLLMs在特定输入提示下生成恶意响应的可能性。通过多次查询MLLMs，我们近似计算这一概率。基于越狱概率预测网络（JPPN）建模输入隐藏状态与其越狱概率的关系后，我们采用连续越狱概率进行优化。具体而言，我们提出了一种基于越狱概率的攻击方法（JPA），通过优化输入扰动来最大化越狱概率。为抵御此类攻击，我们还提出了两种防御策略：基于越狱概率的微调（JPF）和基于越狱概率的防御噪声（JPDN），分别通过最小化MLLM参数和输入空间中的越狱概率来增强模型安全性。实验结果显示，（1）相较于传统方法，JPA在白盒和黑盒场景下均实现了显著提升，最高达28.38%。（2）JPF和JPDN可将越狱攻击减少60%以上。这些结果充分证明了引入越狱概率对细致区分输入越狱能力的重要性。

> Recently, Multimodal Large Language Models (MLLMs) have demonstrated their superior ability in understanding multimodal contents. However, they remain vulnerable to jailbreak attacks, which exploit weaknesses in their safety alignment to generate harmful responses. Previous studies categorize jailbreaks as successful or failed based on whether responses contain malicious content. However, given the stochastic nature of MLLM responses, this binary classification of an input's ability to jailbreak MLLMs is inappropriate. Derived from this viewpoint, we introduce jailbreak probability to quantify the jailbreak potential of an input, which represents the likelihood that MLLMs generated a malicious response when prompted with this input. We approximate this probability through multiple queries to MLLMs. After modeling the relationship between input hidden states and their corresponding jailbreak probability using Jailbreak Probability Prediction Network (JPPN), we use continuous jailbreak probability for optimization. Specifically, we propose Jailbreak-Probability-based Attack (JPA) that optimizes adversarial perturbations on inputs to maximize jailbreak probability. To counteract attacks, we also propose two defensive methods: Jailbreak-Probability-based Finetuning (JPF) and Jailbreak-Probability-based Defensive Noise (JPDN), which minimizes jailbreak probability in the MLLM parameters and input space, respectively. Extensive experiments show that (1) JPA yields improvements (up to 28.38\%) under both white and black box settings compared to previous methods with small perturbation bounds and few iterations. (2) JPF and JPDN significantly reduce jailbreaks by at most over 60\%. Both of the above results demonstrate the significance of introducing jailbreak probability to make nuanced distinctions among input jailbreak abilities.

[Arxiv](https://arxiv.org/abs/2503.06989)