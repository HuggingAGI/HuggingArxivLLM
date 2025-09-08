# 利用大型语言模型（LLMs）实现多语言临床实体链接至ICD-10

发布时间：2025年09月05日

`LLM应用` `医疗健康`

> Using LLMs for Multilingual Clinical Entity Linking to ICD-10

# 摘要

> 临床实体链接是从临床文本中提取结构化信息的关键环节。具体而言，就是为文本中的短语匹配医学本体或分类体系中的对应编码。国际疾病分类第10版（ICD-10）作为疾病分类的国际标准，广泛应用于统计与医保领域。若能自动为出院小结中的术语匹配正确的ICD-10编码，不仅能减轻医护人员的工作负担，还能确保医院编码的规范性。本文提出了一种基于大型语言模型（LLMs）的跨语言临床术语ICD-10编码链接方法。该方法采用多阶段处理流程：首先通过临床词典匹配文本中的明确术语，对于词典未覆盖的术语，则借助GPT-4.1的上下文学习能力预测其ICD-10编码。实验结果表明，该系统在多语言基准数据集上表现优异：西班牙语CodiEsp数据集的类别F1值达0.89、子类别0.78，希腊语ElCardioCC数据集的F1值为0.85。

> The linking of clinical entities is a crucial part of extracting structured information from clinical texts. It is the process of assigning a code from a medical ontology or classification to a phrase in the text. The International Classification of Diseases - 10th revision (ICD-10) is an international standard for classifying diseases for statistical and insurance purposes. Automatically assigning the correct ICD-10 code to terms in discharge summaries will simplify the work of healthcare professionals and ensure consistent coding in hospitals. Our paper proposes an approach for linking clinical terms to ICD-10 codes in different languages using Large Language Models (LLMs). The approach consists of a multistage pipeline that uses clinical dictionaries to match unambiguous terms in the text and then applies in-context learning with GPT-4.1 to predict the ICD-10 code for the terms that do not match the dictionary. Our system shows promising results in predicting ICD-10 codes on different benchmark datasets in Spanish - 0.89 F1 for categories and 0.78 F1 on subcategories on CodiEsp, and Greek - 0.85 F1 on ElCardioCC.

[Arxiv](https://arxiv.org/abs/2509.04868)