# 探索上下文机器翻译在低资源语言中的研究：以满语为例

发布时间：2025年02月17日

`LLM应用` `机器翻译` `低资源语言`

> Understanding In-Context Machine Translation for Low-Resource Languages: A Case Study on Manchu

# 摘要

> 基于大型语言模型（LLMs）的上下文机器翻译（MT）在低资源MT领域展现出巨大潜力，因为它能够充分利用语法书、词典等语言资源。这些资源通常会被有选择地整合到提示中，使得LLMs无需任何特定训练，就能通过其上下文学习能力（ICL）直接执行翻译任务。然而，词典、语法书和并行示例等资源的相对重要性尚不明确。为填补这一空白，本研究以满文为案例，系统性地探讨了每种资源及其质量对翻译性能的影响。为了消除LLM参数中预先编码的满文知识，并单独凸显ICL的效果，我们还对加密版本的满文文本进行了实验。研究结果显示，高质量词典和优质的并行示例对提升翻译效果非常有帮助，而语法规则几乎无明显作用。在后续研究中，我们展示了上下文MT的一个有前景的应用：通过生成合成并行数据来增强传统MT模型的自举能力。当单语数据丰富时，利用上下文MT生成合成并行数据，为缓解数据稀缺性、构建有效的低资源神经MT系统提供了一条可行路径。

> In-context machine translation (MT) with large language models (LLMs) is a promising approach for low-resource MT, as it can readily take advantage of linguistic resources such as grammar books and dictionaries. Such resources are usually selectively integrated into the prompt so that LLMs can directly perform translation without any specific training, via their in-context learning capability (ICL). However, the relative importance of each type of resource e.g., dictionary, grammar book, and retrieved parallel examples, is not entirely clear. To address this gap, this study systematically investigates how each resource and its quality affects the translation performance, with the Manchu language as our case study. To remove any prior knowledge of Manchu encoded in the LLM parameters and single out the effect of ICL, we also experiment with an encrypted version of Manchu texts. Our results indicate that high-quality dictionaries and good parallel examples are very helpful, while grammars hardly help. In a follow-up study, we showcase a promising application of in-context MT: parallel data augmentation as a way to bootstrap the conventional MT model. When monolingual data abound, generating synthetic parallel data through in-context MT offers a pathway to mitigate data scarcity and build effective and efficient low-resource neural MT systems.

[Arxiv](https://arxiv.org/abs/2502.11862)