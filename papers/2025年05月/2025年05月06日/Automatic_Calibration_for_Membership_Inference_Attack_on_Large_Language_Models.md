# 大型语言模型成员推断攻击的自动校准方法

发布时间：2025年05月06日

`LLM理论` `人工智能` `数据安全`

> Automatic Calibration for Membership Inference Attack on Large Language Models

# 摘要

> 最近，成员推断攻击（MIAs）被用于判断特定文本是否属于大型语言模型（LLMs）的预训练数据。然而，现有方法往往误判非成员为成员，导致较高的假阳性率，或依赖额外的参考模型进行概率校准，这限制了其实际应用。为了解决这些挑战，我们提出了一种名为自动校准成员推断攻击（ACMIA）的新框架，该框架通过可调节温度有效校准输出概率。这一方法灵感来源于我们在LLMs预训练过程中对最大似然估计的理论见解。我们以三种配置引入ACMIA，旨在适应不同程度的模型访问，并增加成员与非成员之间的概率差距，从而提高成员推断的可靠性和鲁棒性。在各种开源LLMs上的广泛实验表明，我们的攻击方法具有高度的有效性、鲁棒性和通用性，在三个广泛使用的基准测试中超越了现有的最先进基线。我们的代码可在以下链接获取：\href{https://github.com/Salehzz/ACMIA}{	extcolor{blue}{GitHub}}。


> Membership Inference Attacks (MIAs) have recently been employed to determine whether a specific text was part of the pre-training data of Large Language Models (LLMs). However, existing methods often misinfer non-members as members, leading to a high false positive rate, or depend on additional reference models for probability calibration, which limits their practicality. To overcome these challenges, we introduce a novel framework called Automatic Calibration Membership Inference Attack (ACMIA), which utilizes a tunable temperature to calibrate output probabilities effectively. This approach is inspired by our theoretical insights into maximum likelihood estimation during the pre-training of LLMs. We introduce ACMIA in three configurations designed to accommodate different levels of model access and increase the probability gap between members and non-members, improving the reliability and robustness of membership inference. Extensive experiments on various open-source LLMs demonstrate that our proposed attack is highly effective, robust, and generalizable, surpassing state-of-the-art baselines across three widely used benchmarks. Our code is available at: \href{https://github.com/Salehzz/ACMIA}{\textcolor{blue}{Github}}.

[Arxiv](https://arxiv.org/abs/2505.03392)