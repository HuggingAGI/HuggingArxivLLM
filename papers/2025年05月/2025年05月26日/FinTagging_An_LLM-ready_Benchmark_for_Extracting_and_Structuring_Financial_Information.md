# FinTagging: 适用于LLM的财务信息提取与结构化基准测试

发布时间：2025年05月26日

`LLM应用` `金融数据处理`

> FinTagging: An LLM-ready Benchmark for Extracting and Structuring Financial Information

# 摘要

> 我们推出首个全面且表格感知的XBRL基准测试——FinTagging，旨在评估大型语言模型（LLMs）在基于XBRL的财务报告中进行结构化信息提取和语义对齐的能力。与之前将XBRL标记 oversimplify 为扁平多类分类且仅关注叙述性文本的基准不同，FinTagging将XBRL标记问题分解为两个子任务：FinNI用于财务实体提取，FinCL用于基于 taxonomy 的概念对齐。它要求模型在非结构化文本和结构化表格中联合提取事实，并与完整的10,000+美国通用会计准则 taxonomy 进行对齐，从而实现对模型能力的全面、精细评估。我们在零-shot 设置下评估了多种 LLMs，系统分析了它们在两个子任务上的表现以及整体标记准确性。我们的结果显示，尽管LLMs在信息提取方面表现出强大的泛化能力，但在精细的概念对齐上存在困难，尤其是在区分 taxonomy 中密切相关条目时。这些发现突显了现有LLMs在完全自动化XBRL标记方面的局限性，并强调了改进语义推理和架构感知建模的必要性，以满足准确财务披露的需求。代码可在我们的GitHub仓库获取，数据则在我们的Hugging Face仓库中提供。

> We introduce FinTagging, the first full-scope, table-aware XBRL benchmark designed to evaluate the structured information extraction and semantic alignment capabilities of large language models (LLMs) in the context of XBRL-based financial reporting. Unlike prior benchmarks that oversimplify XBRL tagging as flat multi-class classification and focus solely on narrative text, FinTagging decomposes the XBRL tagging problem into two subtasks: FinNI for financial entity extraction and FinCL for taxonomy-driven concept alignment. It requires models to jointly extract facts and align them with the full 10k+ US-GAAP taxonomy across both unstructured text and structured tables, enabling realistic, fine-grained evaluation. We assess a diverse set of LLMs under zero-shot settings, systematically analyzing their performance on both subtasks and overall tagging accuracy. Our results reveal that, while LLMs demonstrate strong generalization in information extraction, they struggle with fine-grained concept alignment, particularly in disambiguating closely related taxonomy entries. These findings highlight the limitations of existing LLMs in fully automating XBRL tagging and underscore the need for improved semantic reasoning and schema-aware modeling to meet the demands of accurate financial disclosure. Code is available at our GitHub repository and data is at our Hugging Face repository.

[Arxiv](https://arxiv.org/abs/2505.20650)