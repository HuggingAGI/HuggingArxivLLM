# 字节 BPE 标记化视作逆字符串同态

发布时间：2024年12月04日

`LLM理论` `语言模型`

> Byte BPE Tokenization as an Inverse string Homomorphism

# 摘要

> 分词是大型语言模型（LLMs）训练和推理的重要预处理环节。尽管针对 LLMs 所采用的神经架构的表达能力已有广泛研究，然而分词的影响却未被充分理解。在本研究中，我们证实，无论采用何种算法，分词都充当着字符串与标记之间的逆同态。这意味着源语言的字符空间和分词后的标记空间是同态的，能够保留源语言的结构特性。另外，我们探讨了适当分词的概念，即分词器返回的明确分词。我们的分析表明，神经架构在识别上下文无关语言时的表现力不受分词的影响。

> Tokenization is an important preprocessing step in the training and inference of large language models (LLMs). While there has been extensive research on the expressive power of the neural achitectures used in LLMs, the impact of tokenization has not been well understood. In this work, we demonstrate that tokenization, irrespective of the algorithm used, acts as an inverse homomorphism between strings and tokens. This suggests that the character space of the source language and the token space of the tokenized language are homomorphic, preserving the structural properties of the source language. Additionally, we explore the concept of proper tokenization, which refers to an unambiguous tokenization returned from the tokenizer. Our analysis reveals that the expressiveness of neural architectures in recognizing context-free languages is not affected by tokenization.

[Arxiv](https://arxiv.org/abs/2412.03160)