# CodeRAG：基于双图的支持性代码检索，助力现实世界代码生成。

发布时间：2025年04月14日

`RAG` `软件工程` `代码生成`

> CodeRAG: Supportive Code Retrieval on Bigraph for Real-World Code Generation

# 摘要

> 大型语言模型（LLMs）在自动化代码生成领域表现突出，尤其擅长生成独立代码等简单任务。然而，现实世界的代码生成往往依赖于特定的编程环境（如代码仓库），这些环境涉及复杂的依赖关系和领域知识，这对LLMs生成目标代码至关重要。本文提出了一种名为CodeRAG的检索增强代码生成（RAG）框架，旨在全面检索支持现实世界代码生成的相关代码。CodeRAG从需求出发，首先为当前仓库构建需求图，并在图中检索目标需求的子需求节点和相似需求节点。同时，它将仓库建模为DS代码图。随后，CodeRAG将这些相关需求节点映射到对应的代码节点，并将其作为LLM在DS代码图上推理的锚点。最后，CodeRAG引入了一种面向代码的代理推理过程，使LLMs能够无缝进行推理和全面检索，获取生成正确程序所需的支持代码。实验结果显示，与不使用RAG的场景相比，CodeRAG在GPT-4o和Gemini-Pro上的DevEval测试中，Pass@1分别提高了40.90和37.79。进一步对推理LLMs（如QwQ-32B）的测试证实了CodeRAG在各种类型LLMs中的适应性和有效性。此外，CodeRAG在与商业编程产品（如Copilot和Cursor）的对比中表现更优。我们还研究了CodeRAG在不同依赖类型下的性能，发现其在生成目标代码调用预定义跨文件代码片段的示例时表现尤为出色。这些结果充分展示了CodeRAG在解决现实世界仓库级编码挑战方面的潜力。

> Large language models (LLMs) have shown promising performance in automated code generation, especially excelling in simple tasks such as generating standalone codes. Different from simple tasks, real-world code generation usually depends on specific programming environment (e.g., code repositories). It contains complex dependencies and domain knowledge, which is needed for LLMs when generating target code snippets. In this paper, we propose CodeRAG, a retrieval-augmented code generation (RAG) framework to comprehensively retrieve supportive codes for real-world code generation. Beginning with the requirement, CodeRAG first constructs a requirement graph for the current repository, and retrieves sub- and similar- requirement nodes of the target requirement on the graph. Meanwhile, it models the repository into a DS-code graph. CodeRAG then maps these relevant requirement nodes into their corresponding code nodes, and treats these code nodes as archors for LLM reasoning on DS-code graph. Finally, CodeRAG introduces a code-oriented agentic reasoning process, seamlessly allowing LLMs to reason and comprehensively retrieve for supportive codes which LLMs' need for generating correct programs. Experiments show that CodeRAG achieves significant improvements (i.e., increasing 40.90 and 37.79 Pass@1 on GPT-4o and Gemini-Pro on DevEval) compared to no RAG scenarios. Further tests on reasoning LLMs (i.e., QwQ-32B) confirm CodeRAG's adaptability and efficacy across various types of LLMs. In addition, CodeRAG outperforms commercial programming products such as Copilit and Cursor. We further investigate the performance of our framework on different dependency types, and observe that CodeRAG is superior in generating examples where target codes invoke predefined cross-file code snippets. These results demonstrate CodeRAG's potential in solving real-world repo-level coding challenges.

[Arxiv](https://arxiv.org/abs/2504.10046)