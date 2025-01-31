# 用通用魔法词破解LLMs的文本嵌入模型防护

发布时间：2025年01月30日

`LLM应用

理由：该论文主要讨论了大型语言模型（LLMs）的安全问题，特别是针对文本嵌入模型的攻击和防御机制。论文提出了一种攻击方法，通过添加特定的“魔法词”来操纵文本嵌入向量的分布，从而绕过保护机制。此外，论文还提出了一种防御机制来纠正文本嵌入的偏差分布。这些内容直接涉及LLMs在实际应用中的安全问题，因此应归类为“LLM应用”。` `信息安全`

> Jailbreaking LLMs' Safeguard with Universal Magic Words for Text Embedding Models

# 摘要

> LLMs的安全问题近来备受关注，各种防御机制应运而生，其中基于文本嵌入模型的保护措施是基础防线。测试发现，文本嵌入模型的输出分布存在显著偏差，均值较大。受此启发，我们提出了一种高效方法，用于搜索攻击文本嵌入模型的通用魔法词。这些魔法词作为后缀，可将任何文本的嵌入向量推向偏差方向，从而操纵文本对的相似性，误导保护机制。攻击者通过在用户提示后附加魔法词，并要求LLMs以魔法词结尾，即可绕过保护机制。为消除这一安全隐患，我们还提出了一种无需训练的防御机制，可纠正文本嵌入的偏差分布。

> The security issue of large language models (LLMs) has gained significant attention recently, with various defense mechanisms developed to prevent harmful outputs, among which safeguards based on text embedding models serve as a fundamental defense. Through testing, we discover that the distribution of text embedding model outputs is significantly biased with a large mean. Inspired by this observation, we propose novel efficient methods to search for universal magic words that can attack text embedding models. The universal magic words as suffixes can move the embedding of any text towards the bias direction, therefore manipulate the similarity of any text pair and mislead safeguards. By appending magic words to user prompts and requiring LLMs to end answers with magic words, attackers can jailbreak the safeguard. To eradicate this security risk, we also propose defense mechanisms against such attacks, which can correct the biased distribution of text embeddings in a train-free manner.

[Arxiv](https://arxiv.org/abs/2501.18280)