# MMRAG：多模态检索增强生成在生物医学上下文学习中的大型语言模型应用

发布时间：2025年02月21日

`RAG` `生物医学`

> MMRAG: Multi-Mode Retrieval-Augmented Generation with Large Language Models for Biomedical In-Context Learning

# 摘要

> # 摘要  
目标：通过改进示例选择，优化生物医学自然语言处理中的上下文学习。  
方法：我们引入了一种新型的多模式检索增强生成（MMRAG）框架，该框架集成了四种检索策略：（1）随机模式，任意选择示例；（2）Top模式，基于相似度检索最相关的示例；（3）多样性模式，确保所选示例的多样性；（4）类别模式，选择具有代表性的类别示例。  
本研究在三个核心生物医学NLP任务上评估了MMRAG：命名实体识别（NER）、关系抽取（RE）和文本分类（TC）。使用的数据集包括用于基因和蛋白质识别的BC2GM（NER任务）、用于药物相互作用抽取的DDI（RE任务）、用于一般生物医学信息抽取的GIT（RE任务）以及用于健康相关文本分类的HealthAdvice（TC任务）。  
该框架分别使用了两个大型语言模型（Llama2-7B、Llama3-8B）和三个检索器（Contriever、MedCPT、BGE-Large）进行测试，以评估不同检索策略的性能。  
结果：Random模式的结果表明，增加提示中的示例数量可以提升模型的生成性能。同时，Top模式和Diversity模式在DDI关系抽取任务中显著优于Random模式，F1值达到0.9669，提升了26.4%。在测试的三个检索器中，Contriever在更多的实验中表现优于另外两个。此外，Llama 2和Llama 3在不同任务中表现出不同的能力，其中Llama 3在NER任务中表现出了明显的优势。  
结论：MMRAG通过优化示例选择，有效提升了生物医学上下文学习的效果，缓解了数据稀缺问题，并在NLP驱动的医疗应用中展现了卓越的适应能力。

> Objective: To optimize in-context learning in biomedical natural language processing by improving example selection. Methods: We introduce a novel multi-mode retrieval-augmented generation (MMRAG) framework, which integrates four retrieval strategies: (1) Random Mode, selecting examples arbitrarily; (2) Top Mode, retrieving the most relevant examples based on similarity; (3) Diversity Mode, ensuring variation in selected examples; and (4) Class Mode, selecting category-representative examples. This study evaluates MMRAG on three core biomedical NLP tasks: Named Entity Recognition (NER), Relation Extraction (RE), and Text Classification (TC). The datasets used include BC2GM for gene and protein mention recognition (NER), DDI for drug-drug interaction extraction (RE), GIT for general biomedical information extraction (RE), and HealthAdvice for health-related text classification (TC). The framework is tested with two large language models (Llama2-7B, Llama3-8B) and three retrievers (Contriever, MedCPT, BGE-Large) to assess performance across different retrieval strategies. Results: The results from the Random mode indicate that providing more examples in the prompt improves the model's generation performance. Meanwhile, Top mode and Diversity mode significantly outperform Random mode on the RE (DDI) task, achieving an F1 score of 0.9669, a 26.4% improvement. Among the three retrievers tested, Contriever outperformed the other two in a greater number of experiments. Additionally, Llama 2 and Llama 3 demonstrated varying capabilities across different tasks, with Llama 3 showing a clear advantage in handling NER tasks. Conclusion: MMRAG effectively enhances biomedical in-context learning by refining example selection, mitigating data scarcity issues, and demonstrating superior adaptability for NLP-driven healthcare applications.

[Arxiv](https://arxiv.org/abs/2502.15954)