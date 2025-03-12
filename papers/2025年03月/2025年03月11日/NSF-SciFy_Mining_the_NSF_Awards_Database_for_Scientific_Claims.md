# NSF-SciFy: 挖掘NSF奖项数据库中的科学主张

发布时间：2025年03月11日

`LLM应用

摘要：这篇论文介绍了NSF-SciFy数据集，并展示了如何利用大型语言模型进行科学声明提取和研究提案提取等任务，属于LLM的应用层面。` `科学资助` `研究管理`

> NSF-SciFy: Mining the NSF Awards Database for Scientific Claims

# 摘要

> 我们推出 NSF-SciFy，这是一个从美国国家科学基金会（NSF）的奖项数据库中提取的大型科学声明数据集，包含超过40万份跨度五十年的提案摘要。与依赖已发表文献的现有数据集不同，我们利用提案摘要，这具有独特的优势：它们在研究生命周期的早期阶段捕捉声明，早于发表生效。我们还引入了一个新任务，用于区分提案中的现有科学声明与 aspirational 研究意图。利用前沿大型语言模型的零样本提示，我们从材料科学领域的16,000份提案摘要中共同提取了114,000个科学声明和145,000个研究提案，构建了一个专注于材料科学领域的子集，命名为NSF-SciFy-MatSci。我们使用此数据集评估三个关键任务：（1）技术性与非技术性摘要生成，其中模型实现了高BERTScore（0.85+ F1）；（2）科学声明提取，其中微调模型比基础模型性能提升了100%；（3）研究提案提取，微调后模型性能提升了90%以上。我们引入了新颖的基于LLM的评估指标，以 robustly 评估声明/提案提取的质量。作为迄今为止最大的科学声明数据集——NSF资助的所有STEM学科中估计包含280万个声明——NSF-SciFy为声明验证和元科学研究提供了新的机遇。我们公开发布了所有数据集、训练好的模型和评估代码，以促进进一步研究。

> We present NSF-SciFy, a large-scale dataset for scientific claim extraction derived from the National Science Foundation (NSF) awards database, comprising over 400K grant abstracts spanning five decades. While previous datasets relied on published literature, we leverage grant abstracts which offer a unique advantage: they capture claims at an earlier stage in the research lifecycle before publication takes effect. We also introduce a new task to distinguish between existing scientific claims and aspirational research intentions in proposals.Using zero-shot prompting with frontier large language models, we jointly extract 114K scientific claims and 145K investigation proposals from 16K grant abstracts in the materials science domain to create a focused subset called NSF-SciFy-MatSci. We use this dataset to evaluate 3 three key tasks: (1) technical to non-technical abstract generation, where models achieve high BERTScore (0.85+ F1); (2) scientific claim extraction, where fine-tuned models outperform base models by 100% relative improvement; and (3) investigation proposal extraction, showing 90%+ improvement with fine-tuning. We introduce novel LLM-based evaluation metrics for robust assessment of claim/proposal extraction quality. As the largest scientific claim dataset to date -- with an estimated 2.8 million claims across all STEM disciplines funded by the NSF -- NSF-SciFy enables new opportunities for claim verification and meta-scientific research. We publicly release all datasets, trained models, and evaluation code to facilitate further research.

[Arxiv](https://arxiv.org/abs/2503.08600)