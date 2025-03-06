# # CURVALID：基于几何引导的对抗提示检测

发布时间：2025年03月05日

`LLM理论` `人工智能`

> CURVALID: Geometrically-guided Adversarial Prompt Detection

# 摘要

> 对抗性提示能够越狱攻击大型语言模型（LLMs），诱导其产生不良行为，这对LLMs的安全部署构成了重大威胁。当前的缓解策略主要依赖于激活模型的内置防御机制或对其进行微调，但对抗性提示与良性提示之间的本质区别尚未被充分理解。在本研究中，我们提出了CurvaLID——一种全新的防御框架，通过分析对抗性提示的几何特性，实现高效检测。该框架与LLM的类型无关，可统一应对各种对抗性提示和LLM架构。CurvaLID基于对文本提示的几何分析，揭示了其潜在差异。我们通过Whewell方程将曲率的概念理论性地扩展到n维词嵌入空间，【数学公式】，从而能够量化局部几何特性，包括语义偏移和潜在流形中的曲率。此外，我们采用局部内在维度（LID）来捕获对抗性子空间中文本提示的几何特征。研究发现，对抗性提示在几何特性上与良性提示存在根本差异。实验结果表明，CurvaLID在检测和拒绝对抗性查询方面表现出色，为更安全的LLM部署铺平了道路。源代码可在https://github.com/Cancanxxx/CurvaLID获取。

> Adversarial prompts capable of jailbreaking large language models (LLMs) and inducing undesirable behaviours pose a significant obstacle to their safe deployment. Current mitigation strategies rely on activating built-in defence mechanisms or fine-tuning the LLMs, but the fundamental distinctions between adversarial and benign prompts are yet to be understood. In this work, we introduce CurvaLID, a novel defense framework that efficiently detects adversarial prompts by leveraging their geometric properties. It is agnostic to the type of LLM, offering a unified detection framework across diverse adversarial prompts and LLM architectures. CurvaLID builds on the geometric analysis of text prompts to uncover their underlying differences. We theoretically extend the concept of curvature via the Whewell equation into an $n$-dimensional word embedding space, enabling us to quantify local geometric properties, including semantic shifts and curvature in the underlying manifolds. Additionally, we employ Local Intrinsic Dimensionality (LID) to capture geometric features of text prompts within adversarial subspaces. Our findings reveal that adversarial prompts differ fundamentally from benign prompts in terms of their geometric characteristics. Our results demonstrate that CurvaLID delivers superior detection and rejection of adversarial queries, paving the way for safer LLM deployment. The source code can be found at https://github.com/Cancanxxx/CurvaLID

[Arxiv](https://arxiv.org/abs/2503.03502)