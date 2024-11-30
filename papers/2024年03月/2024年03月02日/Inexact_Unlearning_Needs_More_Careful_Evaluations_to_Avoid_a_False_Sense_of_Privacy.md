# 针对 Inexact Unlearning，为了防止对隐私安全产生误解，我们必须对其进行更为细致的评估。

发布时间：2024年03月02日

`Agent`

> Inexact Unlearning Needs More Careful Evaluations to Avoid a False Sense of Privacy

# 摘要

> 鉴于模型训练费用高昂，研发能删除特定训练样本影响而不必完全重训模型的技术变得越来越重要。形象地说，当模型成功遗忘某个样本后，即使面对与模型交互的对手，也应无法判断该样本是否曾经参与过模型训练，这一概念在隐私研究中被称为成员推断。在此工作中，我们将成员推断攻击（MIAs）调整至遗忘情境下，形成相应的“U-MIA”。我们把已有的U-MIAs分为两类：“全体U-MIA”，针对所有样本采用同一攻击策略；以及“逐个U-MIA”，为每个样本设计专属的攻击策略。实验显示，针对每个个体样本定制攻击策略的逐个U-MIA更具威胁性。实际研究发现，当前遗忘文献中广泛应用的U-MIAs在评估视觉及语言模型遗忘技术所提供的隐私防护时存在过高估计的问题。进一步探究发现，不同样本对于逐个U-MIA的脆弱性差异较大，部分遗忘算法虽可使部分待遗忘样本的脆弱性降低，但同时却令其他样本变得更易受到攻击。特别指出，遗忘过程可能会连带导致未被遗忘的训练样本隐私保护程度下降。另外，我们探讨了由于各样本遗忘速率不一，利用现有遗忘方法很难实现对所有样本同等保护的固有难题，并通过实验证明，单纯地根据不同样本调整遗忘停止标准并不能有效缓解上述问题。

> The high cost of model training makes it increasingly desirable to develop techniques for unlearning. These techniques seek to remove the influence of a training example without having to retrain the model from scratch. Intuitively, once a model has unlearned, an adversary that interacts with the model should no longer be able to tell whether the unlearned example was included in the model's training set or not. In the privacy literature, this is known as membership inference. In this work, we discuss adaptations of Membership Inference Attacks (MIAs) to the setting of unlearning (leading to their ``U-MIA'' counterparts). We propose a categorization of existing U-MIAs into ``population U-MIAs'', where the same attacker is instantiated for all examples, and ``per-example U-MIAs'', where a dedicated attacker is instantiated for each example. We show that the latter category, wherein the attacker tailors its membership prediction to each example under attack, is significantly stronger. Indeed, our results show that the commonly used U-MIAs in the unlearning literature overestimate the privacy protection afforded by existing unlearning techniques on both vision and language models. Our investigation reveals a large variance in the vulnerability of different examples to per-example U-MIAs. In fact, several unlearning algorithms lead to a reduced vulnerability for some, but not all, examples that we wish to unlearn, at the expense of increasing it for other examples. Notably, we find that the privacy protection for the remaining training examples may worsen as a consequence of unlearning. We also discuss the fundamental difficulty of equally protecting all examples using existing unlearning schemes, due to the different rates at which examples are unlearned. We demonstrate that naive attempts at tailoring unlearning stopping criteria to different examples fail to alleviate these issues.

[Arxiv](https://arxiv.org/abs/2403.01218)