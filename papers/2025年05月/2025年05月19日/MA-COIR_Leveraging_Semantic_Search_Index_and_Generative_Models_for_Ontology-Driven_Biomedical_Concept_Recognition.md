# MA-COIR：基于语义搜索索引与生成模型的生物医学概念识别方法

发布时间：2025年05月19日

`LLM应用` `生物医学` `知识图谱`

> MA-COIR: Leveraging Semantic Search Index and Generative Models for Ontology-Driven Biomedical Concept Recognition

# 摘要

> 在生物医学文本处理中，概念识别是本体优化、知识图谱构建和概念关系发现的关键环节。传统方法依赖显式提及识别，难以捕捉文本中未明确表达的复杂概念。为此，我们提出了MA-COIR框架，将概念识别重新定义为索引-识别任务。通过为概念分配语义搜索索引（ssIDs），MA-COIR有效解决了本体条目中的歧义问题，显著提升了识别效率。我们采用基于预训练BART模型并针对小规模数据集进行微调的方法，大幅降低了计算需求，使领域专家更易于采用。此外，我们引入了大型语言模型（LLMs）生成的查询和合成数据，进一步提升了在资源匮乏环境下的识别能力。在CDR、HPO和HOIP三个场景下的实验结果表明，MA-COIR能够有效识别显式和隐式概念，且无需在推理阶段进行提及级别标注，为生物医学领域的概念识别技术带来了重要突破。我们的代码和构建的数据已在GitHub上开源，地址为https://github.com/sl-633/macoir-master。

> Recognizing biomedical concepts in the text is vital for ontology refinement, knowledge graph construction, and concept relationship discovery. However, traditional concept recognition methods, relying on explicit mention identification, often fail to capture complex concepts not explicitly stated in the text. To overcome this limitation, we introduce MA-COIR, a framework that reformulates concept recognition as an indexing-recognition task. By assigning semantic search indexes (ssIDs) to concepts, MA-COIR resolves ambiguities in ontology entries and enhances recognition efficiency. Using a pretrained BART-based model fine-tuned on small datasets, our approach reduces computational requirements to facilitate adoption by domain experts. Furthermore, we incorporate large language models (LLMs)-generated queries and synthetic data to improve recognition in low-resource settings. Experimental results on three scenarios (CDR, HPO, and HOIP) highlight the effectiveness of MA-COIR in recognizing both explicit and implicit concepts without the need for mention-level annotations during inference, advancing ontology-driven concept recognition in biomedical domain applications. Our code and constructed data are available at https://github.com/sl-633/macoir-master.

[Arxiv](https://arxiv.org/abs/2505.12964)