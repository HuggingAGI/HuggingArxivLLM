# LLMCup：**基于排名增强的评论更新方法，通过大型语言模型（LLMs）实现**。

发布时间：2025年07月11日

`LLM应用` `软件工程`

> LLMCup: Ranking-Enhanced Comment Updating with LLMs

# 摘要

> 在现代软件开发中，注释对提升代码可读性和可维护性不可或缺。然而，开发者往往热衷于更新代码，却忽视了注释的同步更新，这导致文档过时或不一致，给后续理解和维护带来了障碍。近年来，CUP 和 HebCup 等方法尝试通过神经序列到序列模型和启发式规则实现自动注释更新。然而，这些方法在更新过程中可能遗漏或误解关键信息，导致注释不准确，且难以应对复杂场景的更新需求。

面对这些挑战，大型语言模型（LLMs）展现出巨大潜力。这些模型在代码生成、代码合成和程序修复等软件工程任务中表现出色，尤其是在捕捉代码修改背后逻辑方面的能力，使其成为注释更新任务的理想选择。然而，如何为每个更新场景选择合适的提示策略仍是一个难题。

为此，我们提出了一种全新的注释更新框架 LLMCup。该框架首先通过多种提示策略，借助 LLM 生成多样化的候选更新注释，然后利用排名模型 CupRank 精准筛选出最佳候选作为最终更新结果。

实验结果表明，LLMCup 的表现显著优于现有最先进的基线方法（CUP 和 HebCup）。具体而言，其在准确率方面提升了 49.0%-116.9%，在 BLEU-4 得分方面提升了 10.8%-20%，在 METEOR 得分方面提升了 4.6%，在 F1 分数方面提升了 0.9%-1.9%，在 SentenceBert 相似度方面提升了 2.1%-3.4%。此外，用户研究表明，LLMCup 生成的注释有时甚至超过了人工编写的注释质量，这凸显了在注释质量评估中纳入人工评价的重要性。


> While comments are essential for enhancing code readability and maintainability in modern software projects, developers are often motivated to update code but not comments, leading to outdated or inconsistent documentation that hinders future understanding and maintenance. Recent approaches such as CUP and HebCup have attempted automatic comment updating using neural sequence-to-sequence models and heuristic rules, respectively. However, these methods can miss or misinterpret crucial information during comment updating, resulting in inaccurate comments, and they often struggle with complex update scenarios. Given these challenges, a promising direction lies in leveraging large language models (LLMs), which have shown impressive performance in software engineering tasks such as comment generation, code synthesis, and program repair. This suggests their strong potential to capture the logic behind code modifications - an ability that is crucial for the task of comment updating. Nevertheless, selecting an appropriate prompt strategy for an LLM on each update case remains challenging. To address this, we propose a novel comment updating framework, LLMCup, which first uses multiple prompt strategies to provide diverse candidate updated comments via an LLM, and then employs a ranking model, CupRank, to select the best candidate as final updated comment. Experimental results demonstrate the effectiveness of LLMCup, with improvements over state-of-the-art baselines (CUP and HebCup) by 49.0%-116.9% in Accuracy, 10.8%-20% in BLEU-4, 4.6% in METEOR, 0.9%-1.9% in F1, and 2.1%-3.4% in SentenceBert similarity. Furthermore, a user study shows that comments updated by LLMCup sometimes surpass human-written updates, highlighting the importance of incorporating human evaluation in comment quality assessment.

[Arxiv](https://arxiv.org/abs/2507.08671)