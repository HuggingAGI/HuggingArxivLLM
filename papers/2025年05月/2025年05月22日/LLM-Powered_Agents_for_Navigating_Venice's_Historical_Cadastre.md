# LLM驱动智能体，助力探索威尼斯历史地籍

发布时间：2025年05月22日

`LLM应用

分类理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于处理历史地籍数据，通过文本到程序的框架将自然语言查询转换为可执行代码，从而解决实际问题。这属于LLM的应用层面，因此归类为LLM应用。` `城市历史` `地籍数据`

> LLM-Powered Agents for Navigating Venice's Historical Cadastre

# 摘要

> 地籍数据是研究城市历史组织的重要信息来源，但由于格式多样和人工标注，常常非标准化，给大规模分析带来阻碍。我们以威尼斯1740年至1808年这一关键历史时期为例，研究了从古共和国到旧制度灭亡后的城市变迁。这一时期的地籍数据因数量庞大且缺乏统一结构，带来了独特挑战，而我们的方法成功应对了这些难题，使我们能够生成连接过去与现在城市景观的空间查询。

我们提出了一种基于大型语言模型（LLMs）的文本到程序框架，能够将自然语言查询转换为可执行代码，用于处理历史地籍记录。我们的方法结合了两种互补技术：一种是针对特定地籍信息的结构化查询的文本到SQL方法，另一种是用于需要自定义数据操作的复杂分析的文本到Python方法。

我们还提出了一种分类法，根据历史研究问题的复杂性和分析需求，将其映射到最合适的技术方法。该框架通过系统执行一致性的调查以及对生成答案的定性分析得到了支持。通过确保可解释性并利用可验证的程序输出来最小化幻觉，我们证明了该系统在重构威尼斯人口信息、房产特征以及时空比较方面的有效性。


> Cadastral data reveal key information about the historical organization of cities but are often non-standardized due to diverse formats and human annotations, complicating large-scale analysis. We explore as a case study Venice's urban history during the critical period from 1740 to 1808, capturing the transition following the fall of the ancient Republic and the Ancien Régime. This era's complex cadastral data, marked by its volume and lack of uniform structure, presents unique challenges that our approach adeptly navigates, enabling us to generate spatial queries that bridge past and present urban landscapes. We present a text-to-programs framework that leverages Large Language Models (LLMs) to translate natural language queries into executable code for processing historical cadastral records. Our methodology implements two complementary techniques: a text-to-SQL approach for handling structured queries about specific cadastral information, and a text-to-Python approach for complex analytical operations requiring custom data manipulation. We propose a taxonomy that classifies historical research questions based on their complexity and analytical requirements, mapping them to the most appropriate technical approach. This framework is supported by an investigation into the execution consistency of the system, alongside a qualitative analysis of the answers it produces. By ensuring interpretability and minimizing hallucination through verifiable program outputs, we demonstrate the system's effectiveness in reconstructing past population information, property features, and spatiotemporal comparisons in Venice.

[Arxiv](https://arxiv.org/abs/2505.17148)