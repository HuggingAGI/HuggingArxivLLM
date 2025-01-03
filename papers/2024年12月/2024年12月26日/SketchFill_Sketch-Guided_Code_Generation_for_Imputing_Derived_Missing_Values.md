# SketchFill: 草图引导的代码生成，填补派生缺失值

发布时间：2024年12月26日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决数据科学中的缺失值填补问题，特别是通过提出一种新的方法（SketchFill）来增强LLMs的推理能力。这属于LLM在实际问题中的应用，因此分类为LLM应用。` `数据科学` `自动化`

> SketchFill: Sketch-Guided Code Generation for Imputing Derived Missing Values

# 摘要

> # 摘要
缺失值是数据科学中的一大难题，严重影响分析和预测的可靠性。缺失值填补（MVI）因其高度依赖领域知识而成为长期挑战。大型语言模型（LLMs）凭借其强大的内容理解和生成能力，已成为数据清理的有力工具，尤其在表格数据的MVI中表现出色。然而，尽管前景广阔，现有的LLM技术如上下文学习和思维链（CoT）在指导LLMs进行复杂推理以填补缺失值方面仍显不足，特别是在处理需要跨行跨列的数学公式和数据关系的衍生缺失值时。这一差距凸显了进一步推进LLM方法论以增强其推理能力，从而实现更可靠的填补结果的必要性。为此，我们提出了SketchFill，一种基于草图的新方法，用于指导LLMs生成准确的公式以填补缺失的数值。实验结果表明，SketchFill显著优于现有技术，比基于CoT的方法准确率提高了56.2%，比MetaGPT提高了78.8%。这为自动化数据清理设定了新标准，并推动了数值MVI领域的发展。

> Missing value is a critical issue in data science, significantly impacting the reliability of analyses and predictions. Missing value imputation (MVI) is a longstanding problem because it highly relies on domain knowledge. Large language models (LLMs) have emerged as a promising tool for data cleaning, including MVI for tabular data, offering advanced capabilities for understanding and generating content. However, despite their promise, existing LLM techniques such as in-context learning and Chain-of-Thought (CoT) often fall short in guiding LLMs to perform complex reasoning for MVI, particularly when imputing derived missing values, which require mathematical formulas and data relationships across rows and columns. This gap underscores the need for further advancements in LLM methodologies to enhance their reasoning capabilities for more reliable imputation outcomes. To fill this gap, we propose SketchFill, a novel sketch-based method to guide LLMs in generating accurate formulas to impute missing numerical values. Our experimental results demonstrate that SketchFill significantly outperforms state-of-the-art methods, achieving 56.2% higher accuracy than CoT-based methods and 78.8% higher accuracy than MetaGPT. This sets a new standard for automated data cleaning and advances the field of MVI for numerical values.

[Arxiv](https://arxiv.org/abs/2412.19113)