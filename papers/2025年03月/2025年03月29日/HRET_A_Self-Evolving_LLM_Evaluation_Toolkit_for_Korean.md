# HRET：专为韩语设计的自我演进型 LLM 评估工具包

发布时间：2025年03月29日

`其他` `评估框架`

> HRET: A Self-Evolving LLM Evaluation Toolkit for Korean

# 摘要

> 韩语大型语言模型（LLMs）的最新进展推动了众多基准测试和评估方法的诞生，但缺乏统一的评估框架导致结果不一致且可比性不足。为解决这一问题，我们推出了HRET Haerae评估工具包——一个专为韩语LLMs设计的开源、自我演进的评估框架。HRET整合了基于logit的评分、精确匹配、语言不一致惩罚以及将LLM作为裁判的评估等多种方法。其模块化、基于注册表的架构集成了HAE-RAE Bench、KMMLU、KUDGE、HRM8K等主要基准测试，以及vLLM、HuggingFace、与OpenAI兼容的端点等多个推理后端。通过自动化流水线实现持续演进，HRET为韩语NLP研究提供了坚实的基础，确保研究的可重复性、公平性和透明性。

> Recent advancements in Korean large language models (LLMs) have spurred numerous benchmarks and evaluation methodologies, yet the lack of a standardized evaluation framework has led to inconsistent results and limited comparability. To address this, we introduce HRET Haerae Evaluation Toolkit, an open-source, self-evolving evaluation framework tailored specifically for Korean LLMs. HRET unifies diverse evaluation methods, including logit-based scoring, exact-match, language-inconsistency penalization, and LLM-as-a-Judge assessments. Its modular, registry-based architecture integrates major benchmarks (HAE-RAE Bench, KMMLU, KUDGE, HRM8K) and multiple inference backends (vLLM, HuggingFace, OpenAI-compatible endpoints). With automated pipelines for continuous evolution, HRET provides a robust foundation for reproducible, fair, and transparent Korean NLP research.

[Arxiv](https://arxiv.org/abs/2503.22968)