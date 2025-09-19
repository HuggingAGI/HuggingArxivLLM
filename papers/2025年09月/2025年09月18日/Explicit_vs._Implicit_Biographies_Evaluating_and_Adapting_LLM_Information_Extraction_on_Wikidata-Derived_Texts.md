# # 显式传记与隐式传记对比：针对维基数据衍生文本的大型语言模型信息抽取评估与适配

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Explicit vs. Implicit Biographies: Evaluating and Adapting LLM Information Extraction on Wikidata-Derived Texts

# 摘要

> 在自然语言处理（NLP）领域，文本隐含性始终是一大难题——传统方法往往依赖显式表述来识别实体及其关系。以“Zuhdi每周日去教堂”这句话为例：人类读者能轻松推断出Zuhdi与基督教的关联，但要让机器自动完成这种推理，却并非易事。值得注意的是，大型语言模型（LLMs）已在文本理解、信息提取（IE）等NLP下游任务中展现出强大实力。
  本研究聚焦文本隐含性对预训练大型语言模型（LLMs）——包括LLaMA 2.3、DeepSeekV1和Phi1.5——在IE任务中的影响。我们构建了两个包含10k条隐含与显式传记信息表述的合成数据集，以此评估其对LLM性能的影响，并探究微调隐含数据能否增强模型在隐含推理任务中的泛化能力。
  研究还针对LLMs在IE任务中的内部推理过程展开实验，重点探究其处理隐含与显式上下文的机制。结果显示，通过LoRA（低秩适应）微调LLM模型，能有效提升其从隐含文本中提取信息的性能，进而增强模型的可解释性与可靠性。

> Text Implicitness has always been challenging in Natural Language Processing (NLP), with traditional methods relying on explicit statements to identify entities and their relationships. From the sentence "Zuhdi attends church every Sunday", the relationship between Zuhdi and Christianity is evident for a human reader, but it presents a challenge when it must be inferred automatically. Large language models (LLMs) have proven effective in NLP downstream tasks such as text comprehension and information extraction (IE).
  This study examines how textual implicitness affects IE tasks in pre-trained LLMs: LLaMA 2.3, DeepSeekV1, and Phi1.5. We generate two synthetic datasets of 10k implicit and explicit verbalization of biographic information to measure the impact on LLM performance and analyze whether fine-tuning implicit data improves their ability to generalize in implicit reasoning tasks.
  This research presents an experiment on the internal reasoning processes of LLMs in IE, particularly in dealing with implicit and explicit contexts. The results demonstrate that fine-tuning LLM models with LoRA (low-rank adaptation) improves their performance in extracting information from implicit texts, contributing to better model interpretability and reliability.

[Arxiv](https://arxiv.org/abs/2509.14943)