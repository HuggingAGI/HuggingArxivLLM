# # 基于大型语言模型、集成开发环境和语义嵌入的自动移动方法重构

发布时间：2025年03月26日

`LLM应用` `软件工程` `软件开发工具`

> Leveraging LLMs, IDEs, and Semantic Embeddings for Automated Move Method Refactoring

# 摘要

> MOVEMETHOD 是一种标志性的重构方法。尽管有大量工具建议如何移动方法，但这些建议与专家的实际操作大相径庭。大型语言模型（LLMs）凭借其强大的训练和对代码自然性的依赖，本应能够精准识别哪些方法被误置于某个类中，以及哪些类更适合成为宿主。然而，我们的研究发现，LLMs 的建议中高达 80% 属于“幻觉”，可靠性堪忧。为此，我们推出了首个完全由 LLM 驱动的 MOVEMETHOD 重构助手，它实现了从建议到执行的全流程自动化。我们创新性地结合了静态分析和要求 LLM 自洽评估的机制，以过滤幻觉并优化建议。针对 LLM 上下文限制，我们采用了重构感知的检索增强生成（RAG），确保全局项目级别的推理。我们的方法 MM-assist 将 LLM、IDE、静态分析和语义相关性完美融合。在全面的实证评估中，MM-assist 在 Recall@1 和 Recall@3 上较现有最优方法提升了 1.7 倍，而在开源软件的 210 个实际重构案例中，其 Recall 率更是提升了 2.4 倍。此外，30 名开发者在实际使用一周后，对 MM-assist 的建议满意度高达 82.8%。这充分证明了 MM-assist 的强大效能与实用价值。

> MOVEMETHOD is a hallmark refactoring. Despite a plethora of research tools that recommend which methods to move and where, these recommendations do not align with how expert developers perform MOVEMETHOD. Given the extensive training of Large Language Models and their reliance upon naturalness of code, they should expertly recommend which methods are misplaced in a given class and which classes are better hosts. Our formative study of 2016 LLM recommendations revealed that LLMs give expert suggestions, yet they are unreliable: up to 80% of the suggestions are hallucinations. We introduce the first LLM fully powered assistant for MOVEMETHOD refactoring that automates its whole end-to-end lifecycle, from recommendation to execution. We designed novel solutions that automatically filter LLM hallucinations using static analysis from IDEs and a novel workflow that requires LLMs to be self-consistent, critique, and rank refactoring suggestions. As MOVEMETHOD refactoring requires global, projectlevel reasoning, we solved the limited context size of LLMs by employing refactoring-aware retrieval augment generation (RAG). Our approach, MM-assist, synergistically combines the strengths of the LLM, IDE, static analysis, and semantic relevance. In our thorough, multi-methodology empirical evaluation, we compare MM-assist with the previous state-of-the-art approaches. MM-assist significantly outperforms them: (i) on a benchmark widely used by other researchers, our Recall@1 and Recall@3 show a 1.7x improvement; (ii) on a corpus of 210 recent refactorings from Open-source software, our Recall rates improve by at least 2.4x. Lastly, we conducted a user study with 30 experienced participants who used MM-assist to refactor their own code for one week. They rated 82.8% of MM-assist recommendations positively. This shows that MM-assist is both effective and useful.

[Arxiv](https://arxiv.org/abs/2503.20934)