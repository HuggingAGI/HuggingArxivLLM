# 对比激活工程学中的模式与机制

发布时间：2025年05月06日

`LLM理论` `人工智能` `模型优化`

> Patterns and Mechanisms of Contrastive Activation Engineering

# 摘要

> 驾驭大型语言模型（LLMs）的行为仍然是一个重大挑战，这源于其固有的复杂性和不透明性。虽然像微调这样的技术可以改变模型行为，但它们通常需要大量的计算资源。最近的研究引入了一类对比激活工程（CAE）技术，作为一种有前景的方法，通过有针对性地修改模型的内部表示来引导LLM的输出。CAE在推理时应用且零成本，有可能带来一种新的灵活的、任务特定的LLM行为调节范式。

我们分析了CAE在分布内和分布外设置下的性能，评估了其缺点，并开始制定全面的指南以实现其有效部署。我们发现：
1. CAE仅在应用于分布内场景时才可靠有效。
2. 用于生成引导向量的样本数量增加到约80个时，效果提升会逐渐减弱。
3. 引导向量容易受到对抗性输入的影响，这会逆转被引导的行为。
4. 引导向量会损害整个模型的困惑度。
5. 更大的模型对引导引起的退化更具抵抗力。


> Controlling the behavior of Large Language Models (LLMs) remains a significant challenge due to their inherent complexity and opacity. While techniques like fine-tuning can modify model behavior, they typically require extensive computational resources. Recent work has introduced a class of contrastive activation engineering (CAE) techniques as promising approaches for steering LLM outputs through targeted modifications to their internal representations. Applied at inference-time with zero cost, CAE has the potential to introduce a new paradigm of flexible, task-specific LLM behavior tuning. We analyze the performance of CAE in in-distribution, out-of-distribution settings, evaluate drawbacks, and begin to develop comprehensive guidelines for its effective deployment. We find that 1. CAE is only reliably effective when applied to in-distribution contexts. 2. Increasing the number of samples used to generate steering vectors has diminishing returns at around 80 samples. 3. Steering vectors are susceptible to adversarial inputs that reverses the behavior that is steered for. 4. Steering vectors harm the overall model perplexity. 5. Larger models are more resistant to steering-induced degradation.

[Arxiv](https://arxiv.org/abs/2505.03189)