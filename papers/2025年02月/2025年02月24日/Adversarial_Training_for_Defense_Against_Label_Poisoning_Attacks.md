# 防御标签投毒攻击的对抗训练方法

发布时间：2025年02月24日

`LLM理论` `机器学习`

> Adversarial Training for Defense Against Label Poisoning Attacks

# 摘要

> 随着机器学习模型复杂度的提升以及对公开数据源依赖的增加，例如训练大型语言模型时所用到的人工标注标签，它们也变得更加容易受到标签投毒攻击的影响。这些攻击中，攻击者会细微地篡改训练数据集中的标签，从而严重削弱模型性能，给关键应用带来重大风险。

本文中，我们提出了FLORAL，这是一种基于支持向量机（SVM）的新型对抗训练防御策略，旨在应对这些威胁。通过双层优化框架，我们将训练过程建模为一个非零和的Stackelberg博弈：攻击者战略性地投毒关键训练标签，而模型则试图从此类攻击中恢复。我们的方法兼容多种模型架构，并采用带有核SVM的投影梯度下降算法进行对抗训练。

我们对算法的收敛性质进行了理论分析，并通过实证评估FLORAL在各类分类任务中的有效性。与鲁棒基线模型和基金会模型（如RoBERTa）相比，FLORAL在攻击者预算不断增加的情况下，始终能够实现更高的鲁棒准确性。这些结果凸显了FLORAL在增强机器学习模型抵御标签投毒威胁的韧性方面的潜力，从而确保在对抗环境中实现稳健分类。

> As machine learning models grow in complexity and increasingly rely on publicly sourced data, such as the human-annotated labels used in training large language models, they become more vulnerable to label poisoning attacks. These attacks, in which adversaries subtly alter the labels within a training dataset, can severely degrade model performance, posing significant risks in critical applications. In this paper, we propose FLORAL, a novel adversarial training defense strategy based on support vector machines (SVMs) to counter these threats. Utilizing a bilevel optimization framework, we cast the training process as a non-zero-sum Stackelberg game between an attacker, who strategically poisons critical training labels, and the model, which seeks to recover from such attacks. Our approach accommodates various model architectures and employs a projected gradient descent algorithm with kernel SVMs for adversarial training. We provide a theoretical analysis of our algorithm's convergence properties and empirically evaluate FLORAL's effectiveness across diverse classification tasks. Compared to robust baselines and foundation models such as RoBERTa, FLORAL consistently achieves higher robust accuracy under increasing attacker budgets. These results underscore the potential of FLORAL to enhance the resilience of machine learning models against label poisoning threats, thereby ensuring robust classification in adversarial settings.

[Arxiv](https://arxiv.org/abs/2502.17121)