# # PredicateFix：利用桥接谓词解决静态分析问题

发布时间：2025年03月15日

`RAG` `软件工程` `软件开发工具`

> PredicateFix: Repairing Static Analysis Alerts with Bridging Predicates

# 摘要

> 利用大型语言模型（LLMs）修复程序代码中的静态分析警报正变得广泛应用且成效显著。然而，这些模型在处理复杂和不常见的警报时，常因幻觉问题而导致性能受限。检索增强生成（RAG）通过为模型提供相关示例来解决这一问题，但现有方法因示例质量不高而效果受限。
    为突破这一限制，本文提出利用分析规则中的谓词作为桥梁，连接警报与干净代码库中的关键代码片段。基于此，我们设计了一种自动检索关键示例的算法，并构建了PredicateFix这一RAG流水线，用于修复CodeQL代码检查器及其他Golang静态分析器标记的警报。实验结果表明，PredicateFix在多个LLMs上的正确修复率提升了27.1% ~ 72.5%，显著优于现有基线方法。

> Using Large Language Models (LLMs) to fix static analysis alerts in program code is becoming increasingly popular and helpful. However, these models often have the problem of hallucination and perform poorly for complex and less common alerts, limiting their performance. Retrieval-augmented generation (RAG) aims to solve this problem by providing the model with a relevant example, but the unsatisfactory quality of such examples challenges the effectiveness of existing approaches.
  To address this challenge, this paper utilizes the predicates in the analysis rule, which can serve as a bridge between the alert and relevant code snippets within a clean code corpus, called key examples. Based on the above insight, we propose an algorithm to retrieve key examples for an alert automatically. Then, we build PredicateFix as a RAG pipeline to fix alerts flagged by the CodeQL code checker and another imperative static analyzer for Golang. Evaluation with multiple LLMs shows that PredicateFix increases the number of correct repairs by 27.1% ~ 72.5%, significantly outperforming other baseline RAG approaches.

[Arxiv](https://arxiv.org/abs/2503.12205)