# 我预测，故我在：仅靠预测下一个词，能否从数据中学习人类可理解的概念？

发布时间：2025年03月11日

`LLM理论` `大型语言模型`

> I Predict Therefore I Am: Is Next Token Prediction Enough to Learn Human-Interpretable Concepts from Data?

# 摘要

> 大型语言模型（LLMs）的卓越成就使许多人认为它们展现出某种形式的智能，而非仅仅基于对海量数据进行简单操作的能力。为了阐明这两种观点的区别，我们提出了一种新型生成模型，该模型基于人类可解释的概念（表示为潜在离散变量）生成令牌。在温和的条件下，即使潜在空间到观察空间的映射是非可逆的，我们仍然建立了一个可识别性结果：LLMs通过预测下一个令牌所学习的表示可以近似建模为这些潜在离散概念的后验概率的对数，加上一个可逆的线性变换。这一理论发现不仅表明LLMs捕捉到了潜在的生成因素，而且极大地强化了线性表示假设，该假设认为LLMs学习了人类可解释概念的线性表示。实证研究表明，我们在模拟数据以及Pythia、Llama和DeepSeek模型系列上的评估结果验证了这一理论。

> The remarkable achievements of large language models (LLMs) have led many to conclude that they exhibit a form of intelligence. This is as opposed to explanations of their capabilities based on their ability to perform relatively simple manipulations of vast volumes of data. To illuminate the distinction between these explanations, we introduce a novel generative model that generates tokens on the basis of human interpretable concepts represented as latent discrete variables. Under mild conditions, even when the mapping from the latent space to the observed space is non-invertible, we establish an identifiability result: the representations learned by LLMs through next-token prediction can be approximately modeled as the logarithm of the posterior probabilities of these latent discrete concepts, up to an invertible linear transformation. This theoretical finding not only provides evidence that LLMs capture underlying generative factors, but also strongly reinforces the linear representation hypothesis, which posits that LLMs learn linear representations of human-interpretable concepts. Empirically, we validate our theoretical results through evaluations on both simulation data and the Pythia, Llama, and DeepSeek model families.

[Arxiv](https://arxiv.org/abs/2503.08980)