# 通过语言特定与通用隐私神经元理解并缓解跨语言隐私泄露问题

发布时间：2025年05月31日

`LLM理论` `数据隐私` `人工智能`

> Understanding and Mitigating Cross-lingual Privacy Leakage via Language-specific and Universal Privacy Neurons

# 摘要

> 大型语言模型（LLMs）在海量数据上进行训练，能够捕获训练数据中蕴含的丰富信息。然而，这也带来了隐私泄露的风险，尤其是涉及个人身份信息（PII）。尽管先前的研究表明，可以通过隐私神经元等方法来缓解这一风险，但这些研究均假设训练数据（包括敏感数据）和用户查询均以英语形式存在。我们发现，这些方法无法防御跨语言情境下的隐私泄露：即使训练数据仅使用一种语言，这些（私密的）模型在以另一种语言进行查询时仍可能泄露隐私信息。

在本研究中，我们首先探究了跨语言隐私泄露的信息流，以期获得更深入的理解。我们发现，LLMs会在中间层处理私密信息，这些表示在不同语言间具有高度共享性。当信息被转换到特定语言的空间中时，泄露风险达到峰值。基于这一发现，我们识别出了具有普遍性的隐私神经元和特定于某种语言的隐私神经元。普遍性隐私神经元会影响所有语言的隐私泄露，而特定语言的隐私神经元仅与特定语言相关。通过关闭这些神经元，跨语言隐私泄露的风险降低了23.3%-31.6%。

> Large Language Models (LLMs) trained on massive data capture rich information embedded in the training data. However, this also introduces the risk of privacy leakage, particularly involving personally identifiable information (PII). Although previous studies have shown that this risk can be mitigated through methods such as privacy neurons, they all assume that both the (sensitive) training data and user queries are in English. We show that they cannot defend against the privacy leakage in cross-lingual contexts: even if the training data is exclusively in one language, these (private) models may still reveal private information when queried in another language. In this work, we first investigate the information flow of cross-lingual privacy leakage to give a better understanding. We find that LLMs process private information in the middle layers, where representations are largely shared across languages. The risk of leakage peaks when converted to a language-specific space in later layers. Based on this, we identify privacy-universal neurons and language-specific privacy neurons. Privacy-universal neurons influence privacy leakage across all languages, while language-specific privacy neurons are only related to specific languages. By deactivating these neurons, the cross-lingual privacy leakage risk is reduced by 23.3%-31.6%.

[Arxiv](https://arxiv.org/abs/2506.00759)