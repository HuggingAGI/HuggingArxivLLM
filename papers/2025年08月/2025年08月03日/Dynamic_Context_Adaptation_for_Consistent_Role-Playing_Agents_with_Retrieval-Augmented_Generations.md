# 动态上下文适应，实现一致的角色扮演能力，通过检索增强生成技术。

发布时间：2025年08月03日

`RAG` `角色扮演` `自动化`

> Dynamic Context Adaptation for Consistent Role-Playing Agents with Retrieval-Augmented Generations

# 摘要

> 我们提出了AMADEUS框架，它由自适应上下文感知文本分割器（ACTS）、引导选择（GS）和属性提取器（AE）三部分组成。ACTS为每个角色找到最优的文本块长度和层次上下文。AE从GS检索到的文本块中识别出角色的一般属性，并将这些属性作为最终上下文，即使在回答超出知识范围的问题时也能保持 robust 的人格一致性。为了促进基于RAG的角色扮演自动化（RPA）的发展与评估，我们构建了CharacterRAG，这是一个角色扮演数据集，包含15个不同虚构角色的 persona 文档，总计976K字符，以及450对问答。我们发现，我们的框架不仅有效建模了角色所拥有的知识，还涵盖了个性等各类属性。

> We propose AMADEUS, which is composed of Adaptive Context-aware Text Splitter (ACTS), Guided Selection (GS), and Attribute Extractor (AE). ACTS finds an optimal chunk length and hierarchical contexts for each character. AE identifies a character's general attributes from the chunks retrieved by GS and uses these attributes as a final context to maintain robust persona consistency even when answering out of knowledge questions. To facilitate the development and evaluation of RAG-based RPAs, we construct CharacterRAG, a role-playing dataset that consists of persona documents for 15 distinct fictional characters totaling 976K written characters, and 450 question and answer pairs. We find that our framework effectively models not only the knowledge possessed by characters, but also various attributes such as personality.

[Arxiv](https://arxiv.org/abs/2508.02016)