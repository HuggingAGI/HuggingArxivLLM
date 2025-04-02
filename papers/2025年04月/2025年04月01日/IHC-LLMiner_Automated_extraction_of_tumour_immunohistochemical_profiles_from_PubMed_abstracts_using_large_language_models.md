# # IHC-LLMiner：从PubMed摘要中自动提取肿瘤免疫组化特征，助力精准医疗研究，借助大型语言模型实现高效分析

发布时间：2025年04月01日

`LLM应用` `肿瘤学`

> IHC-LLMiner: Automated extraction of tumour immunohistochemical profiles from PubMed abstracts using large language models

# 摘要

> 免疫组织化学（IHC）在诊断病理学和生物医学研究中发挥着关键作用，为蛋白质表达和肿瘤生物学研究提供了重要见解。本研究开发了一种名为IHC-LLMiner的自动化工具，利用先进的生物医学文本挖掘技术，从PubMed摘要中提取IHC-肿瘤概况。该工具包含两个核心任务：摘要分类（判断是否相关）和在相关摘要中提取IHC-肿瘤概况。其中，"Gemma-2微调版"模型表现最为突出，达到了91.5%的准确率和91.4的F1分数，较GPT4-O在准确率上高出9.5%，推理速度更是快了5.9倍。通过对50个免疫组化标记的107,759篇摘要进行筛选，Gemma-2微调版模型成功识别出30,481篇相关摘要。在IHC-肿瘤概况提取任务中，该模型实现了63.3%的正确输出率。提取的IHC-肿瘤概况（包括肿瘤类型和标记物）被标准化为统一医学语言系统（UMLS）概念，以确保数据的一致性并便于后续分析。这些提取的概况与现有在线汇总数据高度一致，同时在补充缺失的IHC-肿瘤概况和提供定量评估方面具有显著价值。我们的基于LLM的工具为大规模IHC-肿瘤概况数据挖掘提供了一种高效解决方案，不仅提升了数据在研究和临床中的可访问性和实用性，还支持生成结构化和定量数据，从而推动癌症相关知识库的建设。相关模型和训练数据已在GitHub上公开，地址为https://github.com/knowlab/IHC-LLMiner。

> Immunohistochemistry (IHC) is essential in diagnostic pathology and biomedical research, offering critical insights into protein expression and tumour biology. This study presents an automated pipeline, IHC-LLMiner, for extracting IHC-tumour profiles from PubMed abstracts, leveraging advanced biomedical text mining. There are two subtasks: abstract classification (include/exclude as relevant) and IHC-tumour profile extraction on relevant included abstracts. The best-performing model, "Gemma-2 finetuned", achieved 91.5% accuracy and an F1 score of 91.4, outperforming GPT4-O by 9.5% accuracy with 5.9 times faster inference time. From an initial dataset of 107,759 abstracts identified for 50 immunohistochemical markers, the classification task identified 30,481 relevant abstracts (Include) using the Gemma-2 finetuned model. For IHC-tumour profile extraction, the Gemma-2 finetuned model achieved the best performance with 63.3% Correct outputs. Extracted IHC-tumour profiles (tumour types and markers) were normalised to Unified Medical Language System (UMLS) concepts to ensure consistency and facilitate IHC-tumour profile landscape analysis. The extracted IHC-tumour profiles demonstrated excellent concordance with available online summary data and provided considerable added value in terms of both missing IHC-tumour profiles and quantitative assessments. Our proposed LLM based pipeline provides a practical solution for large-scale IHC-tumour profile data mining, enhancing the accessibility and utility of such data for research and clinical applications as well as enabling the generation of quantitative and structured data to support cancer-specific knowledge base development. Models and training datasets are available at https://github.com/knowlab/IHC-LLMiner.

[Arxiv](https://arxiv.org/abs/2504.00748)