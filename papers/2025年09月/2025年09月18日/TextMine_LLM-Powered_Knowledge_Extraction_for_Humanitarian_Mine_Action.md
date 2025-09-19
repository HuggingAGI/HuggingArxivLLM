# TextMine：LLM驱动的人道主义排雷行动知识提取

发布时间：2025年09月18日

`LLM应用` `能源与环保`

> TextMine: LLM-Powered Knowledge Extraction for Humanitarian Mine Action

# 摘要

> 人道主义排雷行动积累了丰富的最佳实践知识，但大量知识仍被困在非结构化报告中。为此，我们提出了TextMine——一个本体引导的处理流程，它利用大型语言模型从HMA文本中提取知识三元组。TextMine整合了文档分块、领域感知提示、三元组提取，以及基于参考和LLM评判的双重评估机制。我们还构建了首个HMA本体，并创建了一个真实世界排雷报告的精选数据集。实验结果显示，与基线方法相比，本体对齐的提示能将提取准确率提升44.2%，减少22.5%的幻觉现象，同时将格式一致性提高20.9%。尽管TextMine是在柬埔寨报告上验证的，但其可适应全球排雷行动或其他领域，助力将非结构化数据转化为结构化知识。

> Humanitarian Mine Action has generated extensive best-practice knowledge, but much remains locked in unstructured reports. We introduce TextMine, an ontology-guided pipeline that uses Large Language Models to extract knowledge triples from HMA texts. TextMine integrates document chunking, domain-aware prompting, triple extraction, and both reference-based and LLM-as-a-Judge evaluation. We also create the first HMA ontology and a curated dataset of real-world demining reports. Experiments show ontology-aligned prompts boost extraction accuracy by 44.2%, cut hallucinations by 22.5%, and improve format conformance by 20.9% over baselines. While validated on Cambodian reports, TextMine can adapt to global demining efforts or other domains, transforming unstructured data into structured knowledge.

[Arxiv](https://arxiv.org/abs/2509.15098)