# NyayaAnumana 与 INLegalLlama：规模最大的印度法律判决预测数据集以及用于强化决策分析的专业语言模型

发布时间：2024年12月11日

`LLM应用` `人工智能`

> NyayaAnumana & INLegalLlama: The Largest Indian Legal Judgment Prediction Dataset and Specialized Language Model for Enhanced Decision Analysis

# 摘要

> 人工智能（AI）在法律判决预测（LJP）中的融合，有望改变法律领域的局面，尤其在印度这类案件大量积压、法律系统负担沉重的司法管辖区。本文介绍了 NyayaAnumana，这是为 LJP 整理的规模最大、种类最多的印度法律案件语料库，总计涵盖 702,945 个预处理案件。NyayaAnumana 分别融合了多数主要印度语言中的“Nyay”（判决）和“Anuman”（预测或推断）这两个词，涵盖了来自最高法院、高等法院、法庭法院、地区法院以及日常命令等的各类案件，从而提供了无可比拟的多样性和覆盖面。我们的数据集优于 PredEx 和 ILDC 等现有数据集，为法律领域的高级人工智能研究奠定了全面的基础。
  除了数据集，我们还推出了 INLegalLlama，这是一个专为印度法律系统的复杂性而定制的特定领域生成式大型语言模型（LLM）。它通过在基础 LLaMa 模型上采用两阶段训练方法开发而成。首先，通过持续预训练注入印度法律文件。其次，进行特定任务的监督微调。这种方法使模型能够更深入地理解法律情境。
  我们的实验表明，纳入多样化的法院数据显著提升了模型的准确性，在预测任务中实现了约 90％的 F1 分数。INLegalLlama 不仅提高了预测准确性，还提供了易于理解的解释，满足了人工智能辅助法律决策中对可解释性的需求。

> The integration of artificial intelligence (AI) in legal judgment prediction (LJP) has the potential to transform the legal landscape, particularly in jurisdictions like India, where a significant backlog of cases burdens the legal system. This paper introduces NyayaAnumana, the largest and most diverse corpus of Indian legal cases compiled for LJP, encompassing a total of 7,02,945 preprocessed cases. NyayaAnumana, which combines the words "Nyay" (judgment) and "Anuman" (prediction or inference) respectively for most major Indian languages, includes a wide range of cases from the Supreme Court, High Courts, Tribunal Courts, District Courts, and Daily Orders and, thus, provides unparalleled diversity and coverage. Our dataset surpasses existing datasets like PredEx and ILDC, offering a comprehensive foundation for advanced AI research in the legal domain.
  In addition to the dataset, we present INLegalLlama, a domain-specific generative large language model (LLM) tailored to the intricacies of the Indian legal system. It is developed through a two-phase training approach over a base LLaMa model. First, Indian legal documents are injected using continual pretraining. Second, task-specific supervised finetuning is done. This method allows the model to achieve a deeper understanding of legal contexts.
  Our experiments demonstrate that incorporating diverse court data significantly boosts model accuracy, achieving approximately 90% F1-score in prediction tasks. INLegalLlama not only improves prediction accuracy but also offers comprehensible explanations, addressing the need for explainability in AI-assisted legal decisions.

[Arxiv](https://arxiv.org/abs/2412.08385)