# GPT-4o mini 和 Gemini 2.0 能否零样本预测精细时尚产品属性？——零样本分析

发布时间：2025年07月14日

`LLM应用` `时尚零售`

> Can GPT-4o mini and Gemini 2.0 Flash Predict Fine-Grained Fashion Product Attributes? A Zero-Shot Analysis

# 摘要

> 时尚零售的核心是理解产品的能力。产品属性识别不仅帮助业务流程理解商品，还能通过优化质量属性提升消费者在海量商品中的浏览体验，从而构建井然有序的产品目录。最终，产品属性识别直接影响了客户的“发现体验”。尽管大型语言模型（LLMs）在多模态数据理解方面表现出色，但其在细粒度时尚属性识别方面的潜力仍待挖掘。本文对GPT-4o-mini和Gemini 2.0 Flash等前沿LLMs进行了零样本评估，这些模型在性能、速度和成本效益之间实现了平衡。我们采用DeepFashion-MultiModal数据集对这些模型的时尚产品属性识别能力进行了全面测试，覆盖了18类时尚属性。仅使用图像作为输入的实验设置为研究创建了受控环境。结果显示，Gemini 2.0 Flash在所有属性上的宏观F1得分为56.79%，表现最为突出，而GPT-4o-mini的得分为43.28%。通过深入的错误分析，本研究为将这些LLMs应用于实际的电商产品属性识别任务提供了实用建议，并强调了领域特定微调的重要性。这项研究不仅为时尚AI和多模态属性提取领域的未来研究奠定了基础，也为行业应用提供了有价值的参考。

> The fashion retail business is centered around the capacity to comprehend products. Product attribution helps in comprehending products depending on the business process. Quality attribution improves the customer experience as they navigate through millions of products offered by a retail website. It leads to well-organized product catalogs. In the end, product attribution directly impacts the 'discovery experience' of the customer. Although large language models (LLMs) have shown remarkable capabilities in understanding multimodal data, their performance on fine-grained fashion attribute recognition remains under-explored. This paper presents a zero-shot evaluation of state-of-the-art LLMs that balance performance with speed and cost efficiency, mainly GPT-4o-mini and Gemini 2.0 Flash. We have used the dataset DeepFashion-MultiModal (https://github.com/yumingj/DeepFashion-MultiModal) to evaluate these models in the attribution tasks of fashion products. Our study evaluates these models across 18 categories of fashion attributes, offering insight into where these models excel. We only use images as the sole input for product information to create a constrained environment. Our analysis shows that Gemini 2.0 Flash demonstrates the strongest overall performance with a macro F1 score of 56.79% across all attributes, while GPT-4o-mini scored a macro F1 score of 43.28%. Through detailed error analysis, our findings provide practical insights for deploying these LLMs in production e-commerce product attribution-related tasks and highlight the need for domain-specific fine-tuning approaches. This work also lays the groundwork for future research in fashion AI and multimodal attribute extraction.

[Arxiv](https://arxiv.org/abs/2507.09950)