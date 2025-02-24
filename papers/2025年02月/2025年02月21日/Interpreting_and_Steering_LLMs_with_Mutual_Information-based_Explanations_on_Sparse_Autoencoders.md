# 基于稀疏自编码器的互信息解释，解读和引导大型语言模型

发布时间：2025年02月21日

`LLM理论` `人工智能`

> Interpreting and Steering LLMs with Mutual Information-based Explanations on Sparse Autoencoders

# 摘要

> 大型语言模型（LLMs）在处理人类查询方面表现出色，但偶尔也会生成错误或意外的回应。理解其内部状态对于解析成功案例、诊断失败原因以及优化模型能力至关重要。尽管稀疏自编码器（SAEs）在解释LLM的内部表示方面显示出潜力，但关于如何更好地解释SAE特征的研究仍然有限，即理解SAE所学习特征的语义含义。我们的理论分析表明，现有的解释方法存在频率偏差问题，它们更关注语言模式而非语义概念，而后者对于引导LLM行为更为关键。为了解决这一问题，我们提出使用固定词汇集进行特征解释，并设计了一个基于互信息的目标函数，旨在更好地捕捉这些特征背后的语义含义。我们还提出了两种运行时引导策略，根据相应解释调整所学特征的激活。实证结果表明，与基线方法相比，我们的方法提供了更 discourse-level 的解释，并有效引导LLM行为以防御越狱攻击。这些发现突显了解释在下游应用中引导LLM行为的价值。一旦被接受，我们将公开我们的代码和数据。

> Large language models (LLMs) excel at handling human queries, but they can occasionally generate flawed or unexpected responses. Understanding their internal states is crucial for understanding their successes, diagnosing their failures, and refining their capabilities. Although sparse autoencoders (SAEs) have shown promise for interpreting LLM internal representations, limited research has explored how to better explain SAE features, i.e., understanding the semantic meaning of features learned by SAE. Our theoretical analysis reveals that existing explanation methods suffer from the frequency bias issue, where they emphasize linguistic patterns over semantic concepts, while the latter is more critical to steer LLM behaviors. To address this, we propose using a fixed vocabulary set for feature interpretations and designing a mutual information-based objective, aiming to better capture the semantic meaning behind these features. We further propose two runtime steering strategies that adjust the learned feature activations based on their corresponding explanations. Empirical results show that, compared to baselines, our method provides more discourse-level explanations and effectively steers LLM behaviors to defend against jailbreak attacks. These findings highlight the value of explanations for steering LLM behaviors in downstream applications. We will release our code and data once accepted.

[Arxiv](https://arxiv.org/abs/2502.15576)