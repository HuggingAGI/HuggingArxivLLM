# # LLM作为裁判：重新评估其在抽取式问答中的表现

发布时间：2025年04月16日

`LLM应用` `问答系统`

> LLM-as-a-Judge: Reassessing the Performance of LLMs in Extractive QA

# 摘要

> 抽取式阅读理解问答（QA）数据集通常使用精确匹配（EM）和F1分数进行评估，但这些指标往往无法全面反映模型的真实表现。随着大型语言模型（LLMs）的成功，它们被应用于各种任务，包括作为评估者（LLM-as-a-judge）。本文中，我们使用LLM-as-a-judge重新评估了四个阅读理解QA数据集中的问答模型性能。我们研究了不同家族的LLMs和各种答案类型，以评估LLM-as-a-judge在这些任务中的有效性。我们的结果显示，LLM-as-a-judge与人类判断高度相关，可以替代传统的EM/F1指标。通过使用LLM-as-a-judge，与人类判断的相关性显著提高，从0.17（EM）和0.36（F1分数）提升至0.85。这些发现证实了EM和F1指标低估了问答模型的真实性能。尽管LLM-as-a-judge在更复杂的答案类型（例如“职业”）上并非完美，但它仍然优于EM/F1，而且我们观察到当同一模型用于问答和评估任务时，不存在自我偏好等偏见问题。

> Extractive reading comprehension question answering (QA) datasets are typically evaluated using Exact Match (EM) and F1-score, but these metrics often fail to fully capture model performance. With the success of large language models (LLMs), they have been employed in various tasks, including serving as judges (LLM-as-a-judge). In this paper, we reassess the performance of QA models using LLM-as-a-judge across four reading comprehension QA datasets. We examine different families of LLMs and various answer types to evaluate the effectiveness of LLM-as-a-judge in these tasks. Our results show that LLM-as-a-judge is highly correlated with human judgments and can replace traditional EM/F1 metrics. By using LLM-as-a-judge, the correlation with human judgments improves significantly, from 0.17 (EM) and 0.36 (F1-score) to 0.85. These findings confirm that EM and F1 metrics underestimate the true performance of the QA models. While LLM-as-a-judge is not perfect for more difficult answer types (e.g., job), it still outperforms EM/F1, and we observe no bias issues, such as self-preference, when the same model is used for both the QA and judgment tasks.

[Arxiv](https://arxiv.org/abs/2504.11972)