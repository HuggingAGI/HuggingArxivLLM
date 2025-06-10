# 超越表面相似性：基于LLM的测试重构评估——结构与语义的深度考量

发布时间：2025年06月07日

`LLM应用` `软件工程` `单元测试`

> Beyond Surface Similarity: Evaluating LLM-Based Test Refactorings with Structural and Semantic Awareness

# 摘要

> 大型语言模型（LLMs）正被广泛用于自动重构单元测试，旨在提升可读性、命名规范性和结构清晰度，同时保持功能性行为不变。然而，评估这种重构仍具挑战性：传统指标如CodeBLEU对重命名和结构编辑过于敏感，而基于嵌入的相似性方法虽能捕捉语义，却忽略了可读性和模块化。为此，我们提出了CTSES，一个综合指标，整合了CodeBLEU、METEOR和ROUGE-L，以平衡行为保持、词汇质量和结构对齐。我们使用Chain-of-Thought提示方法，对GPT-4和Mistral-Large-2407自动重构的超过5,000个测试套件进行了评估，涵盖了Defects4J和SF110两个 established Java基准测试。实验结果表明，CTSES提供了更忠实且可解释的评估，与开发人员期望和人类直觉的契合度显著优于现有指标。

> Large Language Models (LLMs) are increasingly employed to automatically refactor unit tests, aiming to enhance readability, naming, and structural clarity while preserving functional behavior. However, evaluating such refactorings remains challenging: traditional metrics like CodeBLEU are overly sensitive to renaming and structural edits, whereas embedding-based similarities capture semantics but ignore readability and modularity. We introduce CTSES, a composite metric that integrates CodeBLEU, METEOR, and ROUGE-L to balance behavior preservation, lexical quality, and structural alignment. CTSES is evaluated on over 5,000 test suites automatically refactored by GPT-4o and Mistral-Large-2407, using Chain-of-Thought prompting, across two established Java benchmarks: Defects4J and SF110. Our results show that CTSES yields more faithful and interpretable assessments, better aligned with developer expectations and human intuition than existing metrics.

[Arxiv](https://arxiv.org/abs/2506.06767)