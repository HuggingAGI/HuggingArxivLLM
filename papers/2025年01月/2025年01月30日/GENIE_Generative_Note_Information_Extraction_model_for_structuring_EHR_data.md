# <翻译失败>

发布时间：2025年01月30日

`LLM应用

理由：这篇论文介绍了GENIE系统，该系统利用大型语言模型（LLMs）将非结构化临床文本转化为标准化格式的可用数据。GENIE通过微调小规模LLMs，实现了高效的信息提取，并在多个任务中超越了传统工具。这表明该研究主要关注如何将LLMs应用于医疗领域的实际问题，属于LLM应用的范畴。` `电子健康记录`

> GENIE: Generative Note Information Extraction model for structuring EHR data

# 摘要

> # 摘要
电子健康记录（EHRs）在推动医疗进步方面潜力巨大，提供了结合结构化信息和非结构化临床笔记的丰富纵向数据。然而，临床文本的非结构化特性给二次应用带来了挑战。传统方法如基于规则的系统或多阶段管道，常因配置耗时且难以适应不同医疗环境的笔记而受限。很少有系统能全面提取术语属性。尽管GPT-4和LLaMA 405B等大型语言模型（LLMs）在结构化任务中表现出色，但它们速度慢、成本高，难以大规模应用。为此，我们推出了GENIE，一个生成式笔记信息提取系统，利用LLMs将非结构化临床文本高效转化为标准化格式的可用数据。GENIE一次性处理整段文本，高精度提取实体、断言状态、位置、修饰符、值和目的。其端到端的统一方法简化了流程，减少了错误，并大幅降低了人工干预需求。通过强大的数据准备管道和微调的小规模LLMs，GENIE在多个信息提取任务中表现优异，超越了cTAKES和MetaMap等传统工具，并能处理更多属性提取。GENIE显著提升了医疗系统的实际应用性和可扩展性。我们开源了模型和测试数据，旨在促进合作，推动EHR结构化的进一步发展。

> Electronic Health Records (EHRs) hold immense potential for advancing healthcare, offering rich, longitudinal data that combines structured information with valuable insights from unstructured clinical notes. However, the unstructured nature of clinical text poses significant challenges for secondary applications. Traditional methods for structuring EHR free-text data, such as rule-based systems and multi-stage pipelines, are often limited by their time-consuming configurations and inability to adapt across clinical notes from diverse healthcare settings. Few systems provide a comprehensive attribute extraction for terminologies. While giant large language models (LLMs) like GPT-4 and LLaMA 405B excel at structuring tasks, they are slow, costly, and impractical for large-scale use. To overcome these limitations, we introduce GENIE, a Generative Note Information Extraction system that leverages LLMs to streamline the structuring of unstructured clinical text into usable data with standardized format. GENIE processes entire paragraphs in a single pass, extracting entities, assertion statuses, locations, modifiers, values, and purposes with high accuracy. Its unified, end-to-end approach simplifies workflows, reduces errors, and eliminates the need for extensive manual intervention. Using a robust data preparation pipeline and fine-tuned small scale LLMs, GENIE achieves competitive performance across multiple information extraction tasks, outperforming traditional tools like cTAKES and MetaMap and can handle extra attributes to be extracted. GENIE strongly enhances real-world applicability and scalability in healthcare systems. By open-sourcing the model and test data, we aim to encourage collaboration and drive further advancements in EHR structurization.

[Arxiv](https://arxiv.org/abs/2501.18435)