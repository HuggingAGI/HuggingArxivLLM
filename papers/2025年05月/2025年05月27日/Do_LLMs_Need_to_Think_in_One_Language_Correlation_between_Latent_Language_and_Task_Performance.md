# # 摘要  
    大语言模型必须用单一语言思考吗？潜藏语言与任务表现的关系

发布时间：2025年05月27日

`LLM理论` `跨语言处理`

> Do LLMs Need to Think in One Language? Correlation between Latent Language and Task Performance

# 摘要

> 大型语言模型（LLMs）使用一种高效且统一的潜在语言来处理信息，这种潜在语言可能与输入或输出语言不同。然而，潜在语言与输入输出语言之间的差异如何影响下游任务性能，目前研究尚不充分。尽管许多研究探讨了LLMs的潜在语言，但对其在影响任务性能中的重要性关注较少。在本研究中，我们假设始终使用潜在语言进行推理能够提升下游任务性能。为此，我们在多个下游任务中调整输入提示语言，并分析潜在语言一致性与任务性能之间的关联。我们创建了涵盖翻译和地理文化等多个领域的数据集，这些任务会受到潜在语言选择的影响。在翻译和地理文化等对语言选择敏感的任务中，我们对多个LLMs进行了实验。结果表明，保持潜在语言的一致性并非总是能带来最优的下游任务性能。这是因为这些模型会调整其在最终几层的内部表示，以匹配目标语言，从而降低了潜在语言一致性对整体性能的影响。

> Large Language Models (LLMs) are known to process information using a proficient internal language consistently, referred to as latent language, which may differ from the input or output languages. However, how the discrepancy between the latent language and the input and output language affects downstream task performance remains largely unexplored. While many studies research the latent language of LLMs, few address its importance in influencing task performance. In our study, we hypothesize that thinking in latent language consistently enhances downstream task performance. To validate this, our work varies the input prompt languages across multiple downstream tasks and analyzes the correlation between consistency in latent language and task performance. We create datasets consisting of questions from diverse domains such as translation and geo-culture, which are influenced by the choice of latent language. Experimental results across multiple LLMs on translation and geo-culture tasks, which are sensitive to the choice of language, indicate that maintaining consistency in latent language is not always necessary for optimal downstream task performance. This is because these models adapt their internal representations near the final layers to match the target language, reducing the impact of consistency on overall performance.

[Arxiv](https://arxiv.org/abs/2505.21458)