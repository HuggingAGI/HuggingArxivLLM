# Transformer模型在不同长度代码补全任务中的泛化能力研究

发布时间：2025年01月09日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在编程领域的泛化能力，特别是针对训练期间未见过的输入长度的表现。论文通过实证研究评估了不同编码方案的泛化能力，并得出结论。这些内容涉及LLMs的理论基础和性能评估，因此应归类为LLM理论。` `软件工程`

> On the Generalizability of Transformer Models to Code Completions of Different Lengths

# 摘要

> 编程领域正因大型语言模型（LLMs）的崛起而焕然一新，这些模型能够自动化代码实现（如代码补全）和理解（如代码摘要）等任务。这一变革不仅影响了软件的编写、维护和演化方式，还因其高昂的训练成本引发了对其可持续性的质疑。鉴于训练成本，LLMs的泛化能力——即在不同于训练任务实例上的表现——成为了一个值得深入探讨的课题。此前的研究已证明，transformer模型在跨项目环境中能有效支持代码补全。然而，LLMs是否能泛化到训练期间未见过的输入长度仍是个谜。例如，在短实例上训练模型虽能大幅降低成本，但其在未见过的序列长度上的表现如何尚不得而知。最近，自然语言处理（NLP）领域的研究在仅解码器LLMs（如xPOS和ALiBi）中探讨了这一问题。为了验证这些方案是否适用于代码任务中常见的编码器-解码器LLMs，我们进行了一项大规模实证研究，评估了Sinusoidal、xPOS、ALiBi和T5等编码方案的泛化能力。结果表明，这些方案均未能成功泛化到未见过的长度，唯一可靠的解决方案是确保训练集中包含所有可能在推理时遇到的长度。

> The programming landscape is nowadays being reshaped by the advent of Large Language Models (LLMs) able to automate code-related tasks related to code implementation (e.g., code completion) and comprehension (e.g., code summarization). Such a paradigm shift comes with a number of implications related to how software will be written, maintained, and evolved. Also, these LLMs are extremely expensive to train, posing questions on their sustainability over time. Given their training cost, their ability to generalize, namely their ability to work on task instances different from those on which they have been trained, is an aspect worth being investigated. Previous work already showed that transformer models can successfully support code completion in a cross-project setting. However, it is unclear whether LLM are able to generalize to inputs having lengths not seen during training. For example, it is known that training a model on short instances allows to substantially reduce the training cost. However, the extent to which such a model would provide good performance on sequences having lengths not seen during training is not known. Many recent works in Natural Language Processing (NLP) tackled this problem in the context of decoder-only LLMs, i.e., xPOS and ALiBi. To assess if these solutions extend to encoder-decoder LLMs usually adopted in the code-related tasks, we present a large empirical study evaluating this generalization property of these and other encoding schemes proposed in the literature, namely Sinusoidal, xPOS, ALiBi, and T5. We found that none of these solutions successfully generalize to unseen lengths and that the only safe solution is to ensure the representativeness in the training set of all lengths likely to be encountered at inference time.

[Arxiv](https://arxiv.org/abs/2501.05051)