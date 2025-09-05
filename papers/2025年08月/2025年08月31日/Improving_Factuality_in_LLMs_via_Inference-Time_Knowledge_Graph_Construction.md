# 通过推理时知识图谱构建提升大型语言模型（LLMs）的事实性

发布时间：2025年08月31日

`RAG` `基础理论`

> Improving Factuality in LLMs via Inference-Time Knowledge Graph Construction

# 摘要

> 大型语言模型（LLMs）常因参数记忆受限而难以生成事实一致的答案。检索增强生成（RAG）方法通过在推理时整合可信源的外部知识来解决这一问题，但这类方法通常将知识视为非结构化文本，从而限制了其支持组合推理和识别事实不一致的能力。为克服这些局限，我们提出一种新型框架，在推理过程中动态构建和扩展知识图谱（KGs），整合从LLMs提取的内部知识与外部源检索的外部信息。该方法首先通过提示从问题中提取种子知识图谱，随后利用LLM的潜在知识进行迭代扩展，再通过外部检索对图谱进行选择性优化，以增强事实覆盖并纠正不准确之处。我们在三个不同的事实问答基准上进行了评估，结果显示，与基线提示方法和静态知识图谱增强方法相比，我们的方法在事实准确性、答案精确性和可解释性上均有持续提升。研究表明，推理时知识图谱构建是一个极具前景的方向，能以结构化、可解释且可扩展的方式有效增强LLM的事实性。

> Large Language Models (LLMs) often struggle with producing factually consistent answers due to limitations in their parametric memory. Retrieval-Augmented Generation (RAG) methods address this issue by incorporating external knowledge from trusted sources at inference time. However, such methods typically treat knowledge as unstructured text, which limits their ability to support compositional reasoning and identify factual inconsistencies. To overcome these limitations, we propose a novel framework that dynamically constructs and expands knowledge graphs (KGs) during inference, integrating both internal knowledge extracted from LLMs and external information retrieved from external sources. Our method begins by extracting a seed KG from the question via prompting, followed by iterative expansion using the LLM's latent knowledge. The graph is then selectively refined through external retrieval, enhancing factual coverage and correcting inaccuracies. We evaluate our approach on three diverse factual QA benchmarks, demonstrating consistent improvements in factual accuracy, answer precision, and interpretability over baseline prompting and static KG-augmented methods. Our findings suggest that inference-time KG construction is a promising direction for enhancing LLM factuality in a structured, interpretable, and scalable manner.

[Arxiv](https://arxiv.org/abs/2509.03540)