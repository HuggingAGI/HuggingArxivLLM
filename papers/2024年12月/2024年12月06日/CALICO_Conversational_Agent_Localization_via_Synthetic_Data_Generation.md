# CALICO：借助合成数据生成实现会话代理本地化

发布时间：2024年12月06日

`LLM应用` `语言处理` `对话代理`

> CALICO: Conversational Agent Localization via Synthetic Data Generation

# 摘要

> 我们推出了 CALICO 这一方法，用于对大型语言模型（LLMs）进行微调，以实现对话代理训练数据从一种语言到另一种语言的本地化。对于插槽（命名实体），CALICO 支持三种操作：逐字复制、字面翻译和本地化，也就是生成在目标语言中更恰当的插槽值，比如使用该语言的国家中的城市和机场名称。另外，我们设计了一种迭代过滤机制来摒弃有噪声的生成样本，结果表明这提升了下游对话代理的性能。为了验证 CALICO 的有效性，我们构建并发布了新的 8 种语言的 MultiATIS++ 旅游信息测试集的人类本地化（HL）版本。和测试集的原始人工翻译（HT）版本相比，我们发现新的 HL 版本更具挑战性。同时，我们还证明，在 HT 情形下，CALICO 生成的插槽翻译更准确；在 HL 情形下，CALICO 生成的本地化插槽更接近 HL 测试集，所以 CALICO 的表现优于最先进的 LINGUIST（其依赖于脱离上下文的字面插槽翻译）。

> We present CALICO, a method to fine-tune Large Language Models (LLMs) to localize conversational agent training data from one language to another. For slots (named entities), CALICO supports three operations: verbatim copy, literal translation, and localization, i.e. generating slot values more appropriate in the target language, such as city and airport names located in countries where the language is spoken. Furthermore, we design an iterative filtering mechanism to discard noisy generated samples, which we show boosts the performance of the downstream conversational agent. To prove the effectiveness of CALICO, we build and release a new human-localized (HL) version of the MultiATIS++ travel information test set in 8 languages. Compared to the original human-translated (HT) version of the test set, we show that our new HL version is more challenging. We also show that CALICO out-performs state-of-the-art LINGUIST (which relies on literal slot translation out of context) both on the HT case, where CALICO generates more accurate slot translations, and on the HL case, where CALICO generates localized slots which are closer to the HL test set.

[Arxiv](https://arxiv.org/abs/2412.05388)