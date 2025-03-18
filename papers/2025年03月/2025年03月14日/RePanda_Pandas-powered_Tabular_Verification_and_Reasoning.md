# RePanda：基于Pandas的高效表格验证与推理工具

发布时间：2025年03月14日

`LLM应用` `数据验证` `表格处理`

> RePanda: Pandas-powered Tabular Verification and Reasoning

# 摘要

> 对表格数据进行事实核查，是确保结构化信息准确性的重要手段。然而，现有方法往往依赖于黑箱模型，其推理过程难以理解。我们引入了RePanda，一种结构化事实验证方法，它将声明转化为可执行的Pandas查询，从而实现可解释且可验证的推理。
    为了训练RePanda，我们构建了PanTabFact，这是一个从TabFact训练集中衍生而来的结构化数据集。在该数据集中，声明与通过DeepSeek-Chat生成并经过自动化错误修正的可执行查询配对。在PanTabFact上对DeepSeek-coder-7B-instruct-v1.5进行微调后，RePanda在TabFact测试集上达到了84.09%的准确率。
    为了评估其在分布外（OOD）场景下的泛化能力，我们将WikiTableQuestions中的问答对解释为事实声明，并将该数据集称为WikiFact。在没有额外微调的情况下，RePanda在WikiFact上达到了84.72%的准确率，显著优于所有其他基线方法，展现了强大的OOD鲁棒性。值得注意的是，这些结果与DeepSeek-Chat（671B）的零样本性能非常接近，表明我们的微调方法成功地将来自更大模型的结构化推理能力提炼到一个紧凑且本地可执行的7B模型中。
    除了事实验证，RePanda还扩展到了表格问答任务，通过生成可执行查询来检索精确答案。为此，我们引入了PanWiki，这是一个将WikiTableQuestions映射到Pandas查询的数据集。在PanWiki上进行微调后，RePanda在直接答案检索方面达到了75.1%的准确率。这些结果突显了基于结构化执行的推理方法在表格验证和问答任务中的有效性。
    我们已在Hugging Face平台上公开发布了该数据集，地址为datasets/AtoosaChegini/PanTabFact。
    

> Fact-checking tabular data is essential for ensuring the accuracy of structured information. However, existing methods often rely on black-box models with opaque reasoning. We introduce RePanda, a structured fact verification approach that translates claims into executable pandas queries, enabling interpretable and verifiable reasoning.
  To train RePanda, we construct PanTabFact, a structured dataset derived from the TabFact train set, where claims are paired with executable queries generated using DeepSeek-Chat and refined through automated error correction. Fine-tuning DeepSeek-coder-7B-instruct-v1.5 on PanTabFact, RePanda achieves 84.09% accuracy on the TabFact test set.
  To evaluate Out-of-Distribution (OOD) generalization, we interpret question-answer pairs from WikiTableQuestions as factual claims and refer to this dataset as WikiFact. Without additional fine-tuning, RePanda achieves 84.72% accuracy on WikiFact, significantly outperforming all other baselines and demonstrating strong OOD robustness. Notably, these results closely match the zero-shot performance of DeepSeek-Chat (671B), indicating that our fine-tuning approach effectively distills structured reasoning from a much larger model into a compact, locally executable 7B model.
  Beyond fact verification, RePanda extends to tabular question answering by generating executable queries that retrieve precise answers. To support this, we introduce PanWiki, a dataset mapping WikiTableQuestions to pandas queries. Fine-tuning on PanWiki, RePanda achieves 75.1% accuracy in direct answer retrieval. These results highlight the effectiveness of structured execution-based reasoning for tabular verification and question answering.
  We have publicly released the dataset on Hugging Face at datasets/AtoosaChegini/PanTabFact.

[Arxiv](https://arxiv.org/abs/2503.11921)