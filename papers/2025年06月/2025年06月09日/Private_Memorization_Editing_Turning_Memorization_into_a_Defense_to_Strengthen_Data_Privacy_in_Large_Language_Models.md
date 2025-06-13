# 隐私记忆编辑：将记忆转化为防御手段，增强大型语言模型中的数据隐私

发布时间：2025年06月09日

`LLM理论` `隐私保护` `数据安全`

> Private Memorization Editing: Turning Memorization into a Defense to Strengthen Data Privacy in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 具有记忆能力，可能在处理大量未受控制的数据时记忆个人身份信息 (PII)，而这些信息本不应被存储或泄露。本文中，我们引入了私密记忆编辑 (PME)，这是一种将 LLMs 的记忆能力转化为强大隐私防御策略的方法，用于防止私密数据泄露。不同于以往针对 LLMs 的攻击手段，这些攻击手段利用了模型训练数据的相关知识，我们的方法旨在利用相同的知识来增强模型的健壮性。我们通过检测模型记忆的 PII，并编辑模型对训练数据的知识来减轻对 PII 的记忆。实验验证表明，我们的方法在不改变基础语言模型性能的同时，显著增强了模型的抗 privacy Training Data Extraction 攻击能力。PME 在多种配置下均能有效减少泄露的 PII 数量，甚至在某些情况下将隐私攻击的准确率降至零。

> Large Language Models (LLMs) memorize, and thus, among huge amounts of uncontrolled data, may memorize Personally Identifiable Information (PII), which should not be stored and, consequently, not leaked. In this paper, we introduce Private Memorization Editing (PME), an approach for preventing private data leakage that turns an apparent limitation, that is, the LLMs' memorization ability, into a powerful privacy defense strategy. While attacks against LLMs have been performed exploiting previous knowledge regarding their training data, our approach aims to exploit the same kind of knowledge in order to make a model more robust. We detect a memorized PII and then mitigate the memorization of PII by editing a model knowledge of its training data. We verify that our procedure does not affect the underlying language model while making it more robust against privacy Training Data Extraction attacks. We demonstrate that PME can effectively reduce the number of leaked PII in a number of configurations, in some cases even reducing the accuracy of the privacy attacks to zero.

[Arxiv](https://arxiv.org/abs/2506.10024)