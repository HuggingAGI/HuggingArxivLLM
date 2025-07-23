# 关注差距：评估医学语言推理 LLM 基准在非洲疾病负担中的代表性如何

发布时间：2025年07月22日

`LLM应用` `非洲医疗`

> Mind the Gap: Evaluating the Representativeness of Quantitative Medical Language Reasoning LLM Benchmarks for African Disease Burdens

# 摘要

> 引言：当前医疗LLM评估基准主要基于高收入国家的考试大纲和疾病谱，这引发了它们在非洲适用性的问题。疟疾、艾滋病、结核病、镰状细胞病和其他被忽视的热带疾病（NTDs）在非洲占据主导地位，而国家指南则主导着医疗实践。

方法：我们系统性地审查了2019年1月至2025年5月间的31篇定量LLM评估论文，识别出19个英文医疗问答基准。Alama Health QA基于肯尼亚临床实践指南，采用检索增强生成框架开发。我们选取六种常用基准（AfriMedQA、MMLUMedical、PubMedQA、MedMCQA、MedQAUSMLE以及基于指南的Alama Health QA），从语义特征（NTD比例、时效性、可读性、词汇多样性）和专家盲评（临床相关性、指南一致性、清晰度、干扰项合理性、语言/文化适配性）两个维度进行了统一分析。

结果：Alama Health QA涵盖了所有语料库中超过40%的NTD提及，并在疟疾（7.7%）、艾滋病（4.1%）和结核病（5.2%）方面拥有最高频率；AfriMedQA排名第二，但缺乏正式的指南链接。全球性基准尽管规模庞大，却对某些疾病代表性极低（例如，镰状细胞病在三个基准中缺失）。定性分析显示，Alama在相关性和指南一致性方面表现最佳；PubMedQA在临床实用性方面表现最弱。

讨论：现有广泛应用于文献中的定量医疗LLM基准严重低估了非洲地区的疾病负担和监管环境，可能导致性能声称的误导。基于指南、地区精选的资源（如Alama Health QA和扩展的疾病特定衍生基准）对于在非洲卫生系统中安全、公平地进行模型评估和部署至关重要。


> Introduction: Existing medical LLM benchmarks largely reflect examination syllabi and disease profiles from high income settings, raising questions about their validity for African deployment where malaria, HIV, TB, sickle cell disease and other neglected tropical diseases (NTDs) dominate burden and national guidelines drive care. Methodology: We systematically reviewed 31 quantitative LLM evaluation papers (Jan 2019 May 2025) identifying 19 English medical QA benchmarks. Alama Health QA was developed using a retrieval augmented generation framework anchored on the Kenyan Clinical Practice Guidelines. Six widely used sets (AfriMedQA, MMLUMedical, PubMedQA, MedMCQA, MedQAUSMLE, and guideline grounded Alama Health QA) underwent harmonized semantic profiling (NTD proportion, recency, readability, lexical diversity metrics) and blinded expert rating across five dimensions: clinical relevance, guideline alignment, clarity, distractor plausibility, and language/cultural fit. Results: Alama Health QA captured >40% of all NTD mentions across corpora and the highest within set frequencies for malaria (7.7%), HIV (4.1%), and TB (5.2%); AfriMedQA ranked second but lacked formal guideline linkage. Global benchmarks showed minimal representation (e.g., sickle cell disease absent in three sets) despite large scale. Qualitatively, Alama scored highest for relevance and guideline alignment; PubMedQA lowest for clinical utility. Discussion: Quantitative medical LLM benchmarks widely used in the literature underrepresent African disease burdens and regulatory contexts, risking misleading performance claims. Guideline anchored, regionally curated resources such as Alama Health QA and expanded disease specific derivatives are essential for safe, equitable model evaluation and deployment across African health systems.

[Arxiv](https://arxiv.org/abs/2507.16322)