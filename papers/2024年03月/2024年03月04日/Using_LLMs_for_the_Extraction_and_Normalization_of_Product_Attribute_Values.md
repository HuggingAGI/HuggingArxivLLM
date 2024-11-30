# 运用 LLM 技术抽取并规范产品属性值，本研究旨在探索这一方法在处理产品信息时的高效性和准确性。

发布时间：2024年03月04日

`LLM应用`

> Using LLMs for the Extraction and Normalization of Product Attribute Values

# 摘要

> 电商网站的商品呈现常包括标题及描述文字，要实现诸如分类过滤或个性化推荐等特性，就需要从自由格式的产品描述中抽取出属性-值对。本研究利用OpenAI的GPT-3.5和GPT-4等大型语言模型探索了一种新可能——直接从商品标题和描述中抽取并规范化属性值。为此，我们构建了一个名为WDC PAVE的数据集，它涵盖了87个带有schema.org标注的网站商品信息，横跨五类商品，每类商品具有特定属性集合。数据集提供了人工验证过的两种形式的属性-值对：直接提取的原始值和规范化的标准值。其中，规范化过程涉及名称拓展、泛化处理、单位统一及字符串整理等操作。实验表明，GPT-4相较于基于预训练语言模型的方法提升了10%的性能表现，其F1得分高达91%。特别是在商品属性值的提取与规范化过程中，GPT-4展现出了与提取任务相当的优秀性能，尤其擅长于字符串整理和名称拓展任务。

> Product offers on e-commerce websites often consist of a textual product title and a textual product description. In order to provide features such as faceted product filtering or content-based product recommendation, the websites need to extract attribute-value pairs from the unstructured product descriptions. This paper explores the potential of using large language models (LLMs), such as OpenAI's GPT-3.5 and GPT-4, to extract and normalize attribute values from product titles and product descriptions. For our experiments, we introduce the WDC Product Attribute-Value Extraction (WDC PAVE) dataset. WDC PAVE consists of product offers from 87 websites that provide schema.org annotations. The offers belong to five different categories, each featuring a specific set of attributes. The dataset provides manually verified attribute-value pairs in two forms: (i) directly extracted values and (ii) normalized attribute values. The normalization of the attribute values requires systems to perform the following types of operations: name expansion, generalization, unit of measurement normalization, and string wrangling. Our experiments demonstrate that GPT-4 outperforms PLM-based extraction methods by 10%, achieving an F1-Score of 91%. For the extraction and normalization of product attribute values, GPT-4 achieves a similar performance to the extraction scenario, while being particularly strong at string wrangling and name expansion.

[Arxiv](https://arxiv.org/abs/2403.02130)