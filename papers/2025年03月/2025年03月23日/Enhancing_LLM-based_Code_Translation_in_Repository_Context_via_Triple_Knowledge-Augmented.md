# 通过三元知识增强提升基于LLM的代码翻译效果

发布时间：2025年03月23日

`LLM应用` `软件工程` `代码翻译`

> Enhancing LLM-based Code Translation in Repository Context via Triple Knowledge-Augmented

# 摘要

> 大型语言模型 (LLMs) 在函数级别代码翻译中表现出色，但受限于复杂依赖和上下文，在仓库级上下文代码翻译中的性能仍有待提升，这影响了其在工业环境中的应用。为此，我们提出了一种新型基于 LLM 的代码翻译技术 K-Trans，通过三重知识增强来提升 LLM 在真实软件开发中基于仓库上下文的翻译质量。

K-Trans 的工作流程分为三步：首先，它通过提取目标语言代码库、待翻译仓库及先前翻译结果的相关信息来构建翻译知识库。其次，对于每个待翻译的函数，K-Trans 检索相关三重知识，包括目标语言代码示例、依赖使用案例及成功的翻译函数对，作为参考以增强 LLM 的翻译能力。最后，K-Trans 利用检索到的三重知识构建增强型翻译提示，并借助 LLM 生成翻译代码，同时保留仓库上下文。此外，K-Trans 还利用 LLM 进行自我调试，以提升翻译的正确性。

实验结果表明，K-Trans 在 pass@1 和 CodeBLEU 方面分别取得了 19.4% 和 40.2% 的相对提升，以及 0.138 的绝对提升，显著优于从以往工作中改编的基线方法。值得注意的是，每种知识对 K-Trans 处理仓库级上下文代码翻译的有效性都有显著贡献，其中依赖使用案例的贡献尤为突出。此外，随着自我进化过程的推进，知识库能够持续提升 LLM 在仓库级代码翻译各个方面的能力。

> Large language models (LLMs) have behaved well in function-level code translation without repository-level context. However, the performance of LLMs in repository-level context code translation remains suboptimal due to complex dependencies and context, hindering their adoption in industrial settings. In this work, we propose a novel LLM-based code translation technique K-Trans, which leverages triple knowledge augmentation to enhance LLM's translation quality under repository context in real-world software development. First, K-Trans constructs a translation knowledge base by extracting relevant information from target-language codebases, the repository being translated, and prior translation results. Second, for each function to be translated, K-Trans retrieves relevant triple knowledge, including target-language code samples, dependency usage examples, and successful translation function pairs, serving as references to enhance LLM for translation. Third, K-Trans constructs a knowledge-augmented translation prompt using the retrieved triple knowledge and employs LLMs to generate the translated code while preserving repository context. It further leverages LLMs for self-debugging, enhancing translation correctness.
  The experiments show that K-Trans substantially outperforms the baseline adapted from previous work by 19.4%/40.2% relative improvement in pass@1 and 0.138 in CodeBLEU. It is important to note that the results also demonstrate that each knowledge significantly contributes to K-Trans's effectiveness in handling repository-level context code translation, with dependency usage examples making the most notable contribution. Moreover, as the self-evolution process progresses, the knowledge base continuously enhances the LLM's performance across various aspects of the repository-level code translation.

[Arxiv](https://arxiv.org/abs/2503.18305)