# 关于数学副驾驶的数据：机器学习证明的更优呈现途径

发布时间：2024年12月19日

`LLM应用` `人工智能`

> Data for Mathematical Copilots: Better Ways of Presenting Proofs for Machine Learning

# 摘要

> 通常用于训练和评估基于人工智能的数学助手（主要是大型语言模型）数学能力的一系列数据集存在不少缺陷。这些缺陷包括数学复杂程度受限，通常不超过大学低年级数学水平，存在二元评级协议等问题，这使得综合性的基于证明的评估套件难以构建。我们对这些限制进行了系统探讨，并认为要增强大型语言模型的能力，或者基于人工智能的数学助手（助手或“思想伙伴”）取得任何新进展，都需要在数学数据集的设计和数学能力的评估标准上实现范式转变：要摆脱基于结果的数据集（从定理陈述到定理证明），把数学研究实践的丰富层面转化为大型语言模型可训练的数据。比如数学工作流（创建新数学时经常执行的原子序列，可能与子领域相关的任务），这是证明发现过程的重要部分。此外，我们建议数学数据集开发者考虑 G. Pólya 在 1949 年提出的“有动机的证明”概念，这可为提供更优证明学习信号的数据集提供蓝图，缓解上述部分限制。最后，我们为数据集引入数学数据表，拓展了通用的、与数据集无关的数据表变体：我们提供了专为数学数据集设计的问卷，力促数据集创建者将其与数据集一同包含在内。这既能让创建者知晓其数据集的潜在局限，又能让读者从训练和评估数学助手的角度轻松对其进行评估。

> The suite of datasets commonly used to train and evaluate the mathematical capabilities of AI-based mathematical copilots (primarily large language models) exhibit several shortcomings. These limitations include a restricted scope of mathematical complexity, typically not exceeding lower undergraduate-level mathematics, binary rating protocols and other issues, which makes comprehensive proof-based evaluation suites difficult. We systematically explore these limitations and contend that enhancing the capabilities of large language models, or any forthcoming advancements in AI-based mathematical assistants (copilots or "thought partners"), necessitates a paradigm shift in the design of mathematical datasets and the evaluation criteria of mathematical ability: It is necessary to move away from result-based datasets (theorem statement to theorem proof) and convert the rich facets of mathematical research practice to data LLMs can train on. Examples of these are mathematical workflows (sequences of atomic, potentially subfield-dependent tasks that are often performed when creating new mathematics), which are an important part of the proof-discovery process. Additionally, we advocate for mathematical dataset developers to consider the concept of "motivated proof", introduced by G. Pólya in 1949, which can serve as a blueprint for datasets that offer a better proof learning signal, alleviating some of the mentioned limitations. Lastly, we introduce math datasheets for datasets, extending the general, dataset-agnostic variants of datasheets: We provide a questionnaire designed specifically for math datasets that we urge dataset creators to include with their datasets. This will make creators aware of potential limitations of their datasets while at the same time making it easy for readers to assess it from the point of view of training and evaluating mathematical copilots.

[Arxiv](https://arxiv.org/abs/2412.15184)