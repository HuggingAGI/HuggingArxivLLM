# UnStar: 基于自教反样本推理的LLM遗忘学习

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要探讨了反学习（unlearning）在大型语言模型（LLMs）中的应用，特别是通过反样本（counterexamples）来实现反学习的方法。论文提出了新的概念和方法，如反样本诱导反学习、误导性理由生成反样本等，并展示了这些方法在LLMs中的有效性。这些内容属于对LLMs的理论研究和改进，因此归类为“LLM理论”。` `机器学习` `隐私保护`

> UnStar: Unlearning with Self-Taught Anti-Sample Reasoning for LLMs

# 摘要

> 机器学习的关键要素包括训练数据样本、学习模式的模型和优化准确性的损失函数。类似地，反学习可以通过反样本、反学习方法和反向损失函数来实现。尽管已有研究探索了反学习方法和反向损失函数，但反样本的潜力尚未充分挖掘。本文提出UnSTAR：一种用于LLMs的自学反样本推理反学习方法。我们的贡献有三点：首先，提出了反样本诱导反学习的新概念；其次，通过误导性理由生成反样本，逆转已学关联并加速反学习；第三，实现了细粒度的目标反学习，选择性移除特定关联而不影响相关知识——这是以往工作无法做到的。结果表明，反样本为LLMs提供了一种高效、精准的反学习策略，为隐私保护机器学习和模型修改开辟了新路径。

> The key components of machine learning are data samples for training, model for learning patterns, and loss function for optimizing accuracy. Analogously, unlearning can potentially be achieved through anti-data samples (or anti-samples), unlearning method, and reversed loss function. While prior research has explored unlearning methods and reversed loss functions, the potential of anti-samples remains largely untapped. In this paper, we introduce UnSTAR: Unlearning with Self-Taught Anti-Sample Reasoning for large language models (LLMs). Our contributions are threefold; first, we propose a novel concept of anti-sample-induced unlearning; second, we generate anti-samples by leveraging misleading rationales, which help reverse learned associations and accelerate the unlearning process; and third, we enable fine-grained targeted unlearning, allowing for the selective removal of specific associations without impacting related knowledge - something not achievable by previous works. Results demonstrate that anti-samples offer an efficient, targeted unlearning strategy for LLMs, opening new avenues for privacy-preserving machine learning and model modification.

[Arxiv](https://arxiv.org/abs/2410.17050)