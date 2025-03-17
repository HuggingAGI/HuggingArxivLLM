# 提升ESGLLM检索能力的ESG-CID方法——用于GRI与ESRS映射的披露内容索引微调数据集

发布时间：2025年03月10日

`LLM应用

理由：该论文探讨了如何利用检索增强生成（RAG）系统来自动化生成环境、社会和治理（ESG）报告。它详细描述了数据集的构建、模型的微调以及实验结果，这些都是LLM在实际应用中的具体实施和优化，因此归类为LLM应用。` `ESG报告` `可持续发展`

> Enhancing Retrieval for ESGLLM via ESG-CID -- A Disclosure Content Index Finetuning Dataset for Mapping GRI and ESRS

# 摘要

> 气候变化加剧了组织对透明度和问责的需求，使环境、社会和治理（ESG）报告变得愈发重要。全球报告倡议（GRI）和新欧洲可持续性报告标准（ESRS）等框架致力于标准化ESG报告，但生成全面报告仍面临挑战，原因在于ESG文件篇幅较长且公司报告风格不一。为了实现ESG报告的自动化，检索增强生成（RAG）系统是一个可行方案，但其开发受限于缺乏适合训练检索模型的标注数据。本文创新性地利用了以往ESG报告中未被充分利用的披露内容索引，构建了一个全面的数据集ESG-CID，涵盖GRI和ESRS两大标准。通过提取具体披露要求与报告相应部分的映射关系，并借助大型语言模型进行优化，我们生成了一个强大且实用的训练和评估集。我们在该数据集上对主流嵌入模型进行了基准测试，结果表明，经过微调的基于BERT的模型不仅能够超越商业嵌入和领先公共模型的性能，甚至在跨报告风格迁移（从GRI到ESRS）的时序数据划分下表现更优。


> Climate change has intensified the need for transparency and accountability in organizational practices, making Environmental, Social, and Governance (ESG) reporting increasingly crucial. Frameworks like the Global Reporting Initiative (GRI) and the new European Sustainability Reporting Standards (ESRS) aim to standardize ESG reporting, yet generating comprehensive reports remains challenging due to the considerable length of ESG documents and variability in company reporting styles. To facilitate ESG report automation, Retrieval-Augmented Generation (RAG) systems can be employed, but their development is hindered by a lack of labeled data suitable for training retrieval models. In this paper, we leverage an underutilized source of weak supervision -- the disclosure content index found in past ESG reports -- to create a comprehensive dataset, ESG-CID, for both GRI and ESRS standards. By extracting mappings between specific disclosure requirements and corresponding report sections, and refining them using a Large Language Model as a judge, we generate a robust training and evaluation set. We benchmark popular embedding models on this dataset and show that fine-tuning BERT-based models can outperform commercial embeddings and leading public models, even under temporal data splits for cross-report style transfer from GRI to ESRS

[Arxiv](https://arxiv.org/abs/2503.10674)